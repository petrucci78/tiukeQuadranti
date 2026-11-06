# Schema F (DB2 for z/OS) – infrastruttura di replica e EXPLAIN

Lo schema **F** non contiene dati applicativi: contiene le tabelle di servizio di **IBM SQL Replication (Capture)**, le tabelle **EXPLAIN** e alcune viste sul catalogo.

> Negli export il creator compare sia come `F` sia come `F       ` (con spazi): in DB2 il confronto `= 'F'` li prende entrambi.

## Contenuto

| Gruppo | Oggetti | Cosa sono |
|---|---:|---|
| `ASN_<TABELLA>_CD` / `_CD5` | 251 tabelle | **Change Data**: ogni riga è una modifica (insert/update/delete) catturata dal log sulla tabella sorgente |
| `DSN_*_TABLE`, `PLAN_TABLE` | 27 tabelle + 5 LOB | Tabelle EXPLAIN (piani di accesso, costi, statement cache) |
| `BJSYS*`, `NRTAB`, `VWCOL`, `V_AUTH`, `V_DBAUTH`, `V_OGGETTOPLAN`, `V_PLANOGGETTO` | 16 viste | Viste sul catalogo DB2 (package, plan, tabelle, autorizzazioni) |

File: `dizionario.md` (tutte le colonne e indici), `cd_fjbm.md` (le 26 tabelle CD che replicano tabelle FJBM), `raw_*.csv`.

## Come leggere una tabella CD

Struttura: colonne `IBMSNAP_*`, poi le colonne `X<TABELLA>_<CHIAVE>` (before-image della chiave), poi tutte le colonne della tabella sorgente (after-image).

| Colonna | Significato |
|---|---|
| `IBMSNAP_COMMITSEQ` | Sequenza di commit (LSN) – ordina le transazioni |
| `IBMSNAP_INTENTSEQ` | Sequenza della singola modifica nella transazione |
| `IBMSNAP_OPERATION` | `I` insert, `U` update, `D` delete |
| `IBMSNAP_LOGMARKER` | Timestamp del commit (presente in 111 tabelle CD su 251) |
| `X<TAB>_<COL>` | Valore della chiave **prima** della modifica (es. `XANCLI_CODANA`) |

Le tabelle CD vengono svuotate (pruning) dopo che l'Apply ha replicato le modifiche: contengono solo le modifiche recenti e non ancora consumate, per questo hanno pochissime righe.

Uso nei ticket: capire **se e quando** una riga FJBM è stata toccata e con che valori, prima che il pruning la cancelli.

```sql
SELECT IBMSNAP_LOGMARKER, IBMSNAP_OPERATION, XANCLI_CODANA, ANCLI_CODANA, ANCLI_CDFIS
FROM F.ASN_ANCLI_CD5
WHERE ANCLI_CODANA = '000000000000'
ORDER BY IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ;
```

**Non modificare mai le tabelle CD**: sono gestite da Capture/Apply.

## Sorgenti

- 26 tabelle CD replicano tabelle **FJBM** (anagrafica `ANCLI`, `ANIND`, `ANDOC`, `ANPRI`, `ANSER`, contratti `ANCON`, rete `ACLN`, `ANRETE`, e varianti `M`/`SPI`).
- Le altre 225 replicano tabelle di **altri schemi** (agenti `AG*`, prodotti, portafogli `PT*`, quote `QUOTE*`, polizze, provvigioni…): per sapere quali, interrogare il registro di Capture:

```sql
SELECT SOURCE_OWNER, SOURCE_TABLE, CD_OWNER, CD_TABLE, STATE
FROM ASN.IBMSNAP_REGISTER
ORDER BY SOURCE_OWNER, SOURCE_TABLE;
```

(lo schema del registro potrebbe non essere `ASN`: cercarlo con `SELECT CREATOR FROM SYSIBM.SYSTABLES WHERE NAME = 'IBMSNAP_REGISTER'`).
