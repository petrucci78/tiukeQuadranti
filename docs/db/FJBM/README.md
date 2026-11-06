# Schema FJBM (DB2 for z/OS) – riferimento per la risoluzione ticket

> Nota: negli export il creator risulta **`FJBM`** (non FJDM).

## Contenuto

| File | Cosa contiene |
|---|---|
| `dizionario.md` | Tutte le 574 tabelle/viste: descrizione, righe (statistiche `CARDF`), colonne con tipo/null/default/descrizione, indici |
| `chiavi_logiche.md` | Dove compaiono le colonne chiave trasversali (`*_CODANA`, `*_CODAGE`, `*_CDFIS`, `*_NDG`, `*_CODCONF`, `*_CONTO`, …) |
| `raw_colonne.csv`, `raw_indici.csv` | Export originali (separatore `;`) |

## Numeri

- 527 tabelle (`T`), 33 viste (`V`), 14 tabelle ausiliarie LOB (`X`) – 11.507 colonne
- 2.338 righe di indice: 44 primary key, 933 unique, 1.361 non unici; 13 tabelle senza indici
- **Nessuna foreign key dichiarata**: integrità referenziale gestita dai programmi applicativi
- Convenzione nomi colonna: `<TABELLA>_<CAMPO>` (es. `ANCLI_CODANA`)
- Date spesso in `INTEGER`/`DECIMAL(9,0)` formato `AAAAMMGG`, non `DATE`
- Molte tabelle hanno campi di audit: `*_UTENTE`, `*_PGM`, `*_TERM`, `*_DATA`, `*_ORA`, `*_TIPAGG`

## Ancora da recuperare

1. **Testo delle viste** – l'export di `SYSVIEWS.STATEMENT` è arrivato vuoto (CLOB). Usare:
   ```sql
   SELECT NAME AS VISTA, SEQNO,
          CAST(SUBSTR(STATEMENT, 1, 32000) AS VARCHAR(32000)) AS TESTO
   FROM SYSIBM.SYSVIEWS
   WHERE CREATOR = 'FJBM'
   ORDER BY NAME, SEQNO;
   ```
   In DbVisualizer: Tools > Tool Properties > Data Formats/Grid, aumentare "Max chars to display" per i CLOB, oppure esportare in CSV/testo invece che Excel.
2. **Dipendenze viste → tabelle**:
   ```sql
   SELECT DNAME AS VISTA, BCREATOR, BNAME AS OGGETTO_BASE, BTYPE
   FROM SYSIBM.SYSVIEWDEP
   WHERE DCREATOR = 'FJBM'
   ORDER BY DNAME, BNAME;
   ```
3. (Utile) **Trigger**, che spesso spiegano aggiornamenti "fantasma":
   ```sql
   SELECT TBNAME, NAME, TRIGTIME, TRIGEVENT, GRANULARITY, TEXT
   FROM SYSIBM.SYSTRIGGERS
   WHERE TBOWNER = 'FJBM'
   ORDER BY TBNAME, NAME;
   ```
4. (Utile) **Package/programmi che usano ogni tabella** (i nomi in `*_PGM`):
   ```sql
   SELECT BNAME AS TABELLA, DCOLLID, DNAME AS PACKAGE
   FROM SYSIBM.SYSPACKDEP
   WHERE BQUALIFIER = 'FJBM' AND BTYPE IN ('T','V')
   ORDER BY BNAME, DNAME;
   ```

Consiglio per gli export: da DbVisualizer esportare in **CSV** (non Excel), così i campi lunghi non vengono troncati.
