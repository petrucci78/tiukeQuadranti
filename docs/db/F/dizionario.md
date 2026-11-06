# Schema F – Dizionario dati completo

Generato da `SYSIBM.SYSCOLUMNS`/`SYSTABLES` e `SYSIBM.SYSINDEXES`/`SYSKEYS`. Righe `n.d.` = statistiche mai raccolte (`CARDF = -1`).

## Indice oggetti

| Oggetto | Tipo | Righe (stat.) | Tabella sorgente |
|---|---|---:|---|
| [ASN_ACFM_CD5](#asn_acfm_cd5) | T | n.d. | `ACFM` (altro schema) |
| [ASN_ACLNM_CD](#asn_aclnm_cd) | T | 4 | `FJBM.ACLNM` |
| [ASN_ACLNSPI_CD](#asn_aclnspi_cd) | T | 11 | `FJBM.ACLNSPI` |
| [ASN_ACLN_CD5](#asn_acln_cd5) | T | 0 | `FJBM.ACLN` |
| [ASN_ACODISPI_CD](#asn_acodispi_cd) | T | 0 | `ACODISPI` (altro schema) |
| [ASN_ACODI_CD](#asn_acodi_cd) | T | 0 | `ACODI` (altro schema) |
| [ASN_AEAM_CD](#asn_aeam_cd) | T | 0 | `AEAM` (altro schema) |
| [ASN_AEASPI_CD](#asn_aeaspi_cd) | T | 2 | `AEASPI` (altro schema) |
| [ASN_AEA_CD5](#asn_aea_cd5) | T | 0 | `AEA` (altro schema) |
| [ASN_AG2M_CD](#asn_ag2m_cd) | T | 0 | `AG2M` (altro schema) |
| [ASN_AG2SPI_CD](#asn_ag2spi_cd) | T | 2 | `AG2SPI` (altro schema) |
| [ASN_AG2_CD](#asn_ag2_cd) | T | 22 | `AG2` (altro schema) |
| [ASN_AG3M_CD](#asn_ag3m_cd) | T | 3 | `AG3M` (altro schema) |
| [ASN_AG3SPI_CD](#asn_ag3spi_cd) | T | 10 | `AG3SPI` (altro schema) |
| [ASN_AG3_CD5](#asn_ag3_cd5) | T | 0 | `AG3` (altro schema) |
| [ASN_AG4M_CD](#asn_ag4m_cd) | T | 4 | `AG4M` (altro schema) |
| [ASN_AG4SPI_CD](#asn_ag4spi_cd) | T | 14 | `AG4SPI` (altro schema) |
| [ASN_AG4_CD5](#asn_ag4_cd5) | T | 0 | `AG4` (altro schema) |
| [ASN_AG5M_CD](#asn_ag5m_cd) | T | 3 | `AG5M` (altro schema) |
| [ASN_AG5SPI_CD](#asn_ag5spi_cd) | T | 2 | `AG5SPI` (altro schema) |
| [ASN_AG5_CD](#asn_ag5_cd) | T | 14 | `AG5` (altro schema) |
| [ASN_AGLIVPRO_CD](#asn_aglivpro_cd) | T | 0 | `AGLIVPRO` (altro schema) |
| [ASN_AGNM_CD](#asn_agnm_cd) | T | 3 | `AGNM` (altro schema) |
| [ASN_AGNSPI_CD](#asn_agnspi_cd) | T | 14 | `AGNSPI` (altro schema) |
| [ASN_AGN_CD5](#asn_agn_cd5) | T | 0 | `AGN` (altro schema) |
| [ASN_AGPSPI_CD](#asn_agpspi_cd) | T | 0 | `AGPSPI` (altro schema) |
| [ASN_AGP_CD](#asn_agp_cd) | T | 0 | `AGP` (altro schema) |
| [ASN_AGSM_CD](#asn_agsm_cd) | T | 0 | `AGSM` (altro schema) |
| [ASN_AGSSPI_CD](#asn_agsspi_cd) | T | 2 | `AGSSPI` (altro schema) |
| [ASN_AGS_CD](#asn_ags_cd) | T | 21 | `AGS` (altro schema) |
| [ASN_AINSSPI_CD](#asn_ainsspi_cd) | T | 5 | `AINSSPI` (altro schema) |
| [ASN_AINS_CD](#asn_ains_cd) | T | 17 | `AINS` (altro schema) |
| [ASN_ALPS_CD](#asn_alps_cd) | T | 0 | `ALPS` (altro schema) |
| [ASN_ALSL_CD](#asn_alsl_cd) | T | 12.016 | `ALSL` (altro schema) |
| [ASN_AMOVST_CD](#asn_amovst_cd) | T | 92 | `AMOVST` (altro schema) |
| [ASN_ANCCM_CD](#asn_anccm_cd) | T | 1 | `ANCCM` (altro schema) |
| [ASN_ANCCSPI_CD](#asn_anccspi_cd) | T | 0 | `ANCCSPI` (altro schema) |
| [ASN_ANCC_CD](#asn_ancc_cd) | T | 12 | `ANCC` (altro schema) |
| [ASN_ANCLIM_CD](#asn_anclim_cd) | T | 55 | `FJBM.ANCLIM` |
| [ASN_ANCLISPI_CD](#asn_anclispi_cd) | T | 58 | `FJBM.ANCLISPI` |
| [ASN_ANCLI_CD5](#asn_ancli_cd5) | T | 0 | `FJBM.ANCLI` |
| [ASN_ANCONM_CD](#asn_anconm_cd) | T | 6 | `FJBM.ANCONM` |
| [ASN_ANCONSPI_CD](#asn_anconspi_cd) | T | 33 | `FJBM.ANCONSPI` |
| [ASN_ANCON_CD5](#asn_ancon_cd5) | T | 0 | `FJBM.ANCON` |
| [ASN_ANDEC_CD](#asn_andec_cd) | T | 0 | `FJBM.ANDEC` |
| [ASN_ANDOCM_CD](#asn_andocm_cd) | T | 19 | `FJBM.ANDOCM` |
| [ASN_ANDOCSPI_CD](#asn_andocspi_cd) | T | 19 | `FJBM.ANDOCSPI` |
| [ASN_ANDOC_CD5](#asn_andoc_cd5) | T | 0 | `FJBM.ANDOC` |
| [ASN_ANINDM_CD](#asn_anindm_cd) | T | 29 | `FJBM.ANINDM` |
| [ASN_ANINDSPI_CD](#asn_anindspi_cd) | T | 25 | `FJBM.ANINDSPI` |
| [ASN_ANIND_CD5](#asn_anind_cd5) | T | 0 | `FJBM.ANIND` |
| [ASN_ANPRIM_CD](#asn_anprim_cd) | T | 3 | `FJBM.ANPRIM` |
| [ASN_ANPRISPI_CD](#asn_anprispi_cd) | T | 9 | `FJBM.ANPRISPI` |
| [ASN_ANPRI_CD](#asn_anpri_cd) | T | 53 | `FJBM.ANPRI` |
| [ASN_ANRETE_CD](#asn_anrete_cd) | T | 7 | `FJBM.ANRETE` |
| [ASN_ANSERM_CD](#asn_anserm_cd) | T | 10 | `FJBM.ANSERM` |
| [ASN_ANSERSPI_CD](#asn_anserspi_cd) | T | 8 | `FJBM.ANSERSPI` |
| [ASN_ANSER_CD](#asn_anser_cd) | T | 36 | `FJBM.ANSER` |
| [ASN_ANTIT_CD](#asn_antit_cd) | T | 0 | `ANTIT` (altro schema) |
| [ASN_APDEC_CD](#asn_apdec_cd) | T | 0 | `APDEC` (altro schema) |
| [ASN_APFCON_CD](#asn_apfcon_cd) | T | 0 | `APFCON` (altro schema) |
| [ASN_APROD_CD](#asn_aprod_cd) | T | 0 | `APROD` (altro schema) |
| [ASN_APRSPI_CD](#asn_aprspi_cd) | T | 0 | `APRSPI` (altro schema) |
| [ASN_APRVFN_CD](#asn_aprvfn_cd) | T | 0 | `APRVFN` (altro schema) |
| [ASN_APRVOC_CD](#asn_aprvoc_cd) | T | 0 | `APRVOC` (altro schema) |
| [ASN_APRV_CD](#asn_aprv_cd) | T | 10 | `APRV` (altro schema) |
| [ASN_APR_CD](#asn_apr_cd) | T | 0 | `APR` (altro schema) |
| [ASN_ARIC_CD5](#asn_aric_cd5) | T | 0 | `ARIC` (altro schema) |
| [ASN_ASALST_CD](#asn_asalst_cd) | T | 67 | `ASALST` (altro schema) |
| [ASN_ASCMM_CD](#asn_ascmm_cd) | T | 0 | `ASCMM` (altro schema) |
| [ASN_ASGM_CD](#asn_asgm_cd) | T | 0 | `ASGM` (altro schema) |
| [ASN_ASGSPI_CD](#asn_asgspi_cd) | T | 2 | `ASGSPI` (altro schema) |
| [ASN_ASG_CD5](#asn_asg_cd5) | T | 0 | `ASG` (altro schema) |
| [ASN_ASPD_CD](#asn_aspd_cd) | T | 0 | `ASPD` (altro schema) |
| [ASN_ASSICURATI_CD](#asn_assicurati_cd) | T | 179 | `ASSICURATI` (altro schema) |
| [ASN_ASS_CD5](#asn_ass_cd5) | T | 0 | `ASS` (altro schema) |
| [ASN_ATERMSPI_CD](#asn_atermspi_cd) | T | 0 | `ATERMSPI` (altro schema) |
| [ASN_ATERM_CD](#asn_aterm_cd) | T | 2 | `ATERM` (altro schema) |
| [ASN_BANAM_CD](#asn_banam_cd) | T | 1.719 | `BANAM` (altro schema) |
| [ASN_BANASPI_CD](#asn_banaspi_cd) | T | 315 | `BANASPI` (altro schema) |
| [ASN_BANA_CD5](#asn_bana_cd5) | T | 0 | `BANA` (altro schema) |
| [ASN_BCC_CD5](#asn_bcc_cd5) | T | 0 | `BCC` (altro schema) |
| [ASN_BENEF_CD](#asn_benef_cd) | T | 0 | `BENEF` (altro schema) |
| [ASN_BPRO_CD5](#asn_bpro_cd5) | T | 0 | `BPRO` (altro schema) |
| [ASN_CCFA_CD5](#asn_ccfa_cd5) | T | 0 | `CCFA` (altro schema) |
| [ASN_CCFC_CD5](#asn_ccfc_cd5) | T | 0 | `CCFC` (altro schema) |
| [ASN_CCFL_CD5](#asn_ccfl_cd5) | T | 0 | `CCFL` (altro schema) |
| [ASN_CCFM_CD5](#asn_ccfm_cd5) | T | 0 | `CCFM` (altro schema) |
| [ASN_CCFP_CD5](#asn_ccfp_cd5) | T | 0 | `CCFP` (altro schema) |
| [ASN_CCFUL_CD5](#asn_ccful_cd5) | T | 0 | `CCFUL` (altro schema) |
| [ASN_CCFZ_CD](#asn_ccfz_cd) | T | 0 | `CCFZ` (altro schema) |
| [ASN_CCMA_CD5](#asn_ccma_cd5) | T | 24 | `CCMA` (altro schema) |
| [ASN_CCML_CD5](#asn_ccml_cd5) | T | 0 | `CCML` (altro schema) |
| [ASN_CCMM_CD5](#asn_ccmm_cd5) | T | 0 | `CCMM` (altro schema) |
| [ASN_CCMP_CD5](#asn_ccmp_cd5) | T | 0 | `CCMP` (altro schema) |
| [ASN_CCMSP_CD](#asn_ccmsp_cd) | T | 0 | `CCMSP` (altro schema) |
| [ASN_CCMUL_CD5](#asn_ccmul_cd5) | T | 0 | `CCMUL` (altro schema) |
| [ASN_CCMV_CD](#asn_ccmv_cd) | T | 0 | `CCMV` (altro schema) |
| [ASN_CFB_CD5](#asn_cfb_cd5) | T | 0 | `CFB` (altro schema) |
| [ASN_CFG_CD5](#asn_cfg_cd5) | T | 0 | `CFG` (altro schema) |
| [ASN_CFO_CD](#asn_cfo_cd) | T | 0 | `CFO` (altro schema) |
| [ASN_CFS_CD5](#asn_cfs_cd5) | T | 0 | `CFS` (altro schema) |
| [ASN_CMB_CD](#asn_cmb_cd) | T | 0 | `CMB` (altro schema) |
| [ASN_CMCCL_CD](#asn_cmccl_cd) | T | 0 | `CMCCL` (altro schema) |
| [ASN_CMG_CD5](#asn_cmg_cd5) | T | 0 | `CMG` (altro schema) |
| [ASN_CMO_CD](#asn_cmo_cd) | T | 0 | `CMO` (altro schema) |
| [ASN_CMS_CD5](#asn_cms_cd5) | T | 0 | `CMS` (altro schema) |
| [ASN_CMT_CD](#asn_cmt_cd) | T | 0 | `CMT` (altro schema) |
| [ASN_COAGM_CD](#asn_coagm_cd) | T | 11.587 | `COAGM` (altro schema) |
| [ASN_COAGSPI_CD](#asn_coagspi_cd) | T | 3.099 | `COAGSPI` (altro schema) |
| [ASN_COAG_CD5](#asn_coag_cd5) | T | 0 | `COAG` (altro schema) |
| [ASN_COCF_CD](#asn_cocf_cd) | T | 24 | `COCF` (altro schema) |
| [ASN_COCM_CD](#asn_cocm_cd) | T | 2 | `COCM` (altro schema) |
| [ASN_CONSR_CD](#asn_consr_cd) | T | 854.918 | `CONSR` (altro schema) |
| [ASN_CORIC_CD](#asn_coric_cd) | T | 15.092 | `CORIC` (altro schema) |
| [ASN_CTRA_CD5](#asn_ctra_cd5) | T | 0 | `CTRA` (altro schema) |
| [ASN_CVNUL_CD5](#asn_cvnul_cd5) | T | 0 | `CVNUL` (altro schema) |
| [ASN_CVN_CD5](#asn_cvn_cd5) | T | 0 | `CVN` (altro schema) |
| [ASN_DBEN_CD](#asn_dben_cd) | T | 0 | `DBEN` (altro schema) |
| [ASN_DFPORSPI_CD](#asn_dfporspi_cd) | T | 5 | `DFPORSPI` (altro schema) |
| [ASN_DFPOR_CD](#asn_dfpor_cd) | T | 11.649 | `DFPOR` (altro schema) |
| [ASN_DIVI_CD5](#asn_divi_cd5) | T | 0 | `DIVI` (altro schema) |
| [ASN_DSIA_CD5](#asn_dsia_cd5) | T | 0 | `DSIA` (altro schema) |
| [ASN_ECAB_CD5](#asn_ecab_cd5) | T | 0 | `ECAB` (altro schema) |
| [ASN_ENCB_CD5](#asn_encb_cd5) | T | 0 | `ENCB` (altro schema) |
| [ASN_FFOI_CD5](#asn_ffoi_cd5) | T | 0 | `FFOI` (altro schema) |
| [ASN_FFUL_CD5](#asn_fful_cd5) | T | 0 | `FFUL` (altro schema) |
| [ASN_FVOC1_CD](#asn_fvoc1_cd) | T | 0 | `FVOC1` (altro schema) |
| [ASN_FVOC2_CD](#asn_fvoc2_cd) | T | 0 | `FVOC2` (altro schema) |
| [ASN_GARASS_CD](#asn_garass_cd) | T | 0 | `GARASS` (altro schema) |
| [ASN_GARD_CD5](#asn_gard_cd5) | T | 0 | `FJBM.GARD` |
| [ASN_GCF_CD5](#asn_gcf_cd5) | T | 0 | `GCF` (altro schema) |
| [ASN_GPFRANGE_CD](#asn_gpfrange_cd) | T | 0 | `GPFRANGE` (altro schema) |
| [ASN_GPLINEA_CD](#asn_gplinea_cd) | T | 12 | `GPLINEA` (altro schema) |
| [ASN_GPMMOV_CD](#asn_gpmmov_cd) | T | 0 | `GPMMOV` (altro schema) |
| [ASN_GPMSAL_CD](#asn_gpmsal_cd) | T | 0 | `GPMSAL` (altro schema) |
| [ASN_GSEP_CD](#asn_gsep_cd) | T | 0 | `GSEP` (altro schema) |
| [ASN_IVA_CD](#asn_iva_cd) | T | 0 | `IVA` (altro schema) |
| [ASN_IVFD_CD5](#asn_ivfd_cd5) | T | 0 | `IVFD` (altro schema) |
| [ASN_KEYSPI_CD](#asn_keyspi_cd) | T | 0 | `FJBM.KEYSPI` |
| [ASN_MDIR_CD](#asn_mdir_cd) | T | 0 | `MDIR` (altro schema) |
| [ASN_MFSFDT_CD](#asn_mfsfdt_cd) | T | 0 | `MFSFDT` (altro schema) |
| [ASN_MFSGR_CD](#asn_mfsgr_cd) | T | 0 | `MFSGR` (altro schema) |
| [ASN_MFSPE_CD](#asn_mfspe_cd) | T | 956 | `MFSPE` (altro schema) |
| [ASN_MFTUN_CD](#asn_mftun_cd) | T | 145.117 | `MFTUN` (altro schema) |
| [ASN_MGPL_CD](#asn_mgpl_cd) | T | 0 | `MGPL` (altro schema) |
| [ASN_MLIV1A_CD](#asn_mliv1a_cd) | T | 1.405.170 | `MLIV1A` (altro schema) |
| [ASN_MOVE_CD](#asn_move_cd) | T | 0 | `MOVE` (altro schema) |
| [ASN_MOVTIT_CD](#asn_movtit_cd) | T | 236.819 | `MOVTIT` (altro schema) |
| [ASN_MPAY_CD5](#asn_mpay_cd5) | T | 0 | `MPAY` (altro schema) |
| [ASN_MRFA_CD](#asn_mrfa_cd) | T | 0 | `MRFA` (altro schema) |
| [ASN_NAVCONF_CD](#asn_navconf_cd) | T | 2.384 | `NAVCONF` (altro schema) |
| [ASN_NAV_CD5](#asn_nav_cd5) | T | 0 | `NAV` (altro schema) |
| [ASN_NOBPREZ_CD](#asn_nobprez_cd) | T | 316 | `NOBPREZ` (altro schema) |
| [ASN_NRRIA_CD](#asn_nrria_cd) | T | 16.361 | `NRRIA` (altro schema) |
| [ASN_NSRSEI_CD](#asn_nsrsei_cd) | T | 4.459.949 | `NSRSEI` (altro schema) |
| [ASN_NVGS_CD](#asn_nvgs_cd) | T | 0 | `NVGS` (altro schema) |
| [ASN_OCSA_CD5](#asn_ocsa_cd5) | T | 0 | `OCSA` (altro schema) |
| [ASN_OGAR_CD5](#asn_ogar_cd5) | T | 0 | `OGAR` (altro schema) |
| [ASN_OPRT_CD5](#asn_oprt_cd5) | T | 0 | `OPRT` (altro schema) |
| [ASN_OREG_CD5](#asn_oreg_cd5) | T | 0 | `OREG` (altro schema) |
| [ASN_PAG_CD5](#asn_pag_cd5) | T | 0 | `PAG` (altro schema) |
| [ASN_PCOMRT_CD](#asn_pcomrt_cd) | T | 0 | `PCOMRT` (altro schema) |
| [ASN_PDE_CD5](#asn_pde_cd5) | T | 0 | `PDE` (altro schema) |
| [ASN_PDRETE_CD](#asn_pdrete_cd) | T | 419 | `PDRETE` (altro schema) |
| [ASN_PFIPSPI_CD](#asn_pfipspi_cd) | T | 0 | `PFIPSPI` (altro schema) |
| [ASN_PFIP_CD](#asn_pfip_cd) | T | 8 | `PFIP` (altro schema) |
| [ASN_POLD_CD5](#asn_pold_cd5) | T | 0 | `POLD` (altro schema) |
| [ASN_PRESCA_CD](#asn_presca_cd) | T | 13 | `PRESCA` (altro schema) |
| [ASN_PRESTAZ_CD](#asn_prestaz_cd) | T | 2 | `PRESTAZ` (altro schema) |
| [ASN_PROVCG_CD](#asn_provcg_cd) | T | 0 | `PROVCG` (altro schema) |
| [ASN_PROVCT_CD5](#asn_provct_cd5) | T | 0 | `PROVCT` (altro schema) |
| [ASN_PROVOCE_CD5](#asn_provoce_cd5) | T | 0 | `PROVOCE` (altro schema) |
| [ASN_PRVCSPB_CD](#asn_prvcspb_cd) | T | 0 | `PRVCSPB` (altro schema) |
| [ASN_PRVCTSPI_CD](#asn_prvctspi_cd) | T | 0 | `PRVCTSPI` (altro schema) |
| [ASN_PRZTIT_CD](#asn_prztit_cd) | T | 297.264 | `PRZTIT` (altro schema) |
| [ASN_PTCFL_CD](#asn_ptcfl_cd) | T | 179.716 | `PTCFL` (altro schema) |
| [ASN_PTCFM_CD](#asn_ptcfm_cd) | T | 4.821 | `PTCFM` (altro schema) |
| [ASN_PTCML_CD](#asn_ptcml_cd) | T | 343.763 | `PTCML` (altro schema) |
| [ASN_PTCMM_CD](#asn_ptcmm_cd) | T | 201.805 | `PTCMM` (altro schema) |
| [ASN_PTDIV_CD](#asn_ptdiv_cd) | T | 9.887 | `PTDIV` (altro schema) |
| [ASN_PTPIANI_CD](#asn_ptpiani_cd) | T | 54.145 | `PTPIANI` (altro schema) |
| [ASN_PTSEN_CD](#asn_ptsen_cd) | T | 1.133 | `PTSEN` (altro schema) |
| [ASN_PTSPIANI_CD](#asn_ptspiani_cd) | T | 68.425 | `PTSPIANI` (altro schema) |
| [ASN_PTVCG_CD](#asn_ptvcg_cd) | T | 15.428 | `PTVCG` (altro schema) |
| [ASN_QUOTEGP_CD](#asn_quotegp_cd) | T | 153.947.574 | `QUOTEGP` (altro schema) |
| [ASN_QUOTESK_CD](#asn_quotesk_cd) | T | 180.715 | `QUOTESK` (altro schema) |
| [ASN_QUOTE_CD](#asn_quote_cd) | T | 1.987.849 | `QUOTE` (altro schema) |
| [ASN_QVALP_CD](#asn_qvalp_cd) | T | 0 | `QVALP` (altro schema) |
| [ASN_RAMO1_CD](#asn_ramo1_cd) | T | 1.168 | `RAMO1` (altro schema) |
| [ASN_RAMODANNI_CD](#asn_ramodanni_cd) | T | 81 | `RAMODANNI` (altro schema) |
| [ASN_RAMOV_CD](#asn_ramov_cd) | T | 134.562 | `RAMOV` (altro schema) |
| [ASN_RASAL_CD](#asn_rasal_cd) | T | 101.438 | `RASAL` (altro schema) |
| [ASN_RCDMCC_CD](#asn_rcdmcc_cd) | T | 2.445.748 | `RCDMCC` (altro schema) |
| [ASN_RENCO_CD](#asn_renco_cd) | T | 648.853 | `RENCO` (altro schema) |
| [ASN_RFAPBTOP_CD](#asn_rfapbtop_cd) | T | 0 | `RFAPBTOP` (altro schema) |
| [ASN_RGPF_CD5](#asn_rgpf_cd5) | T | 0 | `RGPF` (altro schema) |
| [ASN_RIC_CD](#asn_ric_cd) | T | 83.202 | `RIC` (altro schema) |
| [ASN_RIN1_CD5](#asn_rin1_cd5) | T | 0 | `RIN1` (altro schema) |
| [ASN_RINCAS_CD](#asn_rincas_cd) | T | 922.059 | `RINCAS` (altro schema) |
| [ASN_RNREG_CD](#asn_rnreg_cd) | T | 0 | `RNREG` (altro schema) |
| [ASN_SLIV1A_CD](#asn_sliv1a_cd) | T | 20.378.877 | `SLIV1A` (altro schema) |
| [ASN_SLIV2A_CD](#asn_sliv2a_cd) | T | 10.080.006 | `SLIV2A` (altro schema) |
| [ASN_SPLI_CD](#asn_spli_cd) | T | 0 | `SPLI` (altro schema) |
| [ASN_SPOL_CD5](#asn_spol_cd5) | T | 0 | `SPOL` (altro schema) |
| [ASN_SSIGE_CD5](#asn_ssige_cd5) | T | 0 | `SSIGE` (altro schema) |
| [ASN_STAPOL_CD](#asn_stapol_cd) | T | 0 | `STAPOL` (altro schema) |
| [ASN_STORFA_CD](#asn_storfa_cd) | T | 4.704 | `STORFA` (altro schema) |
| [ASN_STPROVCG_CD](#asn_stprovcg_cd) | T | 0 | `STPROVCG` (altro schema) |
| [ASN_STPR_CD5](#asn_stpr_cd5) | T | 0 | `STPR` (altro schema) |
| [ASN_STPUL_CD](#asn_stpul_cd) | T | 1 | `STPUL` (altro schema) |
| [ASN_TFCLIENT_CD](#asn_tfclient_cd) | T | 0 | `TFCLIENT` (altro schema) |
| [ASN_TFTEAM_CD](#asn_tfteam_cd) | T | 0 | `TFTEAM` (altro schema) |
| [ASN_TIPOLEG_CD](#asn_tipoleg_cd) | T | 7 | `FJBM.TIPOLEG` |
| [ASN_TMCLIENT_CD](#asn_tmclient_cd) | T | 10.904 | `TMCLIENT` (altro schema) |
| [ASN_TMPB_CD](#asn_tmpb_cd) | T | 387 | `TMPB` (altro schema) |
| [ASN_TMPERC_CD](#asn_tmperc_cd) | T | 20.941 | `TMPERC` (altro schema) |
| [ASN_TMTEAM_CD](#asn_tmteam_cd) | T | 749 | `TMTEAM` (altro schema) |
| [ASN_TPREMI_CD](#asn_tpremi_cd) | T | 8 | `TPREMI` (altro schema) |
| [ASN_TRARASPI_CD](#asn_traraspi_cd) | T | 0 | `TRARASPI` (altro schema) |
| [ASN_TRARA_CD](#asn_trara_cd) | T | 0 | `TRARA` (altro schema) |
| [ASN_TRASF_CD](#asn_trasf_cd) | T | 0 | `TRASF` (altro schema) |
| [ASN_TRF_CD5](#asn_trf_cd5) | T | 0 | `TRF` (altro schema) |
| [ASN_VARPOL_CD](#asn_varpol_cd) | T | 0 | `VARPOL` (altro schema) |
| [ASN_VAR_CD5](#asn_var_cd5) | T | 0 | `VAR` (altro schema) |
| [ASN_VDISTR_CD5](#asn_vdistr_cd5) | T | 0 | `VDISTR` (altro schema) |
| [ASN_VFFOI_CD5](#asn_vffoi_cd5) | T | 0 | `VFFOI` (altro schema) |
| [ASN_VTFOIF_CD5](#asn_vtfoif_cd5) | T | 0 | `VTFOIF` (altro schema) |
| [ASN_VTFOI_CD5](#asn_vtfoi_cd5) | T | 0 | `VTFOI` (altro schema) |
| [ASN_W6SCCO_CD](#asn_w6scco_cd) | T | 0 | `W6SCCO` (altro schema) |
| [ASN_W6SCST_CD](#asn_w6scst_cd) | T | 0 | `W6SCST` (altro schema) |
| [ASN_WCARAD_CD](#asn_wcarad_cd) | T | 0 | `WCARAD` (altro schema) |
| [ASN_WCTRAD_CD](#asn_wctrad_cd) | T | 0 | `WCTRAD` (altro schema) |
| [ASN_WDCBEN_CD](#asn_wdcben_cd) | T | 0 | `WDCBEN` (altro schema) |
| [ASN_WESTCD_CD](#asn_westcd_cd) | T | 0 | `WESTCD` (altro schema) |
| [ASN_WIBSTRT_CD](#asn_wibstrt_cd) | T | 0 | `WIBSTRT` (altro schema) |
| [ASN_WPRDD_CD](#asn_wprdd_cd) | T | 0 | `WPRDD` (altro schema) |
| [ASN_WPRDSD_CD](#asn_wprdsd_cd) | T | 0 | `WPRDSD` (altro schema) |
| [ASN_WPRPOD_CD](#asn_wprpod_cd) | T | 0 | `WPRPOD` (altro schema) |
| [ASN_WREPRD_CD](#asn_wreprd_cd) | T | 0 | `WREPRD` (altro schema) |
| [ASN_WSPOLD_CD](#asn_wspold_cd) | T | 0 | `WSPOLD` (altro schema) |
| [ASN_WSTCND_CD](#asn_wstcnd_cd) | T | 0 | `WSTCND` (altro schema) |
| [ASN_WSTRT_CD](#asn_wstrt_cd) | T | 0 | `WSTRT` (altro schema) |
| [ASN_WTPGED_CD](#asn_wtpged_cd) | T | 0 | `WTPGED` (altro schema) |
| [ASN_WTRFD_CD](#asn_wtrfd_cd) | T | 0 | `WTRFD` (altro schema) |
| [ASN_WTVOCD_CD](#asn_wtvocd_cd) | T | 0 | `WTVOCD` (altro schema) |
| [ASN_WVOCID_CD](#asn_wvocid_cd) | T | 0 | `WVOCID` (altro schema) |
| [ASN_WZOPED_CD](#asn_wzoped_cd) | T | 0 | `WZOPED` (altro schema) |
| [ASN_YSTRT_CD](#asn_ystrt_cd) | T | 0 | `YSTRT` (altro schema) |
| [ASN_ZOPR_CD5](#asn_zopr_cd5) | T | 0 | `ZOPR` (altro schema) |
| [ASN_ZTRA_CD5](#asn_ztra_cd5) | T | 0 | `ZTRA` (altro schema) |
| [BJSYSPACKAGEV2](#bjsyspackagev2) | V | n.d. |  |
| [BJSYSPACKAGEV3](#bjsyspackagev3) | V | n.d. |  |
| [BJSYSPLANV1](#bjsysplanv1) | V | n.d. |  |
| [BJSYSPLANV2](#bjsysplanv2) | V | n.d. |  |
| [BJSYSTABLESV1](#bjsystablesv1) | V | n.d. |  |
| [BJSYSTABLESV2](#bjsystablesv2) | V | n.d. |  |
| [BJSYSTABLESV3](#bjsystablesv3) | V | n.d. |  |
| [BJSYSTABLESV4](#bjsystablesv4) | V | n.d. |  |
| [BJSYSTABLESV5](#bjsystablesv5) | V | n.d. |  |
| [BJSYSTABLESV6](#bjsystablesv6) | V | n.d. |  |
| [DSN_COLDIST_TABLE](#dsn_coldist_table) | T | n.d. |  |
| [DSN_DETCOST_TABLE](#dsn_detcost_table) | T | n.d. |  |
| [DSN_FILTER_TABLE](#dsn_filter_table) | T | n.d. |  |
| [DSN_FUNCTION_TABLE](#dsn_function_table) | T | n.d. |  |
| [DSN_KEYTGTDIST_TABLE](#dsn_keytgtdist_table) | T | n.d. |  |
| [DSN_PGRANGE_TABLE](#dsn_pgrange_table) | T | n.d. |  |
| [DSN_PGROUP_TABLE](#dsn_pgroup_table) | T | n.d. |  |
| [DSN_PREDICATE_SELECTIVITY](#dsn_predicate_selectivity) | T | n.d. |  |
| [DSN_PREDICAT_TABLE](#dsn_predicat_table) | T | n.d. |  |
| [DSN_PTASK_TABLE](#dsn_ptask_table) | T | n.d. |  |
| [DSN_QUERYINFO_AUX](#dsn_queryinfo_aux) | X | n.d. |  |
| [DSN_QUERYINFO_AUX2](#dsn_queryinfo_aux2) | X | n.d. |  |
| [DSN_QUERYINFO_TABLE](#dsn_queryinfo_table) | T | n.d. |  |
| [DSN_QUERY_AUX](#dsn_query_aux) | X | n.d. |  |
| [DSN_QUERY_TABLE](#dsn_query_table) | T | n.d. |  |
| [DSN_SORTKEY_TABLE](#dsn_sortkey_table) | T | n.d. |  |
| [DSN_SORT_TABLE](#dsn_sort_table) | T | n.d. |  |
| [DSN_STATEMENT_CACHE_AUX](#dsn_statement_cache_aux) | X | n.d. |  |
| [DSN_STATEMENT_CACHE_TABLE](#dsn_statement_cache_table) | T | n.d. |  |
| [DSN_STATEMNT_TABLE](#dsn_statemnt_table) | T | n.d. |  |
| [DSN_STAT_FEEDBACK](#dsn_stat_feedback) | T | n.d. |  |
| [DSN_STRUCT_TABLE](#dsn_struct_table) | T | n.d. |  |
| [DSN_USERQUERY_TABLE](#dsn_userquery_table) | T | n.d. |  |
| [DSN_USERQUERY_TABLE_AUX](#dsn_userquery_table_aux) | X | n.d. |  |
| [DSN_VIEWREF_TABLE](#dsn_viewref_table) | T | n.d. |  |
| [DSN_VIRTUAL_INDEXES](#dsn_virtual_indexes) | T | n.d. |  |
| [DSN_VIRTUAL_KEYTARGETS](#dsn_virtual_keytargets) | T | n.d. |  |
| [NRTAB](#nrtab) | V | n.d. |  |
| [PLAN_TABLE](#plan_table) | T | n.d. |  |
| [VWCOL](#vwcol) | V | n.d. |  |
| [V_AUTH](#v_auth) | V | n.d. |  |
| [V_DBAUTH](#v_dbauth) | V | n.d. |  |
| [V_OGGETTOPLAN](#v_oggettoplan) | V | n.d. |  |
| [V_PLANOGGETTO](#v_planoggetto) | V | n.d. |  |

## ASN_ACFM_CD5

*Tabella* – righe: n.d.
– change data della tabella `ACFM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ACFM_CODCONF | CHAR(11) | N |  |
| 6 | ACFM_CODPROD | CHAR(2) | N |  |
| 7 | ACFM_DTSENFP | DECIMAL(9,0) | N |  |
| 8 | ACFM_DTSPSAMM | DECIMAL(9,0) | N |  |
| 9 | ACFM_SPSSOTT | DECIMAL(15,3) | N |  |
| 10 | ACFM_SPSAMMI | DECIMAL(15,3) | N |  |
| 11 | ACFM_SPSAMMC | DECIMAL(15,3) | N |  |
| 12 | ACFM_SPSTASS | DECIMAL(15,3) | N |  |
| 13 | ACFM_FPPROV | CHAR(30) | N |  |
| 14 | ACFM_SPSAMML | DECIMAL(15,3) | N |  |
| 15 | ACFM_IVASOTT | DECIMAL(15,2) | N |  |
| 16 | ACFM_IVAAMMI | DECIMAL(15,2) | N |  |
| 17 | ACFM_IVAAMMC | DECIMAL(15,2) | N |  |
| 18 | ACFM_IVAAMML | DECIMAL(15,2) | N |  |
| 19 | ACFM_PROGETTO | CHAR(1) | N | PROGETTO |
| 20 | ACFM_LINEA | CHAR(1) | N | LINEA |
| 21 | ACFM_ADE_PRANTOT | DECIMAL(15,2) | N | CONTRIBUTO ADERENTE -PREMIO ANNUO TOTALE |
| 22 | ACFM_ADE_PERC | DECIMAL(5,2) | N | PERC.RETRIB.CALCOLO TFR/REDDITO FINI IRPEF |
| 23 | ACFM_ADE_RATAFRZ | SMALLINT | N | FRAZIONAMENTO CONTRIBUTO ADERENTE |
| 24 | ACFM_DAT_PRANTOT | DECIMAL(15,2) | N | CONTRIBUTO DATORE LAVORO-PREMIO ANNUO TOTALE |
| 25 | ACFM_DAT_PERC | DECIMAL(5,2) | N | PERC.RETRIB. CALCOLO TFR LAV.DIPENDENTI |
| 26 | ACFM_DAT_RATAFRZ | SMALLINT | N | FRAZIONAMENTO CONTRIBUTO DATORE DI LAVORO |
| 27 | ACFM_CONF_PERC | DECIMAL(5,2) | N | PERC.RETRIB.CALCOLO TFR PER LAV.DIPENDENTI |
| 28 | ACFM_CONF_RATAFRZ | SMALLINT | N | FRAZIONAMENTO CONFERIMENTO TFR |
| 29 | ACFM_NUMPOL | CHAR(11) | N | NUMERO POLIZZA |
| 30 | ACFM_ADE_LORDO | DECIMAL(15,2) | N | IMPORTO RICEVUTO LORDO CONTR. ADER. |
| 31 | ACFM_ADE_NETTO | DECIMAL(15,2) | N | IMPORTO RICEVUTO NETTO CONTR.ADER. |
| 32 | ACFM_ADE_SPSSOTT | DECIMAL(15,2) | N | SPESE DI SOTTOSCRIZIONE PER CONTR. ADER. |
| 33 | ACFM_ADE_SPSTASS | DECIMAL(15,2) | N | TASSE PER CONTR. ADER. |
| 34 | ACFM_DAT_LORDO | DECIMAL(15,2) | N | IMPORTO RICEVUTO LORDO CONTR. DATORE |
| 35 | ACFM_DAT_NETTO | DECIMAL(15,2) | N | IMPORTO RICEVUTO NETTO CONTR. DATORE |
| 36 | ACFM_DAT_SPSSOTT | DECIMAL(15,2) | N | SPESE DI SOTTOSCRIZIONE PER CONTR.DATORE |
| 37 | ACFM_DAT_SPSTASS | DECIMAL(15,2) | N | TASSE PER CONTR. DATORE |
| 38 | ACFM_CONF_LORDO | DECIMAL(15,2) | N | IMPORTO RICEVUTO LORDO DA CONF. TFR |
| 39 | ACFM_CONF_NETTO | DECIMAL(15,2) | N | IMPORTO RICEVUTO NETTO DA CONF. TFR |
| 40 | ACFM_CONF_SPSSOTT | DECIMAL(15,2) | N | SPESE DI SOTTOSCRIZIONE DA CONF.TFR |
| 41 | ACFM_CONF_SPSTASS | DECIMAL(15,2) | N | TASSE PER CONTR. DA CONF. TFR |
| 42 | ACFM_ANZCONTR | DECIMAL(3,0) |  |  |
| 43 | ACFM_REQOBBL | CHAR(1) |  |  |
| 44 | ACFM_LAVDIPEN | CHAR(1) |  |  |
| 45 | ACFM_MONT2000 | DECIMAL(15,2) |  |  |
| 46 | ACFM_IMPANT | DECIMAL(15,2) |  |  |
| 47 | ACFM_RITANT | DECIMAL(15,2) |  |  |
| 48 | ACFM_VECISCR | CHAR(1) |  |  |
| 49 | ACFM_SPSSOTEU | DECIMAL(13,2) |  |  |
| 50 | ACFM_SPSAMEU | DECIMAL(13,2) |  |  |
| 51 | ACFM_SPSAMCEU | DECIMAL(13,2) |  |  |
| 52 | ACFM_SPSTASEU | DECIMAL(13,2) |  |  |
| 53 | ACFM_SPSAMLEU | DECIMAL(13,2) |  |  |
| 54 | ACFM_IVASOTEU | DECIMAL(13,2) |  |  |
| 55 | ACFM_IVAAMEU | DECIMAL(13,2) |  |  |
| 56 | ACFM_IVAAMCEU | DECIMAL(13,2) |  |  |
| 57 | ACFM_IVAAMLEU | DECIMAL(13,2) |  |  |
| 58 | ACFM_MONT2006 | DECIMAL(15,2) |  |  |
| 59 | ACFM_PREVOB_ANTE93 | CHAR(1) |  |  |
| 60 | ACFM_PREVCM_ANTE93 | CHAR(1) |  |  |
| 61 | ACFM_CODCONV | CHAR(6) | N |  |
| 62 | ACFM_ANNO_PENS | DECIMAL(4,0) |  |  |
| 63 | ACFM_TRASF | CHAR(1) |  |  |
| 64 | ACFM_NUMPROV | CHAR(30) |  |  |
| 65 | ACFM_N_COVIP | CHAR(30) |  |  |
| 66 | ACFM_PRODEST | CHAR(5) |  |  |
| 67 | ACFM_DECPOL | DECIMAL(9,0) |  |  |
| 68 | ACFM_DTEMIPOL | DECIMAL(9,0) |  |  |
| 69 | ACFM_TIPBEN | CHAR(1) |  |  |
| 70 | ACFM_ADE_PERCLA | DECIMAL(5,2) |  |  |
| 71 | ACFM_PRECONTO | DECIMAL(15,2) |  |  |
| 72 | ACFM_ADE_SPSAMMI | DECIMAL(15,2) |  |  |
| 73 | ACFM_DAT_SPSAMMI | DECIMAL(15,2) |  |  |
| 74 | ACFM_CONF_SPSAMMI | DECIMAL(15,2) |  |  |
| 75 | ACFM_DTCONV | DECIMAL(9,0) |  |  |
| 76 | ACFM_ADE_TRASF | DECIMAL(15,2) | N | IMPRIC DA ALTRO FONDO |
| 77 | XACFM_CODCONF | CHAR(11) |  |  |
| 78 | XACFM_CODPROD | CHAR(2) |  |  |
| 79 | ACFM_FLGADE | CHAR(1) | N |  |

Indici:

- `ASN_ACFM_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ACLNM_CD

*Tabella* – righe: 4
– change data della tabella `ACLNM` (FJBM: TABELLA COLLEGAMENTO  PB/CLIENTE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ACLNM_RETE | CHAR(1) | N |  |
| 5 | ACLNM_CODANA | CHAR(12) | N |  |
| 6 | XACLNM_CODANA | CHAR(12) |  |  |
| 7 | ACLNM_CODAGE | CHAR(6) | N |  |
| 8 | XACLNM_CODAGE | CHAR(6) |  |  |
| 9 | ACLNM_DTINIZ | INTEGER | N |  |

Indici:

- `IXCDACLNM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ACLNSPI_CD

*Tabella* – righe: 11
– change data della tabella `ACLNSPI` (FJBM: TABELLA RELAZIONI CLIENTI SPI/CONSULENTI FINANZIARI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XACLNSPI_CODANA | CHAR(12) |  |  |
| 6 | ACLNSPI_CODANA | CHAR(12) | N |  |
| 7 | XACLNSPI_CODAGE | CHAR(6) |  |  |
| 8 | ACLNSPI_CODAGE | CHAR(6) | N |  |
| 9 | ACLNSPI_DTINIZ | INTEGER | N |  |

Indici:

- `ACLNSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ACLN_CD5

*Tabella* – righe: 0
– change data della tabella `ACLN` (FJBM: TABELLA RELAZIONI CLIENTI/CONSULENTI FINANZIARI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XACLN_CODANA | CHAR(12) |  |  |
| 6 | XACLN_CODAGE | CHAR(6) |  |  |
| 7 | ACLN_CODANA | CHAR(12) | N |  |
| 8 | ACLN_CODAGE | CHAR(6) | N |  |
| 9 | ACLN_DTINIZ | INTEGER | N |  |

Indici:

- `ASN_ACLN_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ACODISPI_CD

*Tabella* – righe: 0
– change data della tabella `ACODISPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ACODISPI_INDIC | CHAR(3) | N |  |
| 5 | ACODISPI_CODIFICA | CHAR(5) | N |  |
| 6 | ACODISPI_DESCR | CHAR(50) | N |  |
| 7 | ACODISPI_DESCRABB | CHAR(15) | N |  |
| 8 | ACODISPI_GRUPPO | DECIMAL(3,0) | N |  |
| 9 | ACODISPI_DVALINI | DECIMAL(9,0) | N |  |
| 10 | ACODISPI_DVALFIN | DECIMAL(9,0) | N |  |

Indici:

- `ACODISPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ACODI_CD

*Tabella* – righe: 0
– change data della tabella `ACODI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ACODI_INDIC | CHAR(3) | N |  |
| 5 | ACODI_CODIFICA | CHAR(5) | N |  |
| 6 | ACODI_DESCR | CHAR(50) | N |  |
| 7 | ACODI_DESCRABB | CHAR(15) | N |  |
| 8 | ACODI_GRUPPO | DECIMAL(3,0) | N |  |
| 9 | ACODI_DVALINI | DECIMAL(9,0) | N |  |
| 10 | ACODI_DVALFIN | DECIMAL(9,0) | N |  |

Indici:

- `ACODID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AEAM_CD

*Tabella* – righe: 0
– change data della tabella `AEAM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AEAM_RETE | CHAR(1) | N |  |
| 5 | AEAM_CODAGE | CHAR(6) | N |  |
| 6 | AEAM_COGNOME | CHAR(30) | N |  |
| 7 | AEAM_NOME | CHAR(25) | N |  |
| 8 | AEAM_TITOLO | CHAR(8) | N |  |
| 9 | AEAM_CPF | CHAR(2) | N |  |
| 10 | AEAM_DATNAS | DECIMAL(9,0) | N |  |
| 11 | AEAM_CITTA | CHAR(25) | N |  |
| 12 | AEAM_PROV | CHAR(2) | N |  |
| 13 | AEAM_SEX | CHAR(1) | N |  |
| 14 | AEAM_MODRECLU | CHAR(1) | N |  |
| 15 | AEAM_CODAGEPRE | CHAR(6) | N |  |
| 16 | AEAM_STATUS | CHAR(1) | N |  |
| 17 | AEAM_DATPRE | DECIMAL(9,0) | N |  |
| 18 | AEAM_MESPRE | DECIMAL(3,0) | N |  |
| 19 | AEAM_DATINCOL | DECIMAL(9,0) | N |  |
| 20 | AEAM_DATFINE | DECIMAL(9,0) | N |  |
| 21 | AEAM_DATINPOT | DECIMAL(9,0) | N |  |
| 22 | AEAM_DATINPRO | DECIMAL(9,0) | N |  |

Indici:

- `IXCDAEAM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AEASPI_CD

*Tabella* – righe: 2
– change data della tabella `AEASPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AEASPI_CODAGE | CHAR(6) | N |  |
| 6 | AEASPI_COGNOME | CHAR(30) | N |  |
| 7 | AEASPI_NOME | CHAR(25) | N |  |
| 8 | AEASPI_TITOLO | CHAR(8) | N |  |
| 9 | AEASPI_CPF | CHAR(2) | N |  |
| 10 | AEASPI_DATNAS | DECIMAL(9,0) | N |  |
| 11 | AEASPI_CITTA | CHAR(25) | N |  |
| 12 | AEASPI_PROV | CHAR(2) | N |  |
| 13 | AEASPI_SEX | CHAR(1) | N |  |
| 14 | AEASPI_MODRECLU | CHAR(1) | N |  |
| 15 | AEASPI_CODAGEPRE | CHAR(6) | N |  |
| 16 | AEASPI_STATUS | CHAR(1) | N |  |
| 17 | AEASPI_DATPRE | DECIMAL(9,0) | N |  |
| 18 | AEASPI_MESPRE | DECIMAL(3,0) | N |  |
| 19 | AEASPI_DATINCOL | DECIMAL(9,0) | N |  |
| 20 | AEASPI_DATFINE | DECIMAL(9,0) | N |  |
| 21 | AEASPI_DATINPOT | DECIMAL(9,0) | N |  |
| 22 | AEASPI_DATINPRO | DECIMAL(9,0) | N |  |

Indici:

- `AEASPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AEA_CD5

*Tabella* – righe: 0
– change data della tabella `AEA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XAEA_CODAGE | CHAR(6) |  |  |
| 6 | AEA_CODAGE | CHAR(6) | N |  |
| 7 | AEA_COGNOME | CHAR(30) | N |  |
| 8 | AEA_NOME | CHAR(25) | N |  |
| 9 | AEA_TITOLO | CHAR(8) | N |  |
| 10 | AEA_STATUS | CHAR(1) | N |  |
| 11 | AEA_DATFINE | DECIMAL(9,0) | N |  |
| 12 | AEA_DATNAS | DECIMAL(9,0) | N |  |
| 13 | AEA_CITTA | CHAR(25) | N |  |
| 14 | AEA_PROV | CHAR(2) | N |  |
| 15 | AEA_SEX | CHAR(1) | N |  |
| 16 | AEA_DATINCOL | DECIMAL(9,0) | N |  |
| 17 | AEA_DATINPRO | DECIMAL(9,0) | N |  |
| 18 | AEA_CPF | CHAR(2) | N |  |
| 19 | AEA_MODRECLU | CHAR(1) | N |  |
| 20 | AEA_CODAGEPRE | CHAR(6) | N |  |
| 21 | AEA_DATPRE | DECIMAL(9,0) | N |  |
| 22 | AEA_MESPRE | DECIMAL(3,0) | N |  |
| 23 | AEA_DATINPOT | DECIMAL(9,0) | N |  |

Indici:

- `ASN_AEA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG2M_CD

*Tabella* – righe: 0
– change data della tabella `AG2M`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG2M_RETE | CHAR(1) | N |  |
| 5 | AG2M_CODAGE | CHAR(6) | N |  |
| 6 | AG2M_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AG2M_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AG2M_TIPOAGE | CHAR(1) | N |  |

Indici:

- `IXCDAG2M` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG2SPI_CD

*Tabella* – righe: 2
– change data della tabella `AG2SPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG2SPI_CODAGE | CHAR(6) | N |  |
| 5 | AG2SPI_DVALINI | DECIMAL(9,0) | N |  |
| 6 | AG2SPI_DVALFIN | DECIMAL(9,0) | N |  |
| 7 | AG2SPI_TIPOAGE | CHAR(1) | N |  |

Indici:

- `AG2SPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG2_CD

*Tabella* – righe: 22
– change data della tabella `AG2`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG2_CODAGE | CHAR(6) | N |  |
| 5 | AG2_DVALINI | DECIMAL(9,0) | N |  |
| 6 | AG2_DVALFIN | DECIMAL(9,0) | N |  |
| 7 | AG2_TIPOAGE | CHAR(1) | N |  |

Indici:

- `AG2D01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG3M_CD

*Tabella* – righe: 3
– change data della tabella `AG3M`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG3M_RETE | CHAR(1) | N |  |
| 5 | AG3M_CODAGE | CHAR(6) | N |  |
| 6 | AG3M_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AG3M_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AG3M_INDIC | CHAR(1) | N |  |
| 9 | AG3M_CODFIS | CHAR(16) | N |  |
| 10 | AG3M_PARTIVA | CHAR(11) | N |  |
| 11 | AG3M_PRPARTIVA | DECIMAL(3,0) | N |  |
| 12 | AG3M_NOMESOC | CHAR(55) | N |  |
| 13 | AG3M_INDVAL | CHAR(1) | N |  |
| 14 | AG3M_COD_REGIME | CHAR(10) | N |  |
| 15 | AG3M_REGIME_INI | DECIMAL(9,0) | N |  |
| 16 | AG3M_REGIME_FIN | DECIMAL(9,0) | N |  |

Indici:

- `IXCDAG3M` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG3SPI_CD

*Tabella* – righe: 10
– change data della tabella `AG3SPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AG3SPI_CODAGE | CHAR(6) | N |  |
| 6 | AG3SPI_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AG3SPI_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AG3SPI_INDIC | CHAR(1) | N |  |
| 9 | AG3SPI_CODFIS | CHAR(16) | N |  |
| 10 | AG3SPI_PARTIVA | CHAR(11) | N |  |
| 11 | AG3SPI_PRPARTIVA | DECIMAL(3,0) | N |  |
| 12 | AG3SPI_NOMESOC | CHAR(55) | N |  |
| 13 | AG3SPI_INDVAL | CHAR(1) | N |  |
| 14 | AG3SPI_COD_REGIME | CHAR(10) | N |  |
| 15 | AG3SPI_REGIME_INI | DECIMAL(9,0) | N |  |
| 16 | AG3SPI_REGIME_FIN | DECIMAL(9,0) | N |  |

Indici:

- `AG3SPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG3_CD5

*Tabella* – righe: 0
– change data della tabella `AG3`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XAG3_CODAGE | CHAR(6) |  |  |
| 6 | AG3_CODAGE | CHAR(6) | N |  |
| 7 | AG3_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AG3_CODFIS | CHAR(16) | N |  |
| 9 | AG3_DVALINI | DECIMAL(9,0) | N |  |
| 10 | AG3_INDIC | CHAR(1) | N |  |
| 11 | AG3_PARTIVA | CHAR(11) | N |  |
| 12 | AG3_PRPARTIVA | DECIMAL(3,0) | N |  |
| 13 | AG3_NOMESOC | CHAR(55) | N |  |
| 14 | AG3_INDVAL | CHAR(1) | N |  |
| 15 | AG3_COD_REGIME | CHAR(10) | N |  |
| 16 | AG3_REGIME_INI | DECIMAL(9,0) | N |  |
| 17 | AG3_REGIME_FIN | DECIMAL(9,0) | N |  |

Indici:

- `ASN_AG3_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG4M_CD

*Tabella* – righe: 4
– change data della tabella `AG4M`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG4M_RETE | CHAR(1) | N |  |
| 5 | AG4M_CODAGE | CHAR(6) | N |  |
| 6 | AG4M_PERCACC | DECIMAL(7,5) | N |  |
| 7 | AG4M_CODENAS | CHAR(7) | N |  |
| 8 | AG4M_AGCIDIVA | DECIMAL(7,5) | N |  |
| 9 | AG4M_INDISC | CHAR(1) | N |  |
| 10 | AG4M_DATALB | DECIMAL(9,0) | N |  |
| 11 | AG4M_NUMALB | CHAR(16) | N |  |
| 12 | AG4M_PROV | CHAR(2) | N |  |
| 13 | AG4M_INI | CHAR(2) | N |  |
| 14 | AG4M_DVALESV | DECIMAL(9,0) | N |  |
| 15 | AG4M_IMA | CHAR(1) | N |  |
| 16 | AG4M_DVALDMA | DECIMAL(9,0) | N |  |
| 17 | AG4M_I50 | CHAR(1) | N |  |
| 18 | AG4M_AGZ | CHAR(10) | N |  |
| 19 | AG4M_IPV | CHAR(1) | N |  |
| 20 | AG4M_INDINPS | CHAR(1) | N |  |
| 21 | AG4M_DATICON | DECIMAL(9,0) | N |  |
| 22 | AG4M_DATFCON | DECIMAL(9,0) | N |  |
| 23 | AG4M_INDFAT | CHAR(1) | N |  |
| 24 | AG4M_CITT | CHAR(1) | N |  |
| 25 | AG4M_DIPL | CHAR(1) | N |  |
| 26 | AG4M_GEN | CHAR(1) | N |  |
| 27 | AG4M_CIV | CHAR(1) | N |  |
| 28 | AG4M_UNO | DECIMAL(13,0) | N |  |
| 29 | AG4M_DUE | CHAR(1) | N |  |
| 30 | AG4M_BLKCONS | CHAR(3) | N |  |
| 31 | AG4M_DATBLK | DECIMAL(9,0) | N |  |
| 32 | AG4M_BLKINF | CHAR(3) | N |  |
| 33 | AG4M_DATINF | DECIMAL(9,0) | N |  |
| 34 | AG4M_PDE | CHAR(3) | N |  |
| 35 | AG4M_ABI | CHAR(5) | N |  |
| 36 | AG4M_DATFINE | DECIMAL(9,0) | N |  |
| 37 | AG4M_CODENAS1 | CHAR(10) | N |  |
| 38 | AG4M_DTINI60J | DECIMAL(9,0) | N |  |
| 39 | AG4M_DTFIN60J | DECIMAL(9,0) | N |  |
| 40 | AG4M_INDIM | CHAR(1) | N |  |
| 41 | AG4M_DTIN50PM | DECIMAL(9,0) | N |  |
| 42 | AG4M_DTFN50PM | DECIMAL(9,0) | N |  |
| 43 | AG4M_DTIN50GM | DECIMAL(9,0) | N |  |
| 44 | AG4M_DTFN50GM | DECIMAL(9,0) | N |  |
| 45 | AG4M_VAL_ESP | CHAR(2) | N |  |
| 46 | AG4M_CODICE_OCF | CHAR(15) | N |  |
| 47 | AG4M_ENA_DT_ISCR | DECIMAL(9,0) | N |  |
| 48 | AG4M_ENA_DT_ULT_VERS | DECIMAL(9,0) | N |  |
| 49 | AG4M_ENA_FL_AGEV | CHAR(1) | N |  |
| 50 | AG4M_ENA_DT_SCAD_AGEV | DECIMAL(9,0) | N |  |

Indici:

- `IXCDAG4M` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG4SPI_CD

*Tabella* – righe: 14
– change data della tabella `AG4SPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AG4SPI_CODAGE | CHAR(6) | N |  |
| 6 | AG4SPI_PERCACC | DECIMAL(7,5) | N |  |
| 7 | AG4SPI_CODENAS | CHAR(7) | N |  |
| 8 | AG4SPI_AGCIDIVA | DECIMAL(7,5) | N |  |
| 9 | AG4SPI_INDISC | CHAR(1) | N |  |
| 10 | AG4SPI_DATALB | DECIMAL(9,0) | N |  |
| 11 | AG4SPI_NUMALB | CHAR(16) | N |  |
| 12 | AG4SPI_PROV | CHAR(2) | N |  |
| 13 | AG4SPI_INI | CHAR(2) | N |  |
| 14 | AG4SPI_DVALESV | DECIMAL(9,0) | N |  |
| 15 | AG4SPI_IMA | CHAR(1) | N |  |
| 16 | AG4SPI_DVALDMA | DECIMAL(9,0) | N |  |
| 17 | AG4SPI_I50 | CHAR(1) | N |  |
| 18 | AG4SPI_PUO | CHAR(8) | N |  |
| 19 | AG4SPI_IPV | CHAR(1) | N |  |
| 20 | AG4SPI_INDINPS | CHAR(1) | N |  |
| 21 | AG4SPI_DATICON | DECIMAL(9,0) | N |  |
| 22 | AG4SPI_DATFCON | DECIMAL(9,0) | N |  |
| 23 | AG4SPI_INDFAT | CHAR(1) | N |  |
| 24 | AG4SPI_CITT | CHAR(1) | N |  |
| 25 | AG4SPI_DIPL | CHAR(1) | N |  |
| 26 | AG4SPI_GEN | CHAR(1) | N |  |
| 27 | AG4SPI_CIV | CHAR(1) | N |  |
| 28 | AG4SPI_UNO | DECIMAL(13,0) | N |  |
| 29 | AG4SPI_DUE | CHAR(1) | N |  |
| 30 | AG4SPI_BLKCONS | CHAR(3) | N |  |
| 31 | AG4SPI_DATBLK | DECIMAL(9,0) | N |  |
| 32 | AG4SPI_BLKINF | CHAR(3) | N |  |
| 33 | AG4SPI_DATINF | DECIMAL(9,0) | N |  |
| 34 | AG4SPI_PDE | CHAR(3) | N |  |
| 35 | AG4SPI_ABI | CHAR(5) | N |  |
| 36 | AG4SPI_DATFINE | DECIMAL(9,0) | N |  |
| 37 | AG4SPI_CODENAS1 | CHAR(10) | N |  |
| 38 | AG4SPI_DTINI60J | DECIMAL(9,0) | N |  |
| 39 | AG4SPI_DTFIN60J | DECIMAL(9,0) | N |  |
| 40 | AG4SPI_INDIM | CHAR(1) | N |  |
| 41 | AG4SPI_SOCPROVPB | CHAR(4) | N |  |
| 42 | AG4SPI_CODPBPROV | CHAR(7) |  |  |
| 43 | AG4SPI_ENA_DT_ISCR | DECIMAL(9,0) | N |  |
| 44 | AG4SPI_ENA_DT_ULT_VERS | DECIMAL(9,0) | N |  |
| 45 | AG4SPI_ENA_FL_AGEV | CHAR(1) | N |  |
| 46 | AG4SPI_ENA_DT_SCAD_AGEV | DECIMAL(9,0) | N |  |

Indici:

- `AG4SPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG4_CD5

*Tabella* – righe: 0
– change data della tabella `AG4`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XAG4_CODAGE | CHAR(6) |  |  |
| 6 | AG4_CODAGE | CHAR(6) | N |  |
| 7 | AG4_AGZ | CHAR(5) | N |  |
| 8 | AG4_PDE | CHAR(3) | N |  |
| 9 | AG4_PERCACC | DECIMAL(7,5) | N |  |
| 10 | AG4_CODENAS | CHAR(7) | N |  |
| 11 | AG4_AGCIDIVA | DECIMAL(7,5) | N |  |
| 12 | AG4_INDISC | CHAR(1) | N |  |
| 13 | AG4_DATALB | DECIMAL(9,0) | N |  |
| 14 | AG4_NUMALB | CHAR(16) | N |  |
| 15 | AG4_PROV | CHAR(2) | N |  |
| 16 | AG4_INI | CHAR(2) | N |  |
| 17 | AG4_DVALESV | DECIMAL(9,0) | N |  |
| 18 | AG4_IMA | CHAR(1) | N |  |
| 19 | AG4_DVALDMA | DECIMAL(9,0) | N |  |
| 20 | AG4_I50 | CHAR(1) | N |  |
| 21 | AG4_IPV | CHAR(1) | N |  |
| 22 | AG4_INDINPS | CHAR(1) | N |  |
| 23 | AG4_DATICON | DECIMAL(9,0) | N |  |
| 24 | AG4_DATFCON | DECIMAL(9,0) | N |  |
| 25 | AG4_INDFAT | CHAR(1) | N |  |
| 26 | AG4_CITT | CHAR(1) | N |  |
| 27 | AG4_DIPL | CHAR(1) | N |  |
| 28 | AG4_GEN | CHAR(1) | N |  |
| 29 | AG4_CIV | CHAR(1) | N |  |
| 30 | AG4_UNO | DECIMAL(13,0) | N |  |
| 31 | AG4_DUE | CHAR(1) | N |  |
| 32 | AG4_BLKCONS | CHAR(3) | N |  |
| 33 | AG4_DATBLK | DECIMAL(9,0) | N |  |
| 34 | AG4_BLKINF | CHAR(3) | N |  |
| 35 | AG4_DATINF | DECIMAL(9,0) | N |  |
| 36 | AG4_ABI | CHAR(5) | N |  |
| 37 | AG4_DATFINE | DECIMAL(9,0) | N |  |
| 38 | AG4_CODENAS1 | CHAR(10) | N |  |
| 39 | AG4_DTINI60J | DECIMAL(9,0) | N |  |
| 40 | AG4_DTFIN60J | DECIMAL(9,0) | N |  |
| 41 | AG4_INDIM | CHAR(1) | N |  |
| 42 | AG4_DTIN50PM | DECIMAL(9,0) | N |  |
| 43 | AG4_DTFN50PM | DECIMAL(9,0) | N |  |
| 44 | AG4_DTIN50GM | DECIMAL(9,0) | N |  |
| 45 | AG4_DTFN50GM | DECIMAL(9,0) | N |  |
| 46 | AG4_ENA_DT_ISCR | DECIMAL(9,0) | N |  |
| 47 | AG4_ENA_DT_ULT_VERS | DECIMAL(9,0) | N |  |
| 48 | AG4_ENA_FL_AGEV | CHAR(1) | N |  |
| 49 | AG4_ENA_DT_SCAD_AGEV | DECIMAL(9,0) | N |  |

Indici:

- `ASN_AG4_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG5M_CD

*Tabella* – righe: 3
– change data della tabella `AG5M`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG5M_RETE | CHAR(1) | N |  |
| 5 | AG5M_CODAGE | CHAR(6) | N |  |
| 6 | AG5M_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AG5M_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AG5M_MODPAG | CHAR(1) | N |  |
| 9 | AG5M_ABI | CHAR(5) | N |  |
| 10 | AG5M_CAB | CHAR(5) | N |  |
| 11 | AG5M_NUMCC | CHAR(12) | N |  |
| 12 | AG5M_INDPRIV | CHAR(1) | N |  |
| 13 | AG5M_CODIBAN | CHAR(27) | N |  |

Indici:

- `IXCDAG5M` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG5SPI_CD

*Tabella* – righe: 2
– change data della tabella `AG5SPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG5SPI_CODAGE | CHAR(6) | N |  |
| 5 | AG5SPI_DVALINI | DECIMAL(9,0) | N |  |
| 6 | AG5SPI_DVALFIN | DECIMAL(9,0) | N |  |
| 7 | AG5SPI_MODPAG | CHAR(1) | N |  |
| 8 | AG5SPI_ABI | CHAR(5) | N |  |
| 9 | AG5SPI_CAB | CHAR(5) | N |  |
| 10 | AG5SPI_NUMCC | CHAR(12) | N |  |
| 11 | AG5SPI_INDPRIV | CHAR(1) | N |  |
| 12 | AG5SPI_CODIBAN | CHAR(27) | N |  |

Indici:

- `AG5SPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AG5_CD

*Tabella* – righe: 14
– change data della tabella `AG5`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AG5_CODAGE | CHAR(6) | N |  |
| 5 | AG5_DVALINI | DECIMAL(9,0) | N |  |
| 6 | AG5_DVALFIN | DECIMAL(9,0) | N |  |
| 7 | AG5_MODPAG | CHAR(1) | N |  |
| 8 | AG5_ABI | CHAR(5) | N |  |
| 9 | AG5_CAB | CHAR(5) | N |  |
| 10 | AG5_NUMCC | CHAR(12) | N |  |
| 11 | AG5_INDPRIV | CHAR(1) | N |  |
| 12 | AG5_CODIBAN | CHAR(27) | N |  |

Indici:

- `AG5D01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGLIVPRO_CD

*Tabella* – righe: 0
– change data della tabella `AGLIVPRO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AGLIVPRO_RETE | CHAR(1) | N |  |
| 5 | AGLIVPRO_CODAGE | CHAR(6) | N |  |
| 6 | AGLIVPRO_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AGLIVPRO_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AGLIVPRO_LIVPROVV | CHAR(4) | N |  |
| 9 | AGLIVPRO_NOTA | CHAR(250) | N |  |

Indici:

- `IXCDAGLIVPRO` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGNM_CD

*Tabella* – righe: 3
– change data della tabella `AGNM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AGNM_RETE | CHAR(1) | N |  |
| 5 | AGNM_CODAGE | CHAR(6) | N |  |
| 6 | AGNM_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AGNM_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AGNM_CITTA | CHAR(25) | N |  |
| 9 | AGNM_PROV | CHAR(2) | N |  |
| 10 | AGNM_INDIR | CHAR(35) | N |  |
| 11 | AGNM_CAP | CHAR(5) | N |  |
| 12 | AGNM_PTEL | CHAR(4) | N |  |
| 13 | AGNM_TEL | CHAR(8) | N |  |
| 14 | AGNM_PRECEL | CHAR(4) | N |  |
| 15 | AGNM_NUMCEL | CHAR(8) | N |  |

Indici:

- `IXCDAGNM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGNSPI_CD

*Tabella* – righe: 14
– change data della tabella `AGNSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AGNSPI_CODAGE | CHAR(6) | N |  |
| 6 | AGNSPI_DVALINI | DECIMAL(9,0) | N |  |
| 7 | AGNSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | AGNSPI_CITTA | CHAR(25) | N |  |
| 9 | AGNSPI_PROV | CHAR(2) | N |  |
| 10 | AGNSPI_INDIR | CHAR(35) | N |  |
| 11 | AGNSPI_CAP | CHAR(5) | N |  |
| 12 | AGNSPI_PTEL | CHAR(4) | N |  |
| 13 | AGNSPI_TEL | CHAR(8) | N |  |
| 14 | AGNSPI_PRECEL | CHAR(4) | N |  |
| 15 | AGNSPI_NUMCEL | CHAR(8) | N |  |

Indici:

- `AGNSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGN_CD5

*Tabella* – righe: 0
– change data della tabella `AGN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AGN_CODAGE | CHAR(6) | N |  |
| 6 | AGN_INDIR | CHAR(35) | N |  |
| 7 | AGN_CAP | CHAR(5) | N |  |
| 8 | AGN_CITTA | CHAR(25) | N |  |
| 9 | AGN_PROV | CHAR(2) | N |  |
| 10 | AGN_DVALFIN | DECIMAL(9,0) | N |  |
| 11 | AGN_PTEL | CHAR(4) | N |  |
| 12 | AGN_TEL | CHAR(8) | N |  |
| 13 | XAGN_DVALFIN | DECIMAL(9,0) |  |  |
| 14 | XAGN_CODAGE | CHAR(6) |  |  |
| 15 | AGN_DVALINI | DECIMAL(9,0) | N |  |
| 16 | AGN_PRECEL | CHAR(4) | N |  |
| 17 | AGN_NUMCEL | CHAR(8) | N |  |

Indici:

- `ASN_AGN_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGPSPI_CD

*Tabella* – righe: 0
– change data della tabella `AGPSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AGPSPI_GRASOTT | CHAR(3) | N |  |
| 5 | AGPSPI_GRADO | CHAR(3) | N |  |
| 6 | AGPSPI_LIVELLO | CHAR(3) | N |  |
| 7 | AGPSPI_TIPORETE | CHAR(1) | N |  |
| 8 | AGPSPI_AREA | CHAR(3) | N |  |
| 9 | AGPSPI_TIPOCOMM | CHAR(1) | N |  |
| 10 | AGPSPI_SEGNO | CHAR(1) | N |  |
| 11 | AGPSPI_PERC | DECIMAL(7,5) | N |  |
| 12 | AGPSPI_DVALINI | DECIMAL(9,0) | N |  |
| 13 | AGPSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 14 | AGPSPI_GRPPROV | DECIMAL(3,0) | N |  |
| 15 | AGPSPI_REGDIS | CHAR(4) | N |  |

Indici:

- `AGPSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGP_CD

*Tabella* – righe: 0
– change data della tabella `AGP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AGP_GRASOTT | CHAR(3) | N |  |
| 5 | AGP_GRADO | CHAR(3) | N |  |
| 6 | AGP_TIPORETE | CHAR(1) | N |  |
| 7 | AGP_AREA | CHAR(3) | N |  |
| 8 | AGP_TIPOCOMM | CHAR(1) | N |  |
| 9 | AGP_SEGNO | CHAR(1) | N |  |
| 10 | AGP_PERC | DECIMAL(7,5) | N |  |
| 11 | AGP_DVALINI | DECIMAL(9,0) | N |  |
| 12 | AGP_DVALFIN | DECIMAL(9,0) | N |  |
| 13 | AGP_GRPPROV | DECIMAL(3,0) | N |  |
| 14 | AGP_REGDIS | CHAR(4) | N |  |

Indici:

- `AGPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGSM_CD

*Tabella* – righe: 0
– change data della tabella `AGSM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AGSM_RETE | CHAR(1) | N |  |
| 5 | AGSM_CODAGE | CHAR(6) | N |  |
| 6 | AGSM_TIPORETE | CHAR(1) | N |  |
| 7 | AGSM_DVALINI | DECIMAL(9,0) | N |  |
| 8 | AGSM_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | AGSM_CODAGESUP | CHAR(6) | N |  |

Indici:

- `IXCDAGSM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGSSPI_CD

*Tabella* – righe: 2
– change data della tabella `AGSSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AGSSPI_CODAGE | CHAR(6) | N |  |
| 6 | AGSSPI_TIPORETE | CHAR(1) | N |  |
| 7 | AGSSPI_DVALINI | DECIMAL(9,0) | N |  |
| 8 | AGSSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | AGSSPI_CODAGESUP | CHAR(6) | N |  |

Indici:

- `AGSSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AGS_CD

*Tabella* – righe: 21
– change data della tabella `AGS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | AGS_CODAGE | CHAR(6) | N |  |
| 6 | AGS_TIPORETE | CHAR(1) | N |  |
| 7 | AGS_DVALINI | DECIMAL(9,0) | N |  |
| 8 | AGS_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | AGS_CODAGESUP | CHAR(6) | N |  |

Indici:

- `AGSD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AINSSPI_CD

*Tabella* – righe: 5
– change data della tabella `AINSSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AINSSPI_CODAGE | CHAR(6) | N |  |
| 5 | AINSSPI_CODAGEPRE | CHAR(6) | N |  |
| 6 | AINSSPI_TITSTU | CHAR(3) | N |  |
| 7 | AINSSPI_LAVPRE | CHAR(2) | N |  |
| 8 | AINSSPI_AZPROV | CHAR(2) | N |  |
| 9 | AINSSPI_ABI | CHAR(5) | N |  |
| 10 | AINSSPI_PDLPRE | CHAR(2) | N |  |
| 11 | AINSSPI_CERTP | CHAR(2) | N |  |
| 12 | AINSSPI_FIRMA | CHAR(2) | N |  |
| 13 | AINSSPI_ISPET | CHAR(1) | N |  |
| 14 | AINSSPI_NOTE | CHAR(30) | N |  |
| 15 | AINSSPI_ATTIVITA | CHAR(30) | N |  |
| 16 | AINSSPI_SETTMERC | CHAR(30) | N |  |
| 17 | AINSSPI_DTPRE | DECIMAL(9,0) | N |  |
| 18 | AINSSPI_DTPOST | DECIMAL(9,0) | N |  |
| 19 | AINSSPI_TIPINCENT | CHAR(1) | N |  |
| 20 | AINSSPI_NUMCLI | DECIMAL(9,0) | N |  |
| 21 | AINSSPI_POTENZ | DECIMAL(15,2) | N |  |
| 22 | AINSSPI_MOD101 | DECIMAL(15,2) | N |  |
| 23 | AINSSPI_DTSCAINC | DECIMAL(9,0) | N |  |
| 24 | AINSSPI_TIPINCACO | CHAR(5) | N |  |

Indici:

- `AINSSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AINS_CD

*Tabella* – righe: 17
– change data della tabella `AINS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AINS_CODAGE | CHAR(6) | N |  |
| 5 | AINS_CODAGEPRE | CHAR(6) | N |  |
| 6 | AINS_TITSTU | CHAR(3) | N |  |
| 7 | AINS_LAVPRE | CHAR(2) | N |  |
| 8 | AINS_AZPROV | CHAR(2) | N |  |
| 9 | AINS_ABI | CHAR(5) | N |  |
| 10 | AINS_PDLPRE | CHAR(2) | N |  |
| 11 | AINS_CERTP | CHAR(2) | N |  |
| 12 | AINS_FIRMA | CHAR(2) | N |  |
| 13 | AINS_ISPET | CHAR(1) | N |  |
| 14 | AINS_NOTE | CHAR(30) | N |  |
| 15 | AINS_ATTIVITA | CHAR(30) | N |  |
| 16 | AINS_SETTMERC | CHAR(30) | N |  |
| 17 | AINS_DTPRE | DECIMAL(9,0) | N |  |
| 18 | AINS_DTPOST | DECIMAL(9,0) | N |  |
| 19 | AINS_TIPINCENT | CHAR(1) | N |  |
| 20 | AINS_NUMCLI | DECIMAL(9,0) | N |  |
| 21 | AINS_POTENZ | DECIMAL(15,2) | N |  |
| 22 | AINS_MOD101 | DECIMAL(15,2) | N |  |
| 23 | AINS_DTSCAINC | DECIMAL(9,0) | N |  |
| 24 | AINS_TIPINCACO | CHAR(5) | N |  |

Indici:

- `AINSD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ALPS_CD

*Tabella* – righe: 0
– change data della tabella `ALPS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ALPS_CODPROD | CHAR(2) | N |  |
| 5 | ALPS_SUBPROD | CHAR(5) | N |  |
| 6 | ALPS_CODPRI | CHAR(1) | N |  |
| 7 | ALPS_ADSIA | CHAR(1) | N |  |
| 8 | ALPS_TIPOTAB | CHAR(1) | N |  |
| 9 | ALPS_DIRCUM | CHAR(1) | N |  |
| 10 | ALPS_CIRCUITO | CHAR(1) | N |  |
| 11 | ALPS_INDWARR | CHAR(1) | N |  |
| 12 | ALPS_INDGAR | CHAR(1) | N |  |
| 13 | ALPS_PRODO1 | CHAR(2) | N |  |
| 14 | ALPS_DVALINI | DECIMAL(9,0) | N |  |
| 15 | ALPS_DVALFIN | DECIMAL(9,0) | N |  |
| 16 | ALPS_PERCINV | DECIMAL(5,2) | N |  |
| 17 | ALPS_PREMIO | CHAR(1) | N |  |
| 18 | ALPS_INDGDOE | CHAR(2) | N |  |

Indici:

- `ALPSD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ALSL_CD

*Tabella* – righe: 12.016
– change data della tabella `ALSL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ALSL_CODPROD | CHAR(2) | N |  |
| 5 | ALSL_CODSUP | CHAR(5) | N |  |
| 6 | ALSL_CODDIP | CHAR(5) | N |  |
| 7 | ALSL_DVALINI | DECIMAL(9,0) | N |  |
| 8 | ALSL_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | ALSL_ORDER | DECIMAL(3,0) | N |  |
| 10 | ALSL_MINCVN | DECIMAL(15,2) | N |  |
| 11 | ALSL_MAXCVN | DECIMAL(15,2) | N |  |
| 12 | ALSL_LIVEL | DECIMAL(3,0) | N |  |

Indici:

- `ALSLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_AMOVST_CD

*Tabella* – righe: 92
– change data della tabella `AMOVST`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | AMOVST_CODCONF | CHAR(11) | N |  |
| 5 | AMOVST_CODPROD | CHAR(2) | N |  |
| 6 | AMOVST_LINEA | CHAR(5) | N |  |
| 7 | AMOVST_ISIN | CHAR(12) | N |  |
| 8 | AMOVST_MERCATO | CHAR(3) | N |  |
| 9 | AMOVST_PROGMOV | SMALLINT | N |  |
| 10 | AMOVST_PROGOPE | SMALLINT | N |  |
| 11 | AMOVST_TIPOPER | CHAR(2) | N |  |
| 12 | AMOVST_TIPOPES | CHAR(2) | N |  |
| 13 | AMOVST_CODULLA | CHAR(6) | N |  |
| 14 | AMOVST_TIPOMOV | CHAR(1) | N |  |
| 15 | AMOVST_IMPOPER | DECIMAL(15,7) | N |  |
| 16 | AMOVST_PRTOPER | DECIMAL(15,7) | N |  |
| 17 | AMOVST_VALNAV | DECIMAL(15,7) | N |  |
| 18 | AMOVST_DATANAV | DECIMAL(9,0) | N |  |
| 19 | AMOVST_PERCFND | DECIMAL(3,0) | N |  |
| 20 | AMOVST_CODDIV | CHAR(3) | N |  |
| 21 | AMOVST_NAVDIV | DECIMAL(15,7) | N |  |
| 22 | AMOVST_CAMBIO | DECIMAL(13,5) | N |  |
| 23 | AMOVST_PAYIN | DECIMAL(15,2) | N |  |
| 24 | AMOVST_PAYOUT | DECIMAL(15,2) | N |  |
| 25 | AMOVST_RETE | CHAR(1) | N |  |
| 26 | AMOVST_DATAVAL | DECIMAL(9,0) | N | DATA VALUTA |

Indici:

- `AMOVSTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCCM_CD

*Tabella* – righe: 1
– change data della tabella `ANCCM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANCCM_RETE | CHAR(1) | N |  |
| 5 | ANCCM_CODANA | CHAR(12) | N |  |
| 6 | ANCCM_PRGCON | SMALLINT | N |  |
| 7 | ANCCM_ABI | CHAR(5) | N |  |
| 8 | ANCCM_CAB | CHAR(5) | N |  |
| 9 | ANCCM_CONTO | CHAR(30) | N |  |
| 10 | ANCCM_CIN | CHAR(1) | N |  |
| 11 | ANCCM_NAZIOIBAN | CHAR(2) | N |  |
| 12 | ANCCM_CINIBAN | CHAR(2) | N |  |

Indici:

- `IXCDANCCM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCCSPI_CD

*Tabella* – righe: 0
– change data della tabella `ANCCSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ANCCSPI_CODANA | CHAR(12) | N |  |
| 6 | ANCCSPI_PRGCON | SMALLINT | N |  |
| 7 | ANCCSPI_ABI | CHAR(5) | N |  |
| 8 | ANCCSPI_CAB | CHAR(5) | N |  |
| 9 | ANCCSPI_CONTO | CHAR(30) | N |  |

Indici:

- `ANCCSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCC_CD

*Tabella* – righe: 12
– change data della tabella `ANCC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ANCC_CODANA | CHAR(12) | N |  |
| 6 | ANCC_PRGCON | SMALLINT | N |  |
| 7 | ANCC_ABI | CHAR(5) | N |  |
| 8 | ANCC_CAB | CHAR(5) | N |  |
| 9 | ANCC_CONTO | CHAR(30) | N |  |

Indici:

- `ANCCD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCLIM_CD

*Tabella* – righe: 55
– change data della tabella `ANCLIM` (FJBM: TABELLA DATI ANAGRAFICI CLIENRE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANCLIM_CODANA | CHAR(12) | N |  |
| 5 | XANCLIM_CODANA | CHAR(12) |  |  |
| 6 | ANCLIM_COGNOME | CHAR(25) | N |  |
| 7 | ANCLIM_NOME | CHAR(25) | N |  |
| 8 | ANCLIM_DTNAS | INTEGER | N |  |
| 9 | ANCLIM_SEX | CHAR(1) | N |  |
| 10 | ANCLIM_CMNAS | CHAR(25) | N |  |
| 11 | ANCLIM_CDFIS | CHAR(16) | N |  |
| 12 | ANCLIM_NAZION | CHAR(25) | N |  |
| 13 | ANCLIM_CITTAD | CHAR(25) | N |  |
| 14 | ANCLIM_NRE | CHAR(1) | N |  |
| 15 | ANCLIM_GRP | CHAR(1) | N |  |
| 16 | ANCLIM_FORCOS | CHAR(3) | N |  |
| 17 | ANCLIM_PROF | CHAR(2) | N |  |
| 18 | ANCLIM_TITSTD | CHAR(1) | N |  |
| 19 | ANCLIM_MININT | CHAR(1) | N |  |
| 20 | ANCLIM_DECEDT | CHAR(1) | N |  |
| 21 | ANCLIM_F_CDFIS | CHAR(1) | N |  |
| 22 | ANCLIM_F_DOCUM | CHAR(1) | N |  |
| 23 | ANCLIM_F_INDIR | CHAR(1) | N |  |
| 24 | ANCLIM_DTULVAR | INTEGER | N |  |
| 25 | ANCLIM_EMAIL | CHAR(50) | N |  |
| 26 | ANCLIM_NUMCELL | CHAR(15) | N |  |
| 27 | ANCLIM_FLAGSMS | CHAR(1) | N |  |
| 28 | ANCLIM_IPM | CHAR(1) | N |  |
| 29 | ANCLIM_DTCOLL | DECIMAL(9,0) | N |  |
| 30 | ANCLIM_DTLETCOL | DECIMAL(9,0) | N |  |
| 31 | ANCLIM_ALERTROL | CHAR(1) | N |  |
| 32 | ANCLIM_EMAILROL | CHAR(50) | N |  |
| 33 | ANCLIM_DATACELL | DECIMAL(9,0) | N |  |
| 34 | ANCLIM_CMNAS_ESTERO | CHAR(25) | N |  |
| 35 | ANCLIM_CITTAD2 | CHAR(25) | N |  |
| 36 | ANCLIM_TIPO_CDN | CHAR(5) | N |  |
| 37 | ANCLIM_NOME_NAG | CHAR(64) | N |  |
| 38 | ANCLIM_COGNOME_NAG | CHAR(64) | N |  |
| 39 | ANCLIM_CMNAS_NAG | CHAR(64) | N |  |
| 40 | ANCLIM_PROVINCIA | CHAR(3) | N |  |
| 41 | ANCLIM_NAZION_NAG | CHAR(64) | N |  |
| 42 | ANCLIM_CITTAD_NAG | CHAR(64) | N |  |
| 43 | ANCLIM_NUM_CCIAA | CHAR(10) | N |  |
| 44 | ANCLIM_PROV_CCIAA | CHAR(2) | N |  |
| 45 | ANCLIM_PIVA_NAG | CHAR(16) | N |  |
| 46 | ANCLIM_TIPO_CODICE_UNIVOCO | CHAR(5) | N |  |
| 47 | ANCLIM_CODICE_UNIVOCO | CHAR(20) | N |  |
| 48 | ANCLIM_TIPO_CODICE_UNIVOCO2 | CHAR(5) | N |  |
| 49 | ANCLIM_CODICE_UNIVOCO2 | CHAR(20) | N |  |
| 50 | ANCLIM_FLAG_DIPEND | CHAR(1) | N |  |
| 51 | ANCLIM_CHECK_PROFIT | CHAR(1) | N |  |
| 52 | ANCLIM_T2A | CHAR(1) | N |  |
| 53 | ANCLIM_T2B | CHAR(1) | N |  |
| 54 | ANCLIM_DATA_COST | DECIMAL(9,0) | N |  |
| 55 | ANCLIM_CITTAD2_NAG | CHAR(64) | N |  |
| 56 | ANCLIM_DATA_DECESSO | DECIMAL(9,0) | N |  |
| 57 | ANCLIM_PREFISSO_INTERNAZ | CHAR(6) | N |  |

Indici:

- `IXCDANCLIM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCLISPI_CD

*Tabella* – righe: 58
– change data della tabella `ANCLISPI` (FJBM: TABELLA ANAGRAFICA CLIENTI SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANCLISPI_CODANA | CHAR(12) |  |  |
| 6 | ANCLISPI_CODANA | CHAR(12) | N |  |
| 7 | ANCLISPI_COGNOME | CHAR(25) | N |  |
| 8 | ANCLISPI_NOME | CHAR(25) | N |  |
| 9 | ANCLISPI_DTNAS | INTEGER | N |  |
| 10 | ANCLISPI_SEX | CHAR(1) | N |  |
| 11 | ANCLISPI_CMNAS | CHAR(25) | N |  |
| 12 | ANCLISPI_CDFIS | CHAR(16) | N |  |
| 13 | ANCLISPI_NAZION | CHAR(25) | N |  |
| 14 | ANCLISPI_CITTAD | CHAR(25) | N |  |
| 15 | ANCLISPI_FORCOS | CHAR(3) | N |  |
| 16 | ANCLISPI_PROF | CHAR(2) | N |  |
| 17 | ANCLISPI_TITSTD | CHAR(1) | N |  |
| 18 | ANCLISPI_MININT | CHAR(1) | N |  |
| 19 | ANCLISPI_F_CDFIS | CHAR(1) | N |  |
| 20 | ANCLISPI_F_DOCUM | CHAR(1) | N |  |
| 21 | ANCLISPI_F_INDIR | CHAR(1) | N |  |
| 22 | ANCLISPI_DTFIRMA | DECIMAL(9,0) | N | DATA FIRMA CONTRATTO DI CONSULENZA MIFID |
| 23 | ANCLISPI_CODQUEST | CHAR(20) | N | CODICE QUESTIONARIO PROFILATURA MIFID |
| 24 | ANCLISPI_CODANASPI | CHAR(9) |  |  |
| 25 | ANCLISPI_NRE | CHAR(1) |  |  |
| 26 | ANCLISPI_GRP | CHAR(1) |  |  |
| 27 | ANCLISPI_DECEDT | CHAR(1) |  |  |
| 28 | ANCLISPI_DTULVAR | INTEGER |  |  |
| 29 | ANCLISPI_EMAIL | CHAR(50) |  |  |
| 30 | ANCLISPI_NUMCELL | CHAR(15) |  |  |
| 31 | ANCLISPI_FLAGSMS | CHAR(1) |  |  |
| 32 | ANCLISPI_TIPCLI | CHAR(1) |  |  |
| 33 | ANCLISPI_DTLETTCC | DECIMAL(9,0) |  |  |
| 34 | ANCLISPI_IPM | CHAR(1) |  |  |
| 35 | ANCLISPI_DTCOLL | DECIMAL(9,0) |  |  |
| 36 | ANCLISPI_DTLETCOL | DECIMAL(9,0) |  |  |
| 37 | ANCLISPI_DATACELL | DECIMAL(9,0) |  |  |

Indici:

- `ANCLISPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCLI_CD5

*Tabella* – righe: 0
– change data della tabella `ANCLI` (FJBM: TABELLA ANAGRAFICA CLIENTI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANCLI_CODANA | CHAR(12) |  |  |
| 6 | ANCLI_CODANA | CHAR(12) | N |  |
| 7 | ANCLI_COGNOME | CHAR(25) | N |  |
| 8 | ANCLI_NOME | CHAR(25) | N |  |
| 9 | ANCLI_DTNAS | INTEGER | N |  |
| 10 | ANCLI_SEX | CHAR(1) | N |  |
| 11 | ANCLI_CMNAS | CHAR(25) | N |  |
| 12 | ANCLI_CDFIS | CHAR(16) | N |  |
| 13 | ANCLI_NAZION | CHAR(25) | N |  |
| 14 | ANCLI_CITTAD | CHAR(25) | N |  |
| 15 | ANCLI_FORCOS | CHAR(3) | N |  |
| 16 | ANCLI_PROF | CHAR(2) | N |  |
| 17 | ANCLI_TITSTD | CHAR(1) | N |  |
| 18 | ANCLI_MININT | CHAR(1) | N |  |
| 19 | ANCLI_F_CDFIS | CHAR(1) | N |  |
| 20 | ANCLI_F_DOCUM | CHAR(1) | N |  |
| 21 | ANCLI_F_INDIR | CHAR(1) | N |  |
| 22 | ANCLI_DTFIRMA | DECIMAL(9,0) | N | DATA FIRMA CONTRATTO DI CONSULENZA MIFID |
| 23 | ANCLI_CODQUEST | CHAR(20) | N | CODICE QUESTIONARIO PROFILATURA MIFID |
| 24 | ANCLI_NRE | CHAR(1) |  |  |
| 25 | ANCLI_GRP | CHAR(1) |  |  |
| 26 | ANCLI_DECEDT | CHAR(1) |  |  |
| 27 | ANCLI_DTULVAR | INTEGER |  |  |
| 28 | ANCLI_EMAIL | CHAR(50) |  |  |
| 29 | ANCLI_NUMCELL | CHAR(15) |  |  |
| 30 | ANCLI_FLAGSMS | CHAR(1) |  |  |
| 31 | ANCLI_TIPCLI | CHAR(1) |  |  |
| 32 | ANCLI_DTLETTCC | DECIMAL(9,0) |  |  |
| 33 | ANCLI_IPM | CHAR(1) |  |  |
| 34 | ANCLI_DTCOLL | DECIMAL(9,0) |  |  |
| 35 | ANCLI_DTLETCOL | DECIMAL(9,0) |  |  |
| 36 | ANCLI_DATACELL | DECIMAL(9,0) |  |  |

Indici:

- `ASN_ANCLI_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCONM_CD

*Tabella* – righe: 6
– change data della tabella `ANCONM` (FJBM: TABELLA COLLEGAMENTO CLIENTE CONTRATTO)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANCONM_RETE | CHAR(1) | N |  |
| 5 | ANCONM_CODCONF | CHAR(11) | N |  |
| 6 | XANCONM_CODCONF | CHAR(11) |  |  |
| 7 | ANCONM_CODPROD | CHAR(2) | N |  |
| 8 | ANCONM_POSMAND | CHAR(2) | N |  |
| 9 | XANCONM_POSMAND | CHAR(2) |  |  |
| 10 | ANCONM_CODANA | CHAR(12) | N |  |
| 11 | XANCONM_CODANA | CHAR(12) |  |  |
| 12 | ANCONM_STATO | CHAR(1) | N |  |
| 13 | ANCONM_TPPOS | CHAR(1) | N |  |
| 14 | ANCONM_F_SCHEDA | CHAR(1) | N |  |
| 15 | ANCONM_ID1 | DECIMAL(15,0) | N |  |
| 16 | ANCONM_PRGCONF2 | CHAR(11) | N |  |

Indici:

- `IXCDANCONM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCONSPI_CD

*Tabella* – righe: 33
– change data della tabella `ANCONSPI` (FJBM: TABELLA RELAZIONI CODICE CLIENTE/CODICE CONTRATTO SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANCONSPI_CODCONF | CHAR(11) |  |  |
| 6 | ANCONSPI_CODCONF | CHAR(11) | N |  |
| 7 | ANCONSPI_CODPROD | CHAR(2) | N |  |
| 8 | XANCONSPI_POSMAND | CHAR(2) |  |  |
| 9 | ANCONSPI_POSMAND | CHAR(2) | N |  |
| 10 | XANCONSPI_CODANA | CHAR(12) |  |  |
| 11 | ANCONSPI_CODANA | CHAR(12) | N |  |
| 12 | ANCONSPI_STATO | CHAR(1) | N |  |
| 13 | ANCONSPI_TPPOS | CHAR(1) | N |  |
| 14 | ANCONSPI_F_SCHEDA | CHAR(1) | N |  |
| 15 | ANCONSPI_ID1 | DECIMAL(15,0) | N |  |
| 16 | ANCONSPI_PRGCONF2 | CHAR(11) | N |  |

Indici:

- `ANCONSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANCON_CD5

*Tabella* – righe: 0
– change data della tabella `ANCON` (FJBM: TABELLA RELAZIONI CODICE CLIENTE/CODICE CONTRATTO)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANCON_CODCONF | CHAR(11) |  |  |
| 6 | XANCON_POSMAND | CHAR(2) |  |  |
| 7 | XANCON_CODANA | CHAR(12) |  |  |
| 8 | ANCON_CODCONF | CHAR(11) | N |  |
| 9 | ANCON_CODPROD | CHAR(2) | N |  |
| 10 | ANCON_POSMAND | CHAR(2) | N |  |
| 11 | ANCON_CODANA | CHAR(12) | N |  |
| 12 | ANCON_TPPOS | CHAR(1) | N |  |
| 13 | ANCON_STATO | CHAR(1) |  |  |
| 14 | ANCON_F_SCHEDA | CHAR(1) |  |  |
| 15 | ANCON_ID1 | DECIMAL(15,0) |  |  |
| 16 | ANCON_PRGCONF2 | CHAR(11) |  |  |

Indici:

- `ASN_ANCON_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANDEC_CD

*Tabella* – righe: 0
– change data della tabella `ANDEC` (FJBM: TABELLA DESCRIZIONI PRIVACY)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANDEC_TIPO | CHAR(1) | N |  |
| 5 | ANDEC_PROGR | DECIMAL(3,0) | N |  |
| 6 | ANDEC_DESCR | CHAR(80) | N |  |
| 7 | ANDEC_COMPOS | CHAR(50) | N |  |

Indici:

- `ANDECD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANDOCM_CD

*Tabella* – righe: 19
– change data della tabella `ANDOCM` (FJBM: TABELLA DATI DOCUMENTO CLIENTE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANDOCM_CODANA | CHAR(12) | N |  |
| 5 | XANDOCM_CODANA | CHAR(12) |  |  |
| 6 | ANDOCM_TIPODOC | CHAR(3) | N |  |
| 7 | ANDOCM_NUMDOC | CHAR(20) | N |  |
| 8 | ANDOCM_RILDOC | CHAR(20) | N |  |
| 9 | ANDOCM_LUODOC | CHAR(25) | N |  |
| 10 | ANDOCM_PRVDOC | CHAR(2) | N |  |
| 11 | ANDOCM_DOCDAT | INTEGER | N |  |
| 12 | ANDOCM_DT_SCAD | DECIMAL(9,0) | N |  |
| 13 | ANDOCM_STATO_EMISSIONE | CHAR(64) | N |  |
| 14 | ANDOCM_LUODOC_NAG | CHAR(64) | N |  |
| 15 | ANDOCM_SIGLA_ENTE | CHAR(5) | N |  |
| 16 | ANDOCM_RILDOC_NAG | CHAR(64) | N |  |
| 17 | ANDOCM_STATO_SCAN | CHAR(1) | N |  |
| 18 | ANDOCM_ID_FILE | CHAR(41) | N |  |

Indici:

- `IXCDANDOCM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANDOCSPI_CD

*Tabella* – righe: 19
– change data della tabella `ANDOCSPI` (FJBM: TABELLA ANAGRAFICA DEI DOCUMENTI CLIENTI SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANDOCSPI_CODANA | CHAR(12) |  |  |
| 6 | ANDOCSPI_CODANA | CHAR(12) | N |  |
| 7 | ANDOCSPI_TIPODOC | CHAR(3) | N |  |
| 8 | ANDOCSPI_NUMDOC | CHAR(20) | N |  |
| 9 | ANDOCSPI_RILDOC | CHAR(20) | N |  |
| 10 | ANDOCSPI_LUODOC | CHAR(25) | N |  |
| 11 | ANDOCSPI_PRVDOC | CHAR(2) | N |  |
| 12 | ANDOCSPI_DOCDAT | INTEGER | N |  |

Indici:

- `ANDOCSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANDOC_CD5

*Tabella* – righe: 0
– change data della tabella `ANDOC` (FJBM: TABELLA ANAGRAFICA DEI DOCUMENTI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANDOC_CODANA | CHAR(12) |  |  |
| 6 | ANDOC_CODANA | CHAR(12) | N |  |
| 7 | ANDOC_TIPODOC | CHAR(3) | N |  |
| 8 | ANDOC_NUMDOC | CHAR(20) | N |  |
| 9 | ANDOC_RILDOC | CHAR(20) | N |  |
| 10 | ANDOC_LUODOC | CHAR(25) | N |  |
| 11 | ANDOC_DOCDAT | INTEGER | N |  |

Indici:

- `ASN_ANDOC_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANINDM_CD

*Tabella* – righe: 29
– change data della tabella `ANINDM` (FJBM: TABELLA DATI INDIRIZZO CLIENTE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANINDM_RETE | CHAR(1) | N |  |
| 5 | ANINDM_CODANA | CHAR(12) | N |  |
| 6 | XANINDM_CODANA | CHAR(12) |  |  |
| 7 | ANINDM_CODCONF | CHAR(11) | N |  |
| 8 | XANINDM_CODCONF | CHAR(11) |  |  |
| 9 | ANINDM_INDIR | CHAR(44) | N |  |
| 10 | ANINDM_CAP | CHAR(5) | N |  |
| 11 | ANINDM_CITTA | CHAR(25) | N |  |
| 12 | ANINDM_PROV | CHAR(2) | N |  |
| 13 | ANINDM_NAZION | CHAR(25) | N |  |
| 14 | ANINDM_PRESSO | CHAR(32) | N |  |
| 15 | ANINDM_PTELC | CHAR(5) | N |  |
| 16 | ANINDM_NTELC | CHAR(10) | N |  |
| 17 | ANINDM_VOTO | CHAR(4) | N |  |
| 18 | ANINDM_TOPONIMO_NAG | CHAR(32) | N |  |
| 19 | ANINDM_INDIRIZZO_NAG | CHAR(64) | N |  |
| 20 | ANINDM_NUM_CIVICO_NAG | CHAR(32) | N |  |
| 21 | ANINDM_COMUNE_RES_NAG | CHAR(64) | N |  |
| 22 | ANINDM_CAP_NAG | CHAR(10) | N |  |
| 23 | ANINDM_NAZION_NAG | CHAR(64) | N |  |
| 24 | ANINDM_FRAZIONE | CHAR(64) | N |  |
| 25 | ANINDM_ID_INDIRIZZO | DECIMAL(17,0) | N |  |
| 26 | ANINDM_PREFISSO_INTERNAZ | CHAR(6) | N |  |

Indici:

- `IXCDANINDM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANINDSPI_CD

*Tabella* – righe: 25
– change data della tabella `ANINDSPI` (FJBM: TABELLA ANAGRAFICA DEGLI INDIRIZZI CLIENTI SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANINDSPI_CODANA | CHAR(12) |  |  |
| 6 | ANINDSPI_CODANA | CHAR(12) | N |  |
| 7 | XANINDSPI_CODCONF | CHAR(11) |  |  |
| 8 | ANINDSPI_CODCONF | CHAR(11) | N |  |
| 9 | ANINDSPI_INDIR | CHAR(44) | N |  |
| 10 | ANINDSPI_CAP | CHAR(5) | N |  |
| 11 | ANINDSPI_CITTA | CHAR(25) | N |  |
| 12 | ANINDSPI_PROV | CHAR(2) | N |  |
| 13 | ANINDSPI_NAZION | CHAR(25) | N |  |
| 14 | ANINDSPI_PRESSO | CHAR(32) | N |  |
| 15 | ANINDSPI_PTELC | CHAR(5) | N |  |
| 16 | ANINDSPI_NTELC | CHAR(10) | N |  |
| 17 | ANINDSPI_VOTO | CHAR(4) | N |  |

Indici:

- `ANINDSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANIND_CD5

*Tabella* – righe: 0
– change data della tabella `ANIND` (FJBM: TABELLA ANAGRAFICA DEGLI INDIRIZZI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XANIND_CODANA | CHAR(12) |  |  |
| 6 | XANIND_CODCONF | CHAR(11) |  |  |
| 7 | ANIND_CODANA | CHAR(12) | N |  |
| 8 | ANIND_CODCONF | CHAR(11) | N |  |
| 9 | ANIND_INDIR | CHAR(44) | N |  |
| 10 | ANIND_CAP | CHAR(5) | N |  |
| 11 | ANIND_CITTA | CHAR(25) | N |  |
| 12 | ANIND_PROV | CHAR(2) | N |  |
| 13 | ANIND_NAZION | CHAR(25) | N |  |
| 14 | ANIND_PRESSO | CHAR(32) | N |  |
| 15 | ANIND_PTELC | CHAR(5) | N |  |
| 16 | ANIND_NTELC | CHAR(10) | N |  |
| 17 | ANIND_VOTO | CHAR(4) |  |  |

Indici:

- `ASN_ANIND_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANPRIM_CD

*Tabella* – righe: 3
– change data della tabella `ANPRIM` (FJBM: TABELLA STORICA VARIAZIONI ANAGRAFICHE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANPRIM_RETE | CHAR(1) | N |  |
| 5 | ANPRIM_CDFIS | CHAR(16) | N |  |
| 6 | ANPRIM_CODCONF | CHAR(11) | N |  |
| 7 | ANPRIM_CODCONF2 | CHAR(11) | N |  |
| 8 | ANPRIM_CC | CHAR(12) | N |  |
| 9 | ANPRIM_PRIVACY | DECIMAL(3,0) | N |  |
| 10 | ANPRIM_RISCHIO | CHAR(1) | N |  |
| 11 | ANPRIM_USERID | CHAR(8) | N |  |
| 12 | ANPRIM_DATVAR | DECIMAL(9,0) | N |  |
| 13 | ANPRIM_ORAVAR | DECIMAL(9,0) | N |  |
| 14 | ANPRIM_CIN | CHAR(1) | N |  |
| 15 | ANPRIM_DIN | CHAR(1) | N |  |
| 16 | ANPRIM_FLAG1 | CHAR(1) | N |  |
| 17 | ANPRIM_FLAG2 | CHAR(1) | N |  |
| 18 | ANPRIM_FLAG3 | CHAR(1) | N |  |
| 19 | ANPRIM_FLAG4 | CHAR(1) | N |  |
| 20 | ANPRIM_FLAG5 | CHAR(1) | N |  |
| 21 | ANPRIM_FLAG6 | CHAR(1) | N |  |

Indici:

- `IXCDANPRIM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANPRISPI_CD

*Tabella* – righe: 9
– change data della tabella `ANPRISPI` (FJBM: TABELLA PRIVACY DELLA CLIENTELA SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANPRISPI_CDFIS | CHAR(16) | N |  |
| 5 | ANPRISPI_CODCONF | CHAR(11) | N |  |
| 6 | ANPRISPI_CODCONF2 | CHAR(11) | N |  |
| 7 | ANPRISPI_CC | CHAR(12) | N |  |
| 8 | ANPRISPI_PRIVACY | DECIMAL(3,0) | N |  |
| 9 | ANPRISPI_RISCHIO | CHAR(1) | N |  |
| 10 | ANPRISPI_USERID | CHAR(8) | N |  |
| 11 | ANPRISPI_DATVAR | DECIMAL(9,0) | N |  |
| 12 | ANPRISPI_ORAVAR | DECIMAL(9,0) | N |  |
| 13 | ANPRISPI_CIN | CHAR(1) | N |  |
| 14 | ANPRISPI_DIN | CHAR(1) | N | PRESENZA DINIEGO |

Indici:

- `ANPRISPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANPRI_CD

*Tabella* – righe: 53
– change data della tabella `ANPRI` (FJBM: TABELLA PRIVACY DELLA CLIENTELA)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANPRI_CDFIS | CHAR(16) | N |  |
| 5 | ANPRI_CODCONF | CHAR(11) | N |  |
| 6 | ANPRI_CODCONF2 | CHAR(11) | N |  |
| 7 | ANPRI_CC | CHAR(12) | N |  |
| 8 | ANPRI_PRIVACY | DECIMAL(3,0) | N |  |
| 9 | ANPRI_RISCHIO | CHAR(1) | N |  |
| 10 | ANPRI_USERID | CHAR(8) | N |  |
| 11 | ANPRI_DATVAR | DECIMAL(9,0) | N |  |
| 12 | ANPRI_ORAVAR | DECIMAL(9,0) | N |  |
| 13 | ANPRI_CIN | CHAR(1) | N |  |
| 14 | ANPRI_DIN | CHAR(1) | N | PRESENZA DINIEGO |

Indici:

- `ANPRID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANRETE_CD

*Tabella* – righe: 7
– change data della tabella `ANRETE` (FJBM: TABELLA COLLEGAMENTO CLIENTE RETE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANRETE_RETE | CHAR(1) | N |  |
| 5 | ANRETE_CDFIS | CHAR(16) | N |  |
| 6 | ANRETE_DTINSER | DECIMAL(9,0) | N |  |
| 7 | ANRETE_RAESEN | CHAR(1) | N |  |
| 8 | ANRETE_DTFIRMA | DECIMAL(9,0) | N |  |
| 9 | ANRETE_CODQUEST | CHAR(20) | N |  |
| 10 | ANRETE_TIPCLI | CHAR(1) | N |  |
| 11 | ANRETE_DTLETCC | DECIMAL(9,0) | N |  |

Indici:

- `IXCDANRETE` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANSERM_CD

*Tabella* – righe: 10
– change data della tabella `ANSERM` (FJBM: TABELLA DATI ADEGUATA VERIFICA CLIENTE)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANSERM_CODANA | CHAR(12) | N |  |
| 5 | ANSERM_SETTORE | CHAR(3) | N |  |
| 6 | ANSERM_RAMO | CHAR(3) | N |  |
| 7 | ANSERM_TAE | DECIMAL(3,0) | N |  |
| 8 | ANSERM_PROV | CHAR(2) | N |  |
| 9 | ANSERM_NAZIONE | CHAR(25) | N |  |
| 10 | ANSERM_CPROF | CHAR(2) | N |  |
| 11 | ANSERM_FONDI_PA | CHAR(1) | N |  |
| 12 | ANSERM_BENEF | CHAR(2) | N |  |
| 13 | ANSERM_CARICA1 | CHAR(2) | N |  |
| 14 | ANSERM_CARICA2 | CHAR(2) | N |  |
| 15 | ANSERM_CARICA3 | CHAR(2) | N |  |
| 16 | ANSERM_PAESE_RAP1 | CHAR(3) | N |  |
| 17 | ANSERM_PAESE_RAP2 | CHAR(3) | N |  |
| 18 | ANSERM_PAESE_RAP3 | CHAR(3) | N |  |
| 19 | ANSERM_RELAZIONI1 | CHAR(2) | N |  |
| 20 | ANSERM_RELAZIONI2 | CHAR(2) | N |  |
| 21 | ANSERM_RELAZIONI3 | CHAR(2) | N |  |
| 22 | ANSERM_NOTE_BENEF | CHAR(50) | N |  |
| 23 | ANSERM_CANALE | CHAR(5) | N |  |
| 24 | ANSERM_DACQUIS | DECIMAL(9,0) | N |  |
| 25 | ANSERM_DT_CONCIL | DECIMAL(9,0) | N |  |
| 26 | ANSERM_QRCODE | CHAR(100) | N |  |
| 27 | ANSERM_CPROF_NAG | CHAR(3) | N |  |

Indici:

- `IXCDANSERM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANSERSPI_CD

*Tabella* – righe: 8
– change data della tabella `ANSERSPI` (FJBM: TABELLA DATI ANSER SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANSERSPI_CODANA | CHAR(12) | N |  |
| 5 | ANSERSPI_SETTORE | CHAR(3) | N |  |
| 6 | ANSERSPI_RAMO | CHAR(3) | N |  |
| 7 | ANSERSPI_TAE | DECIMAL(3,0) | N |  |
| 8 | ANSERSPI_PROV | CHAR(2) | N |  |
| 9 | ANSERSPI_NAZIONE | CHAR(25) | N |  |
| 10 | ANSERSPI_CPROF | CHAR(2) | N |  |
| 11 | ANSERSPI_FONDI_PA | CHAR(1) | N |  |
| 12 | ANSERSPI_BENEF | CHAR(2) | N |  |
| 13 | ANSERSPI_CARICA1 | CHAR(2) | N |  |
| 14 | ANSERSPI_CARICA2 | CHAR(2) | N |  |
| 15 | ANSERSPI_CARICA3 | CHAR(2) | N |  |
| 16 | ANSERSPI_PAESE_RAP1 | CHAR(3) | N |  |
| 17 | ANSERSPI_PAESE_RAP2 | CHAR(3) | N |  |
| 18 | ANSERSPI_PAESE_RAP3 | CHAR(3) | N |  |
| 19 | ANSERSPI_RELAZIONI1 | CHAR(2) | N |  |
| 20 | ANSERSPI_RELAZIONI2 | CHAR(2) | N |  |
| 21 | ANSERSPI_RELAZIONI3 | CHAR(2) | N |  |

Indici:

- `ANSERSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANSER_CD

*Tabella* – righe: 36
– change data della tabella `ANSER` (FJBM: TABELLA DATI ANSER SPECCHIO)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANSER_CODANA | CHAR(12) | N |  |
| 5 | ANSER_SETTORE | CHAR(3) | N |  |
| 6 | ANSER_RAMO | CHAR(3) | N |  |
| 7 | ANSER_TAE | DECIMAL(3,0) | N |  |
| 8 | ANSER_PROV | CHAR(2) | N |  |
| 9 | ANSER_NAZIONE | CHAR(25) | N |  |
| 10 | ANSER_CPROF | CHAR(2) | N |  |
| 11 | ANSER_FONDI_PA | CHAR(1) | N |  |
| 12 | ANSER_BENEF | CHAR(2) | N |  |
| 13 | ANSER_CARICA1 | CHAR(2) | N |  |
| 14 | ANSER_CARICA2 | CHAR(2) | N |  |
| 15 | ANSER_CARICA3 | CHAR(2) | N |  |
| 16 | ANSER_PAESE_RAP1 | CHAR(3) | N |  |
| 17 | ANSER_PAESE_RAP2 | CHAR(3) | N |  |
| 18 | ANSER_PAESE_RAP3 | CHAR(3) | N |  |
| 19 | ANSER_RELAZIONI1 | CHAR(2) | N |  |
| 20 | ANSER_RELAZIONI2 | CHAR(2) | N |  |
| 21 | ANSER_RELAZIONI3 | CHAR(2) | N |  |

Indici:

- `ANSERD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ANTIT_CD

*Tabella* – righe: 0
– change data della tabella `ANTIT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ANTIT_AREAFIN | CHAR(11) | N |  |
| 5 | ANTIT_ISIN | CHAR(12) | N |  |
| 6 | ANTIT_MAF | CHAR(14) | N |  |
| 7 | ANTIT_CVM | CHAR(14) | N |  |
| 8 | ANTIT_TIPOTIT | CHAR(20) | N |  |
| 9 | ANTIT_DATACAR | DECIMAL(9,0) | N |  |
| 10 | ANTIT_DATAULT | DECIMAL(9,0) | N |  |
| 11 | ANTIT_DATAINIZ | DECIMAL(9,0) | N |  |
| 12 | ANTIT_DATAFINE | DECIMAL(9,0) | N |  |
| 13 | ANTIT_DESCR | CHAR(80) | N |  |
| 14 | ANTIT_SUBPROD | CHAR(5) | N |  |
| 15 | ANTIT_ASSOGEST | CHAR(3) | N |  |
| 16 | ANTIT_PIAZZA | CHAR(2) | N |  |
| 17 | ANTIT_MERCATO | CHAR(3) | N |  |
| 18 | ANTIT_FQUOT | CHAR(1) | N |  |
| 19 | ANTIT_DIVEMI | CHAR(3) | N |  |
| 20 | ANTIT_SOCGES | CHAR(80) | N |  |
| 21 | ANTIT_COMGES | DECIMAL(9,6) | N |  |
| 22 | ANTIT_COMSOTT | DECIMAL(9,5) | N |  |
| 23 | ANTIT_COMBKDEP | DECIMAL(9,5) | N |  |
| 24 | ANTIT_MERCBL | CHAR(6) | N |  |
| 25 | ANTIT_ULLA | CHAR(6) | N |  |
| 26 | ANTIT_MACROCAT | CHAR(5) | N |  |
| 27 | XANTIT_MAF | CHAR(14) |  | CHIAVE MAF OLD |
| 28 | XANTIT_DATAFINE | DECIMAL(9,0) |  | CHIAVE DATAFINE OLD |
| 29 | ANTIT_INDRIS | CHAR(1) | N | INDICATORE ISIN RISERVATO A LINEE KS |
| 30 | ANTIT_DATASOSP | DECIMAL(9,0) | N | DATA SOSPENSIONE ISIN |
| 31 | ANTIT_DATACHIU | DECIMAL(9,0) | N | DATA CHIUSURA ISIN |
| 32 | ANTIT_NAVPROT | CHAR(1) | N | FLAG SOTTOSTANTE PROTETTO |
| 33 | ANTIT_LINKASPD | CHAR(5) |  |  |
| 34 | ANTIT_SUBPROD2 | CHAR(5) |  |  |
| 35 | ANTIT_ORIZZTEMP | DECIMAL(5,2) | N |  |
| 36 | ANTIT_SRI | DECIMAL(5,2) | N |  |
| 37 | ANTIT_PRCPROT | DECIMAL(5,2) | N |  |

Indici:

- `ANTITD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APDEC_CD

*Tabella* – righe: 0
– change data della tabella `APDEC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APDEC_CAMPO | CHAR(20) | N |  |
| 5 | APDEC_VALORE | CHAR(10) | N |  |
| 6 | APDEC_DVALINI | DECIMAL(9,0) | N |  |
| 7 | APDEC_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | APDEC_DESCR | CHAR(80) | N |  |
| 9 | APDEC_DESCRID | CHAR(10) | N |  |

Indici:

- `APDECD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APFCON_CD

*Tabella* – righe: 0
– change data della tabella `APFCON`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APFCON_DATAFLUSSO | DECIMAL(9,0) | N |  |
| 5 | APFCON_CODPROD | CHAR(2) | N |  |
| 6 | XAPFCON_CODPROD | CHAR(2) |  |  |
| 7 | APFCON_LINEA | CHAR(5) | N |  |
| 8 | XAPFCON_LINEA | CHAR(5) |  |  |
| 9 | APFCON_SUBPROD_SOTTOSCRIVIBILE | CHAR(5) | N |  |
| 10 | XAPFCON_SUBPROD_SOTTOSCRIVIBIL | CHAR(5) |  |  |
| 11 | APFCON_MAF_SOTTOSCRIVIBILE | CHAR(14) | N |  |
| 12 | APFCON_ISIN_SOTTOSCRIVIBILE | CHAR(12) | N |  |
| 13 | APFCON_ISIN_CONFERIBILE | CHAR(12) | N |  |
| 14 | XAPFCON_ISIN_CONFERIBILE | CHAR(12) |  |  |
| 15 | APFCON_MAF_CONFERIBILE | CHAR(14) | N |  |
| 16 | XAPFCON_MAF_CONFERIBILE | CHAR(14) |  |  |
| 17 | APFCON_DESCR_CONFERIBILE | CHAR(100) | N |  |
| 18 | APFCON_IND_CONVERTIBILE | CHAR(1) | N |  |
| 19 | APFCON_DVALINI | DECIMAL(9,0) | N |  |
| 20 | APFCON_DVALFIN | DECIMAL(9,0) | N |  |
| 21 | XAPFCON_DVALFIN | DECIMAL(9,0) |  |  |

Indici:

- `APFCOND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APROD_CD

*Tabella* – righe: 0
– change data della tabella `APROD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APROD_CODPROD | CHAR(2) | N |  |
| 5 | APROD_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | APROD_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | APROD_DESCR | CHAR(30) | N |  |
| 8 | APROD_DESCRID | CHAR(10) | N |  |
| 9 | APROD_INDFPPA | CHAR(1) | N |  |
| 10 | APROD_INDMECC | CHAR(1) | N |  |
| 11 | APROD_DATASOTT | DECIMAL(9,0) | N |  |
| 12 | APROD_BKCORR | CHAR(2) | N |  |
| 13 | APROD_INDSSOT | CHAR(1) | N |  |
| 14 | APROD_INDSAMM | CHAR(1) | N |  |
| 15 | APROD_INDSLIQ | CHAR(1) | N |  |
| 16 | APROD_INDPAY | CHAR(1) | N |  |
| 17 | APROD_INDRGL | CHAR(1) | N |  |
| 18 | APROD_FAMAGP | CHAR(2) | N |  |
| 19 | APROD_DEFPROV | CHAR(1) | N |  |
| 20 | APROD_FAMPAG | CHAR(2) | N |  |
| 21 | APROD_FAMGF | CHAR(2) | N |  |
| 22 | APROD_INDRM | CHAR(1) | N |  |
| 23 | APROD_FAMAUI | CHAR(2) | N |  |
| 24 | APROD_SOCSRV | CHAR(2) | N |  |
| 25 | APROD_FAMVP | CHAR(3) | N |  |
| 26 | APROD_RAMO | CHAR(3) | N |  |
| 27 | APROD_RISCONTO | CHAR(2) | N |  |
| 28 | APROD_BANCACORR | CHAR(2) | N |  |
| 29 | APROD_TIPOPRD | CHAR(2) | N |  |
| 30 | APROD_INDCINV | CHAR(1) |  |  |
| 31 | APROD_PRCIVA | DECIMAL(7,2) |  |  |
| 32 | APROD_INDPROV | CHAR(1) |  |  |
| 33 | APROD_OPZREIN | CHAR(1) |  |  |
| 34 | APROD_OPZPAG | CHAR(1) |  |  |
| 35 | APROD_MODPAG | CHAR(1) |  |  |
| 36 | APROD_NATURA | CHAR(5) |  |  |
| 37 | APROD_FATNAV4 | CHAR(2) |  |  |
| 38 | APROD_FATNAV5 | CHAR(2) |  |  |

Indici:

- `APRODD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APRSPI_CD

*Tabella* – righe: 0
– change data della tabella `APRSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APRSPI_PROV | CHAR(2) | N |  |
| 5 | APRSPI_PROVINCIA | CHAR(20) | N |  |
| 6 | APRSPI_SCP | CHAR(2) | N |  |
| 7 | APRSPI_CAPOLUOGO | CHAR(1) | N |  |
| 8 | APRSPI_REGIONE | CHAR(30) | N |  |
| 9 | APRSPI_GAM | CHAR(2) | N |  |
| 10 | APRSPI_AREA | CHAR(3) | N |  |
| 11 | APRSPI_DVALINI | DECIMAL(9,0) | N |  |
| 12 | APRSPI_DVALFIN | DECIMAL(9,0) | N |  |

Indici:

- `APRSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APRVFN_CD

*Tabella* – righe: 0
– change data della tabella `APRVFN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APRVFN_CODFN | CHAR(16) | N |  |
| 5 | APRVFN_DESCR | CHAR(50) | N |  |
| 6 | APRVFN_LINKUP | CHAR(16) | N |  |
| 7 | APRVFN_TIPODETT | CHAR(1) | N |  |
| 8 | APRVFN_VOC | CHAR(3) | N |  |
| 9 | APRVFN_RETE | CHAR(1) | N |  |
| 10 | APRVFN_FATNAV4 | CHAR(2) | N |  |
| 11 | APRVFN_FATNAV5 | CHAR(2) | N |  |
| 12 | APRVFN_INDPROV | CHAR(1) | N |  |
| 13 | APRVFN_INDNAV | CHAR(1) | N |  |
| 14 | APRVFN_INDZERO | CHAR(1) | N |  |
| 15 | APRVFN_INDVEND | CHAR(1) | N |  |
| 16 | APRVFN_LIVELLO | DECIMAL(3,0) | N |  |
| 17 | APRVFN_INDLIV | CHAR(1) | N |  |

Indici:

- `APRVFND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APRVOC_CD

*Tabella* – righe: 0
– change data della tabella `APRVOC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APRVOC_VOC | CHAR(3) | N |  |
| 5 | APRVOC_DESCR | CHAR(80) | N |  |
| 6 | APRVOC_DVALINI | DECIMAL(9,0) | N |  |
| 7 | APRVOC_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | APRVOC_RETE | CHAR(1) | N |  |
| 9 | APRVOC_TIPOPB | CHAR(3) | N |  |
| 10 | APRVOC_VOC3 | CHAR(3) | N |  |
| 11 | APRVOC_INDACCNT | CHAR(2) | N |  |
| 12 | APRVOC_LEGAIVA | CHAR(3) | N |  |
| 13 | APRVOC_INDENAS | CHAR(2) | N |  |
| 14 | APRVOC_TIPO | CHAR(2) | N |  |
| 15 | APRVOC_INDRTA | CHAR(1) | N |  |
| 16 | APRVOC_INDMG | CHAR(2) | N |  |
| 17 | APRVOC_INDELAB | CHAR(2) | N |  |
| 18 | APRVOC_MACROVOCE | CHAR(2) | N |  |
| 19 | APRVOC_CONSOB | CHAR(2) | N |  |
| 20 | APRVOC_VOCECOR | CHAR(3) | N |  |
| 21 | APRVOC_LEGAIVA2 | CHAR(3) |  |  |

Indici:

- `APRVOCD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APRV_CD

*Tabella* – righe: 10
– change data della tabella `APRV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APRV_CODPROD | CHAR(2) | N |  |
| 5 | APRV_SUBPROD | CHAR(5) | N |  |
| 6 | APRV_RETE | CHAR(2) | N |  |
| 7 | APRV_TIPOPER | CHAR(2) | N |  |
| 8 | APRV_TIPOPES | CHAR(2) | N |  |
| 9 | APRV_DURMIN | DECIMAL(3,0) | N |  |
| 10 | APRV_DURMAX | DECIMAL(3,0) | N |  |
| 11 | APRV_CVNMIN | DECIMAL(15,2) | N |  |
| 12 | APRV_CVNMAX | DECIMAL(15,2) | N |  |
| 13 | APRV_CONTRTIPO | CHAR(2) | N |  |
| 14 | APRV_DVALINI | DECIMAL(9,0) | N |  |
| 15 | APRV_DVALFIN | DECIMAL(9,0) | N |  |
| 16 | APRV_TIPOCOMM | CHAR(1) | N |  |
| 17 | APRV_REGCOMM | CHAR(4) | N |  |
| 18 | APRV_DTINIPAG | DECIMAL(9,0) | N |  |
| 19 | APRV_FREQPROV | CHAR(1) | N |  |
| 20 | APRV_TIPAGE | CHAR(2) | N |  |
| 21 | APRV_TIPSTRU | CHAR(2) | N |  |
| 22 | APRV_REGOUT | CHAR(2) | N |  |
| 23 | APRV_NOSPLIT | CHAR(2) | N |  |
| 24 | APRV_REGSPLIT | CHAR(2) | N |  |
| 25 | APRV_REGVOL | CHAR(2) | N |  |
| 26 | APRV_DWH | CHAR(2) | N |  |
| 27 | APRV_VOCPB | CHAR(3) | N |  |
| 28 | APRV_VOCTFA | CHAR(3) | N |  |
| 29 | APRV_REGDIS | CHAR(4) | N |  |
| 30 | APRV_GRUPPO | CHAR(8) | N |  |
| 31 | APRV_TIPTAB | CHAR(2) | N |  |
| 32 | APRV_TABDIS | CHAR(2) | N |  |
| 33 | APRV_LAYOUT | CHAR(2) | N |  |
| 34 | APRV_ELAB | CHAR(2) | N |  |
| 35 | APRV_CLASSE | CHAR(2) | N |  |
| 36 | APRV_INDFND | CHAR(1) | N |  |
| 37 | APRV_LINEA | CHAR(5) |  |  |
| 38 | APRV_PERCORSO | CHAR(5) |  |  |
| 39 | APRV_MATURAZIONE | CHAR(1) |  |  |
| 40 | APRV_MESEFATT | CHAR(2) |  |  |
| 41 | APRV_INDBC | CHAR(2) |  |  |

Indici:

- `APRVD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_APR_CD

*Tabella* – righe: 0
– change data della tabella `APR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | APR_PROV | CHAR(2) | N |  |
| 5 | APR_PROVINCIA | CHAR(20) | N |  |
| 6 | APR_SCP | CHAR(2) | N |  |
| 7 | APR_CAPOLUOGO | CHAR(1) | N |  |
| 8 | APR_REGIONE | CHAR(30) | N |  |
| 9 | APR_GAM | CHAR(2) | N |  |
| 10 | APR_AREA | CHAR(3) | N |  |
| 11 | APR_DVALINI | DECIMAL(9,0) | N |  |
| 12 | APR_DVALFIN | DECIMAL(9,0) | N |  |

Indici:

- `APRD001` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ARIC_CD5

*Tabella* – righe: 0
– change data della tabella `ARIC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ARIC_CODCONF | CHAR(11) | N |  |
| 6 | XARIC_CODCONF | CHAR(11) |  |  |
| 7 | ARIC_CODPROD | CHAR(2) | N |  |
| 8 | XARIC_CODPROD | CHAR(2) |  |  |
| 9 | ARIC_CODANA | CHAR(12) | N |  |
| 10 | ARIC_PRGDOC | SMALLINT | N |  |
| 11 | ARIC_DATINC | CHAR(8) | N |  |
| 12 | XARIC_DATINC | CHAR(8) |  |  |
| 13 | ARIC_TIPORIM | CHAR(1) | N |  |
| 14 | XARIC_TIPORIM | CHAR(1) |  |  |
| 15 | ARIC_PROGRIM | CHAR(10) | N |  |
| 16 | ARIC_IMPORIM | DECIMAL(15,0) | N |  |
| 17 | XARIC_IMPORIM | DECIMAL(15,0) |  |  |
| 18 | ARIC_PROGMOV | SMALLINT | N |  |
| 19 | XARIC_PROGMOV | SMALLINT |  |  |
| 20 | ARIC_PROGINC | SMALLINT | N |  |
| 21 | XARIC_PROGINC | SMALLINT |  |  |
| 22 | ARIC_TIPOPER | CHAR(2) | N |  |
| 23 | ARIC_DVALFND | DECIMAL(9,0) | N |  |
| 24 | ARIC_DRICEZ | DECIMAL(9,0) | N |  |
| 25 | ARIC_NUMASS | CHAR(16) | N |  |
| 26 | ARIC_NUMBON | CHAR(20) | N |  |
| 27 | ARIC_DISINV | CHAR(11) | N |  |
| 28 | ARIC_CODDIST | CHAR(15) | N |  |
| 29 | ARIC_ABI | CHAR(5) | N |  |
| 30 | ARIC_CAB | CHAR(5) | N |  |
| 31 | ARIC_CONTO | CHAR(12) | N |  |
| 32 | ARIC_POSMAND | CHAR(2) | N |  |
| 33 | XARIC_POSMAND | CHAR(2) |  |  |
| 34 | ARIC_DTINRM | DECIMAL(9,0) | N |  |
| 35 | ARIC_TIPOPES | CHAR(2) | N |  |
| 36 | ARIC_CODDIV | CHAR(3) | N |  |
| 37 | ARIC_IMPOVER | DECIMAL(15,2) | N |  |
| 38 | XARIC_IMPOVER | DECIMAL(15,2) |  |  |
| 39 | ARIC_IMPEURO | DECIMAL(15,2) | N |  |
| 40 | XARIC_IMPEURO | DECIMAL(15,2) |  |  |
| 41 | ARIC_SCACONV | DECIMAL(6,5) | N |  |
| 42 | ARIC_DACQUIS | DECIMAL(9,0) | N |  |
| 43 | ARIC_DTBOLL | DECIMAL(9,0) | N |  |
| 44 | ARIC_RETE | CHAR(1) | N |  |

Indici:

- `ASN_ARIC_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASALST_CD

*Tabella* – righe: 67
– change data della tabella `ASALST`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ASALST_CODCONF | CHAR(11) | N |  |
| 5 | ASALST_CODPROD | CHAR(2) | N |  |
| 6 | ASALST_LINEA | CHAR(5) | N |  |
| 7 | ASALST_ISIN | CHAR(12) | N |  |
| 8 | ASALST_MERCATO | CHAR(3) | N |  |
| 9 | ASALST_CODULLA | CHAR(6) | N |  |
| 10 | ASALST_BLOCCO | CHAR(1) | N |  |
| 11 | ASALST_PRTACQS | DECIMAL(15,7) | N |  |
| 12 | ASALST_VALNAV | DECIMAL(15,7) | N |  |
| 13 | ASALST_NETINVS | DECIMAL(15,7) | N |  |
| 14 | ASALST_DATANAV | DECIMAL(9,0) | N |  |
| 15 | ASALST_DATAVAL | DECIMAL(9,0) | N |  |
| 16 | ASALST_CODDIV | CHAR(3) | N |  |
| 17 | ASALST_NAVDIV | DECIMAL(15,7) | N |  |
| 18 | ASALST_CAMBIO | DECIMAL(13,5) | N |  |
| 19 | ASALST_RETE | CHAR(1) | N |  |

Indici:

- `ASALSTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASCMM_CD

*Tabella* – righe: 0
– change data della tabella `ASCMM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ASCMM_CODCONF | CHAR(11) | N |  |
| 5 | ASCMM_CODPROD | CHAR(2) | N |  |
| 6 | ASCMM_PROGMOV | SMALLINT | N |  |
| 7 | ASCMM_PROVENIENZA | CHAR(10) | N |  |
| 8 | ASCMM_RETE | CHAR(1) | N |  |
| 9 | ASCMM_MOPAG | CHAR(1) | N |  |

Indici:

- `ASCMMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASGM_CD

*Tabella* – righe: 0
– change data della tabella `ASGM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ASGM_RETE | CHAR(1) | N |  |
| 5 | ASGM_CODAGE | CHAR(6) | N |  |
| 6 | ASGM_TIPORETE | CHAR(1) | N |  |
| 7 | ASGM_DVALINI | DECIMAL(9,0) | N |  |
| 8 | ASGM_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | ASGM_GRADO | CHAR(4) | N |  |
| 10 | ASGM_LIVVEN | CHAR(3) | N |  |

Indici:

- `IXCDASGM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASGSPI_CD

*Tabella* – righe: 2
– change data della tabella `ASGSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ASGSPI_CODAGE | CHAR(6) | N |  |
| 6 | ASGSPI_TIPORETE | CHAR(1) | N |  |
| 7 | ASGSPI_DVALINI | DECIMAL(9,0) | N |  |
| 8 | ASGSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | ASGSPI_GRADO | CHAR(4) | N |  |
| 10 | ASGSPI_LIVVEN | CHAR(3) | N |  |

Indici:

- `ASGSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASG_CD5

*Tabella* – righe: 0
– change data della tabella `ASG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XASG_CODAGE | CHAR(6) |  |  |
| 6 | ASG_CODAGE | CHAR(6) | N |  |
| 7 | ASG_TIPORETE | CHAR(1) | N |  |
| 8 | ASG_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | ASG_GRADO | CHAR(4) | N |  |
| 10 | ASG_LIVVEN | CHAR(3) | N |  |
| 11 | ASG_DVALINI | DECIMAL(9,0) | N |  |

Indici:

- `ASN_ASG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASPD_CD

*Tabella* – righe: 0
– change data della tabella `ASPD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ASPD_SUBPROD | CHAR(5) | N |  |
| 5 | ASPD_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | ASPD_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | ASPD_DESCR | CHAR(30) | N |  |
| 8 | ASPD_DESCRID | CHAR(10) | N |  |
| 9 | ASPD_CODFAM | CHAR(2) | N |  |
| 10 | ASPD_TIPOSPD | CHAR(1) | N |  |
| 11 | ASPD_CODFONDO | CHAR(2) | N |  |
| 12 | ASPD_SUBPROD2 | CHAR(2) | N |  |
| 13 | ASPD_CODDIV | CHAR(3) | N |  |
| 14 | ASPD_AREAFIN | CHAR(15) | N |  |
| 15 | ASPD_CODBKIT | CHAR(7) | N |  |
| 16 | ASPD_CODTIT | CHAR(4) | N |  |
| 17 | ASPD_GRUPINV | CHAR(2) | N |  |
| 18 | ASPD_ASSOGEST | CHAR(3) | N |  |
| 19 | ASPD_ISIN | CHAR(12) | N |  |
| 20 | ASPD_DIVINV | CHAR(3) | N |  |
| 21 | ASPD_COMGES | DECIMAL(7,3) | N |  |
| 22 | ASPD_CODEST | CHAR(65) | N |  |
| 23 | ASPD_PREMIO | CHAR(1) | N |  |
| 24 | ASPD_INDGDOE | CHAR(2) | N |  |
| 25 | ASPD_INDPROV | CHAR(1) | N |  |
| 26 | ASPD_DEFPROV | CHAR(1) | N |  |
| 27 | ASPD_INDFPPA | CHAR(1) | N |  |
| 28 | ASPD_INDLOAD | CHAR(1) | N |  |
| 29 | ASPD_EUROTAX | CHAR(2) | N |  |
| 30 | ASPD_CLASSE | CHAR(2) | N |  |
| 31 | ASPD_CODPREST | CHAR(1) | N |  |
| 32 | ASPD_SOCGES | CHAR(2) | N |  |
| 33 | ASPD_INDCOMP | CHAR(1) | N |  |
| 34 | ASPD_DESTCOD | CHAR(5) | N |  |
| 35 | ASPD_COMSUBD | DECIMAL(7,3) | N |  |
| 36 | ASPD_FRQPROV | CHAR(1) |  |  |
| 37 | ASPD_INDPRS | CHAR(1) |  |  |
| 38 | ASPD_INDPSS | CHAR(1) |  |  |
| 39 | ASPD_INDPRC | CHAR(1) |  |  |
| 40 | ASPD_INDFND | CHAR(1) |  |  |

Indici:

- `ASPD0001` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASSICURATI_CD

*Tabella* – righe: 179
– change data della tabella `ASSICURATI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ASSICURATI_CODCONF | CHAR(11) | N |  |
| 5 | ASSICURATI_CODPROD | CHAR(2) | N |  |
| 6 | ASSICURATI_POS_ASSICURATO | CHAR(2) | N |  |
| 7 | ASSICURATI_CONTRAENTE | CHAR(1) | N |  |
| 8 | ASSICURATI_RETE | CHAR(1) | N |  |
| 9 | ASSICURATI_COGNOME | CHAR(25) | N |  |
| 10 | ASSICURATI_NOME | CHAR(25) | N |  |
| 11 | ASSICURATI_DTNAS | DECIMAL(9,0) | N |  |
| 12 | ASSICURATI_SEX | CHAR(1) | N |  |
| 13 | ASSICURATI_CMNAS | CHAR(25) | N |  |
| 14 | ASSICURATI_PRVNAS | CHAR(2) | N |  |
| 15 | ASSICURATI_CDFIS | CHAR(16) | N |  |
| 16 | ASSICURATI_NAZNAS | CHAR(25) | N |  |
| 17 | ASSICURATI_CITTAD | CHAR(25) | N |  |
| 18 | ASSICURATI_INDRES | CHAR(44) | N |  |
| 19 | ASSICURATI_CAPRES | CHAR(5) | N |  |
| 20 | ASSICURATI_PRVRES | CHAR(2) | N |  |
| 21 | ASSICURATI_CMRES | CHAR(25) | N |  |
| 22 | ASSICURATI_NAZRES | CHAR(25) | N |  |
| 23 | ASSICURATI_TELEFONO | CHAR(12) | N |  |
| 24 | ASSICURATI_CELLULARE | CHAR(12) | N |  |
| 25 | ASSICURATI_MAIL | CHAR(30) | N |  |
| 26 | ASSICURATI_PRIVACY_SEN | CHAR(1) | N |  |
| 27 | ASSICURATI_PRIVACY_INT | CHAR(1) | N |  |
| 28 | ASSICURATI_PRIVACY_EST | CHAR(1) | N |  |
| 29 | ASSICURATI_FUMATORE | CHAR(1) | N |  |
| 30 | ASSICURATI_PROFESSIONE | CHAR(4) | N |  |
| 31 | ASSICURATI_PREMIO_LORDO_ANNUO | DECIMAL(13,2) | N |  |
| 32 | ASSICURATI_PREMIO_NETTO_ANNUO | DECIMAL(13,2) | N |  |
| 33 | ASSICURATI_IMP_PREMIO_ANNUO | DECIMAL(13,2) | N |  |
| 34 | ASSICURATI_IMP_PREST_LORDO | DECIMAL(13,2) | N |  |
| 35 | ASSICURATI_IMP_PREST_NETTO | DECIMAL(13,2) | N |  |
| 36 | ASSICURATI_IMPOSTE_PRESTAZ | DECIMAL(13,2) | N |  |
| 37 | ASSICURATI_PREMIO_LORDO_MENS | DECIMAL(13,2) | N |  |
| 38 | ASSICURATI_PREMIO_NETTO_MENS | DECIMAL(13,2) | N |  |
| 39 | ASSICURATI_IMPOSTE_MENSILI | DECIMAL(13,2) | N |  |

Indici:

- `ASSICURATID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ASS_CD5

*Tabella* – righe: 0
– change data della tabella `ASS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ASS_CODCONF | CHAR(11) | N |  |
| 6 | ASS_CODPROD | CHAR(2) | N |  |
| 7 | ASS_TIPOPER | CHAR(2) | N |  |
| 8 | ASS_ABI | CHAR(5) | N |  |
| 9 | ASS_CAB | CHAR(5) | N |  |
| 10 | ASS_INTEST1 | CHAR(40) | N |  |
| 11 | ASS_NUM | CHAR(16) | N |  |
| 12 | ASS_IMP | DECIMAL(13,0) | N |  |
| 13 | ASS_PROGPAG | SMALLINT | N |  |
| 14 | ASS_SUBPROD | CHAR(5) | N |  |
| 15 | ASS_DACQUIS | DECIMAL(9,0) | N |  |
| 16 | ASS_INDIR | CHAR(60) | N |  |
| 17 | ASS_CAP | CHAR(5) | N |  |
| 18 | ASS_CITTA | CHAR(23) | N |  |
| 19 | ASS_PROV | CHAR(2) | N |  |
| 20 | ASS_IMPOPAG | DECIMAL(15,2) | N |  |
| 21 | ASS_IMPEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_ASS_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ATERMSPI_CD

*Tabella* – righe: 0
– change data della tabella `ATERMSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ATERMSPI_CODAGE | CHAR(6) | N |  |
| 5 | ATERMSPI_CAUSALE | CHAR(3) | N |  |
| 6 | ATERMSPI_NOTE | CHAR(70) | N |  |
| 7 | ATERMSPI_MOTIVTERM | CHAR(1) | N |  |
| 8 | ATERMSPI_MOTIVPRES | CHAR(30) | N |  |
| 9 | ATERMSPI_CONCOR | CHAR(30) | N |  |
| 10 | ATERMSPI_CAUBDG99 | CHAR(5) | N |  |
| 11 | ATERMSPI_NOTBDG99 | CHAR(70) | N |  |
| 12 | ATERMSPI_CAURAPCC | CHAR(3) | N |  |
| 13 | ATERMSPI_NOTRAPCC | CHAR(70) | N |  |
| 14 | ATERMSPI_RFA | DECIMAL(13,0) | N |  |
| 15 | ATERMSPI_RFA_E | DECIMAL(15,2) | N |  |
| 16 | ATERMSPI_DESCR_C | CHAR(50) | N |  |
| 17 | ATERMSPI_CODICE | CHAR(5) | N |  |
| 18 | ATERMSPI_RFA_SIM | DECIMAL(15,2) | N |  |
| 19 | ATERMSPI_DATA_SIM | DECIMAL(9,0) | N |  |
| 20 | ATERMSPI_TIPOTERM | CHAR(1) | N |  |

Indici:

- `ATERMSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ATERM_CD

*Tabella* – righe: 2
– change data della tabella `ATERM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | ATERM_CODAGE | CHAR(6) | N |  |
| 5 | ATERM_CAUSALE | CHAR(3) | N |  |
| 6 | ATERM_NOTE | CHAR(70) | N |  |
| 7 | ATERM_MOTIVTERM | CHAR(1) | N |  |
| 8 | ATERM_MOTIVPRES | CHAR(30) | N |  |
| 9 | ATERM_CONCORRENZA | CHAR(30) | N |  |
| 10 | ATERM_CAUBDG99 | CHAR(5) | N |  |
| 11 | ATERM_NOTBDG99 | CHAR(70) | N |  |
| 12 | ATERM_CAURAPCC | CHAR(3) | N |  |
| 13 | ATERM_NOTRAPCC | CHAR(70) | N |  |
| 14 | ATERM_RFA | DECIMAL(13,0) | N |  |
| 15 | ATERM_RFA_E | DECIMAL(15,2) | N |  |
| 16 | ATERM_DESCR_CONC | CHAR(50) | N |  |
| 17 | ATERM_CODICE | CHAR(5) | N |  |
| 18 | ATERM_RFA_SIM | DECIMAL(15,2) | N |  |
| 19 | ATERM_DATA_SIM | DECIMAL(9,0) | N |  |
| 20 | ATERM_TIPOTERM | CHAR(1) | N |  |

Indici:

- `ATERMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BANAM_CD

*Tabella* – righe: 1.719
– change data della tabella `BANAM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | BANAM_RETE | CHAR(1) | N |  |
| 5 | BANAM_CONTO | CHAR(12) | N |  |
| 6 | BANAM_DOSSIER | CHAR(15) | N |  |
| 7 | BANAM_NDG | CHAR(9) | N |  |
| 8 | BANAM_CODFISC | CHAR(16) | N |  |
| 9 | BANAM_INT1 | CHAR(64) | N |  |
| 10 | BANAM_RUB1 | CHAR(3) | N |  |
| 11 | BANAM_NDG1 | DECIMAL(9,0) | N |  |
| 12 | BANAM_CODFISC1 | CHAR(16) | N |  |
| 13 | BANAM_INTEST1 | CHAR(32) | N |  |
| 14 | BANAM_RUB2 | CHAR(3) | N |  |
| 15 | BANAM_NDG2 | DECIMAL(9,0) | N |  |
| 16 | BANAM_CODFISC2 | CHAR(16) | N |  |
| 17 | BANAM_INTEST2 | CHAR(32) | N |  |
| 18 | BANAM_RUB3 | CHAR(3) | N |  |
| 19 | BANAM_NDG3 | DECIMAL(9,0) | N |  |
| 20 | BANAM_CODFISC3 | CHAR(16) | N |  |
| 21 | BANAM_INTEST3 | CHAR(32) | N |  |
| 22 | BANAM_ABILITOL | CHAR(1) | N |  |
| 23 | BANAM_RUB4 | CHAR(3) | N |  |
| 24 | BANAM_NDG4 | DECIMAL(9,0) | N |  |
| 25 | BANAM_CODFISC4 | CHAR(16) | N |  |
| 26 | BANAM_INTEST4 | CHAR(32) | N |  |
| 27 | BANAM_RUB5 | CHAR(3) | N |  |
| 28 | BANAM_NDG5 | DECIMAL(9,0) | N |  |
| 29 | BANAM_CODFISC5 | CHAR(16) | N |  |
| 30 | BANAM_INTEST5 | CHAR(32) | N |  |
| 31 | BANAM_RUB6 | CHAR(3) | N |  |
| 32 | BANAM_NDG6 | DECIMAL(9,0) | N |  |
| 33 | BANAM_CODFISC6 | CHAR(16) | N |  |
| 34 | BANAM_INTEST6 | CHAR(32) | N |  |
| 35 | BANAM_RUB7 | CHAR(3) | N |  |
| 36 | BANAM_NDG7 | DECIMAL(9,0) | N |  |
| 37 | BANAM_CODFISC7 | CHAR(16) | N |  |
| 38 | BANAM_INTEST7 | CHAR(32) | N |  |
| 39 | BANAM_RUB8 | CHAR(3) | N |  |
| 40 | BANAM_NDG8 | DECIMAL(9,0) | N |  |
| 41 | BANAM_CODFISC8 | CHAR(16) | N |  |
| 42 | BANAM_INTEST8 | CHAR(32) | N |  |

Indici:

- `BANAMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BANASPI_CD

*Tabella* – righe: 315
– change data della tabella `BANASPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XBANASPI_CONTO | CHAR(12) |  |  |
| 6 | BANASPI_CONTO | CHAR(12) | N |  |
| 7 | BANASPI_DOSSIER | CHAR(15) | N |  |
| 8 | XBANASPI_DOSSIER | CHAR(15) |  |  |
| 9 | BANASPI_NDG | CHAR(9) | N |  |
| 10 | BANASPI_CODFISC | CHAR(16) | N |  |
| 11 | BANASPI_INT1 | CHAR(64) | N |  |
| 12 | BANASPI_RUB1 | CHAR(3) | N |  |
| 13 | BANASPI_NDG1 | DECIMAL(9,0) | N |  |
| 14 | BANASPI_CODFISC1 | CHAR(16) | N |  |
| 15 | BANASPI_INTEST1 | CHAR(32) | N |  |
| 16 | BANASPI_RUB2 | CHAR(3) | N |  |
| 17 | BANASPI_NDG2 | DECIMAL(9,0) | N |  |
| 18 | BANASPI_CODFISC2 | CHAR(16) | N |  |
| 19 | BANASPI_INTEST2 | CHAR(32) | N |  |
| 20 | BANASPI_RUB3 | CHAR(3) | N |  |
| 21 | BANASPI_NDG3 | DECIMAL(9,0) | N |  |
| 22 | BANASPI_CODFISC3 | CHAR(16) | N |  |
| 23 | BANASPI_INTEST3 | CHAR(32) | N |  |
| 24 | BANASPI_ABILITOL | CHAR(1) | N |  |
| 25 | BANASPI_RUB4 | CHAR(3) | N |  |
| 26 | BANASPI_NDG4 | DECIMAL(9,0) | N |  |
| 27 | BANASPI_CODFISC4 | CHAR(16) | N |  |
| 28 | BANASPI_INTEST4 | CHAR(32) | N |  |
| 29 | BANASPI_RUB5 | CHAR(3) | N |  |
| 30 | BANASPI_NDG5 | DECIMAL(9,0) | N |  |
| 31 | BANASPI_CODFISC5 | CHAR(16) | N |  |
| 32 | BANASPI_INTEST5 | CHAR(32) | N |  |
| 33 | BANASPI_RUB6 | CHAR(3) | N |  |
| 34 | BANASPI_NDG6 | DECIMAL(9,0) | N |  |
| 35 | BANASPI_CODFISC6 | CHAR(16) | N |  |
| 36 | BANASPI_INTEST6 | CHAR(32) | N |  |
| 37 | BANASPI_RUB7 | CHAR(3) | N |  |
| 38 | BANASPI_NDG7 | DECIMAL(9,0) | N |  |
| 39 | BANASPI_CODFISC7 | CHAR(16) | N |  |
| 40 | BANASPI_INTEST7 | CHAR(32) | N |  |
| 41 | BANASPI_RUB8 | CHAR(3) | N |  |
| 42 | BANASPI_NDG8 | DECIMAL(9,0) | N |  |
| 43 | BANASPI_CODFISC8 | CHAR(16) | N |  |
| 44 | BANASPI_INTEST8 | CHAR(32) | N |  |

Indici:

- `BANASPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BANA_CD5

*Tabella* – righe: 0
– change data della tabella `BANA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XBANA_CONTO | CHAR(12) |  |  |
| 6 | XBANA_DOSSIER | CHAR(15) |  |  |
| 7 | BANA_CONTO | CHAR(12) | N |  |
| 8 | BANA_DOSSIER | CHAR(15) | N |  |
| 9 | BANA_INT1 | CHAR(64) | N |  |
| 10 | BANA_RUB1 | CHAR(3) | N |  |
| 11 | BANA_INTEST1 | CHAR(32) | N |  |
| 12 | BANA_RUB2 | CHAR(3) | N |  |
| 13 | BANA_INTEST2 | CHAR(32) | N |  |
| 14 | BANA_RUB3 | CHAR(3) | N |  |
| 15 | BANA_INTEST3 | CHAR(32) | N |  |
| 16 | BANA_CODFISC | CHAR(16) | N |  |
| 17 | BANA_CODFISC1 | CHAR(16) | N |  |
| 18 | BANA_CODFISC2 | CHAR(16) | N |  |
| 19 | BANA_CODFISC3 | CHAR(16) | N |  |
| 20 | BANA_RUB4 | CHAR(3) | N |  |
| 21 | BANA_NDG4 | DECIMAL(9,0) | N |  |
| 22 | BANA_CODFISC4 | CHAR(16) | N |  |
| 23 | BANA_INTEST4 | CHAR(32) | N |  |

Indici:

- `ASN_BANA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BCC_CD5

*Tabella* – righe: 0
– change data della tabella `BCC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | BCC_CODCONF | CHAR(11) | N |  |
| 6 | BCC_CODPROD | CHAR(2) | N |  |
| 7 | BCC_TIPOPER | CHAR(2) | N |  |
| 8 | BCC_DELABOR | DECIMAL(9,0) | N |  |
| 9 | BCC_ABI | CHAR(5) | N |  |
| 10 | BCC_CAB | CHAR(5) | N |  |
| 11 | BCC_CONTO | CHAR(12) | N |  |
| 12 | BCC_INTEST | CHAR(30) | N |  |
| 13 | BCC_IMP | DECIMAL(13,0) | N |  |
| 14 | BCC_PROGPAG | SMALLINT | N |  |
| 15 | BCC_SUBPROD | CHAR(5) | N |  |
| 16 | BCC_DACQUIS | DECIMAL(9,0) | N |  |
| 17 | BCC_IMPOPAG | DECIMAL(15,2) | N |  |
| 18 | BCC_IMPEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_BCC_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BENEF_CD

*Tabella* – righe: 0
– change data della tabella `BENEF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | BENEF_NUMPOL | CHAR(11) | N |  |
| 6 | BENEF_CODCONF | CHAR(11) | N |  |
| 7 | BENEF_TIPBEN | CHAR(1) | N |  |
| 8 | BENEF_CDFIS1 | CHAR(16) | N |  |
| 9 | BENEF_PERCCAP1 | DECIMAL(5,2) | N |  |
| 10 | BENEF_COGNNOME1 | CHAR(35) | N |  |
| 11 | BENEF_CDFIS2 | CHAR(16) | N |  |
| 12 | BENEF_PERCCAP2 | DECIMAL(5,2) | N |  |
| 13 | BENEF_COGNNOME2 | CHAR(35) | N |  |
| 14 | BENEF_CDFIS3 | CHAR(16) | N |  |
| 15 | BENEF_PERCCAP3 | DECIMAL(5,2) | N |  |
| 16 | BENEF_COGNNOME3 | CHAR(35) | N |  |
| 17 | XBENEF_NUMPOL | CHAR(11) |  |  |
| 18 | XBENEF_CODCONF | CHAR(11) |  |  |
| 19 | XBENEF_TIPBEN | CHAR(1) |  |  |

Indici:

- `BENEFD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_BPRO_CD5

*Tabella* – righe: 0
– change data della tabella `BPRO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | BPRO_CODCONF | CHAR(11) | N |  |
| 6 | BPRO_CODCAU | CHAR(2) | N |  |
| 7 | BPRO_PROGBLC | SMALLINT | N |  |

Indici:

- `ASN_BPRO_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFA_CD5

*Tabella* – righe: 0
– change data della tabella `CCFA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFA_CODCONF | CHAR(11) | N |  |
| 6 | CFA_CODPROD | CHAR(2) | N |  |
| 7 | CFA_SUBPROD | CHAR(5) | N |  |
| 8 | CFA_BLOCCO | CHAR(1) | N |  |
| 9 | CFA_IDADCON | CHAR(1) | N |  |
| 10 | CFA_INDBENV | CHAR(1) | N |  |
| 11 | CFA_INDBENM | CHAR(1) | N |  |
| 12 | CFA_RATATIP | CHAR(1) | N |  |
| 13 | CFA_RATAIMP | DECIMAL(13,0) | N |  |
| 14 | CFA_VALASSC | DECIMAL(13,0) | N |  |
| 15 | CFA_MOLTVAL | DECIMAL(1,0) | N |  |
| 16 | CFA_IMPRICV | DECIMAL(13,0) | N |  |
| 17 | CFA_IMPACCS | DECIMAL(13,0) | N |  |
| 18 | CFA_NPREMPG | SMALLINT | N |  |
| 19 | CFA_IPREMPG | DECIMAL(13,0) | N |  |
| 20 | CFA_DECPOL | DECIMAL(9,0) | N |  |
| 21 | CFA_RATAIMPEURO | DECIMAL(15,2) | N |  |
| 22 | CFA_VALASSCEURO | DECIMAL(15,2) | N |  |
| 23 | CFA_IMPRICVEURO | DECIMAL(15,2) | N |  |
| 24 | CFA_IMPCACCSEURO | DECIMAL(15,2) | N |  |
| 25 | CFA_EIPREMPG | DECIMAL(15,2) | N |  |
| 26 | CFA_RETE | CHAR(1) | N |  |
| 27 | CFA_PERCCAR | DECIMAL(7,5) | N |  |
| 28 | CFA_IMPCAR | DECIMAL(11,2) | N |  |
| 29 | CFA_PREMIO_NETTO | DECIMAL(11,2) | N |  |
| 30 | CFA_RISMAT | DECIMAL(11,2) | N |  |
| 31 | CFA_PAF | CHAR(1) | N |  |
| 32 | CFA_NUMPOL | CHAR(11) | N |  |
| 33 | CFA_DSCADENZA | DECIMAL(9,0) | N |  |
| 34 | CFA_DEMISSIONE | DECIMAL(9,0) | N |  |
| 35 | CFA_TASSO_RIV | DECIMAL(5,2) | N |  |
| 36 | CFA_CAP_RIV | DECIMAL(11,2) | N |  |
| 37 | CFA_DATA_RIV | DECIMAL(9,0) | N |  |
| 38 | CFA_DURANNI | SMALLINT | N |  |
| 39 | CFA_RATAFRZ | SMALLINT | N |  |
| 40 | CFA_EPRANTOT | DECIMAL(15,2) | N |  |
| 41 | CFA_DURVRSI | SMALLINT |  |  |
| 42 | CFA_RATERIC | SMALLINT |  |  |
| 43 | CFA_QUIETAN | SMALLINT |  |  |
| 44 | CFA_PAGABIL | DECIMAL(13,0) |  |  |
| 45 | CFA_ERRORE | DECIMAL(13,0) |  |  |
| 46 | CFA_LASTMOV | SMALLINT |  |  |
| 47 | CFA_PRVACQPA | DECIMAL(13,0) |  |  |
| 48 | CFA_PRVACQSA | DECIMAL(13,0) |  |  |
| 49 | CFA_PRVACQSS | DECIMAL(13,0) |  |  |
| 50 | CFA_PRVINCAS | DECIMAL(13,0) |  |  |
| 51 | CFA_IGARCOMP | CHAR(1) |  |  |
| 52 | CFA_PRANTOT | DECIMAL(13,0) |  |  |
| 53 | CFA_LASTVAL | DECIMAL(9,0) |  |  |
| 54 | CFA_COPPROV | CHAR(2) |  |  |
| 55 | CFA_DPERFEZ | DECIMAL(9,0) |  |  |
| 56 | CFA_IPROVV | CHAR(1) |  |  |
| 57 | CFA_INDSTD | CHAR(1) |  |  |
| 58 | CFA_INDDEC | CHAR(1) |  |  |
| 59 | CFA_IPRENO | DECIMAL(15,3) |  |  |
| 60 | CFA_NPREMPG_N | SMALLINT |  |  |
| 61 | CFA_CODDIV | CHAR(3) |  |  |
| 62 | CFA_DTCONEURO | DECIMAL(9,0) |  |  |
| 63 | CFA_EPAGABIL | DECIMAL(15,2) |  |  |
| 64 | CFA_EERRORE | DECIMAL(15,2) |  |  |
| 65 | CFA_EPRVACQPA | DECIMAL(15,2) |  |  |
| 66 | CFA_EPRVACQSA | DECIMAL(15,2) |  |  |
| 67 | CFA_EPRVACQSS | DECIMAL(15,2) |  |  |
| 68 | CFA_EPRVINCAS | DECIMAL(15,2) |  |  |
| 69 | CFA_EIPRENO | DECIMAL(15,2) |  |  |
| 70 | CFA_DTEFFRIS | DECIMAL(9,0) |  |  |
| 71 | CFA_COD_LIV2 | CHAR(5) |  |  |
| 72 | CFA_COD_LIV3 | CHAR(5) |  |  |

Indici:

- `ASN_CCFA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFC_CD5

*Tabella* – righe: 0
– change data della tabella `CCFC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFC_CODCONF | CHAR(11) | N |  |
| 6 | CFC_CODPROD | CHAR(2) | N |  |
| 7 | CFC_SUBPROD | CHAR(5) | N |  |
| 8 | CFC_PERCCMP | SMALLINT | N |  |
| 9 | CFC_PRIPROD | CHAR(1) | N |  |
| 10 | CFC_PRC_SUBPROD | DECIMAL(7,3) |  |  |

Indici:

- `ASN_CCFC_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFL_CD5

*Tabella* – righe: 0
– change data della tabella `CCFL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFL_CODCONF | CHAR(11) | N |  |
| 6 | CFL_CODPROD | CHAR(2) | N |  |
| 7 | CFL_SUBPROD | CHAR(5) | N |  |
| 8 | CFL_BLOCCO | CHAR(1) | N |  |
| 9 | CFL_IMPRICV | DECIMAL(13,0) | N |  |
| 10 | CFL_IMPRIFS | DECIMAL(13,0) | N |  |
| 11 | CFL_LIQUID | DECIMAL(13,0) | N |  |
| 12 | CFL_SPSSOTT | DECIMAL(13,0) | N |  |
| 13 | CFL_SPSSERV | DECIMAL(13,0) | N |  |
| 14 | CFL_SPSAMMI | DECIMAL(13,0) | N |  |
| 15 | CFL_PRTACQS | DECIMAL(13,3) | N |  |
| 16 | CFL_PRTACQT | DECIMAL(13,3) | N |  |
| 17 | CFL_PRTRIFS | DECIMAL(13,3) | N |  |
| 18 | CFL_PRTLIQD | DECIMAL(13,3) | N |  |
| 19 | CFL_PRTCEDT | DECIMAL(13,3) | N |  |
| 20 | CFL_PRTCRTF | DECIMAL(13,3) | N |  |
| 21 | CFL_PRTVINC | DECIMAL(13,3) | N |  |
| 22 | CFL_INVEST | DECIMAL(13,0) | N |  |
| 23 | CFL_ISPSLIQ | DECIMAL(13,0) | N |  |
| 24 | CFL_RETE | CHAR(1) | N |  |
| 25 | CFL_FLUTTUA | DECIMAL(13,0) | N | FLUTTUAZIONE |
| 26 | CFL_LASTMOV | SMALLINT | N | ULTIMO NUMERO MOVIMENTO |
| 27 | CFL_IMPRICVEURO | DECIMAL(15,2) | N | IMPORTO IN FORMATO EURO |
| 28 | CFL_CODDIV | CHAR(3) | N | CODICE DIVISA (LIT-EUR) |
| 29 | CFL_DTCONEURO | DECIMAL(9,0) | N | DATA CONVERSIONE EUROçLIRE |
| 30 | CFL_ELIQUID | DECIMAL(13,2) | N | IMPORTO LIQUIDATO IN EURO |
| 31 | CFL_IMPRIFSEU | DECIMAL(13,2) | N | IMPORTO RIFUSO EURO |
| 32 | CFL_SPSSOTEU | DECIMAL(13,2) | N | SPESE SOTTOSCRIZIONE EURO |
| 33 | CFL_SPSSEREU | DECIMAL(13,2) | N | SPESE SERVIZIO EURO |
| 34 | CFL_SPSAMEU | DECIMAL(13,2) | N | SPESE AMMINISTRATIVE EURO |
| 35 | CFL_FLUTTEU | DECIMAL(13,2) | N | FLUTTUAZIONE EURO |
| 36 | CFL_INVESTEU | DECIMAL(13,2) | N | IMPORTO INVESTITO EURO |
| 37 | CFL_ISPSLIQEU | DECIMAL(13,2) | N | SPESE LIQUIDAZIONE EURO |
| 38 | CFL_CTRVIMPLIQ | DECIMAL(15,2) | N | CONTROVALORE SALDO LIQ. |
| 39 | CFL_PREZZO | DECIMAL(15,3) | N | PREZZO DEL SALDO |
| 40 | CFL_DATANAV | DECIMAL(9,0) | N | DATA NAV |

Indici:

- `ASN_CCFL_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFM_CD5

*Tabella* – righe: 0
– change data della tabella `CCFM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFM_CODCONF | CHAR(11) | N |  |
| 6 | CFM_CODPROD | CHAR(2) | N |  |
| 7 | CFM_BLOCCO | CHAR(1) | N |  |
| 8 | CFM_DSOTTOS | DECIMAL(9,0) | N |  |
| 9 | CFM_ERRORE | DECIMAL(13,0) | N |  |
| 10 | CFM_CODSPSE | CHAR(1) | N |  |
| 11 | CFM_EERRORE | DECIMAL(15,2) | N |  |
| 12 | CFM_RETE | CHAR(1) | N |  |
| 13 | CFM_NUMMODL | CHAR(11) |  |  |
| 14 | CFM_DPRELAB | DECIMAL(9,0) |  |  |
| 15 | CFM_IMPRICV | DECIMAL(13,0) |  |  |
| 16 | CFM_PAGABIL | DECIMAL(13,0) |  |  |
| 17 | CFM_ECCEDEN | DECIMAL(13,0) |  |  |
| 18 | CFM_LASTMOV | SMALLINT |  |  |
| 19 | CFM_LASTMOD | SMALLINT |  |  |
| 20 | CFM_IDFIRMC | CHAR(1) |  |  |
| 21 | CFM_TIPVEND | CHAR(1) |  |  |
| 22 | CFM_LASTVAR | SMALLINT |  |  |
| 23 | CFM_IMPRICEURO | DECIMAL(15,2) |  |  |
| 24 | CFM_CODDIV | CHAR(3) |  |  |
| 25 | CFM_DTCONEURO | DECIMAL(9,0) |  |  |
| 26 | CFM_CODAZIENDA | CHAR(5) |  |  |
| 27 | CFM_EPAGABIL | DECIMAL(15,2) |  |  |
| 28 | CFM_EECCEDEN | DECIMAL(15,2) |  |  |
| 29 | CFM_SOSPENSIVA | CHAR(1) |  |  |
| 30 | CFM_ID | DECIMAL(15,0) |  |  |
| 31 | CFM_CVN_CONT | DECIMAL(15,2) |  |  |
| 32 | CFM_NATURA | CHAR(5) |  |  |
| 33 | CFM_SCOPO | SMALLINT |  |  |
| 34 | CFM_STATOROL | CHAR(1) | N |  |
| 35 | CFM_TIPO_CONSUL | CHAR(4) |  |  |
| 36 | CFM_CODCONF_VP | CHAR(11) | N |  |
| 37 | CFM_DADDENDUM | DECIMAL(9,0) |  |  |

Indici:

- `ASN_CCFM_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFP_CD5

*Tabella* – righe: 0
– change data della tabella `CCFP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFP_CODCONF | CHAR(11) | N |  |
| 6 | CFP_CODPROD | CHAR(2) | N |  |
| 7 | CFP_SUBPROD | CHAR(5) | N |  |
| 8 | CFP_BLOCCO | CHAR(1) | N |  |
| 9 | CFP_DURVRSI | SMALLINT | N |  |
| 10 | CFP_RATAIMP | DECIMAL(13,0) | N |  |
| 11 | CFP_INDDIVI | CHAR(1) | N |  |
| 12 | CFP_VALNOMN | DECIMAL(13,0) | N |  |
| 13 | CFP_RATERIC | SMALLINT | N |  |
| 14 | CFP_RATERIF | SMALLINT | N |  |
| 15 | CFP_IMPRICV | DECIMAL(13,0) | N |  |
| 16 | CFP_IMPRICL | DECIMAL(13,0) | N |  |
| 17 | CFP_IMPRIFS | DECIMAL(13,0) | N |  |
| 18 | CFP_IMPLIQD | DECIMAL(13,0) | N |  |
| 19 | CFP_SPSSOTT | DECIMAL(13,0) | N |  |
| 20 | CFP_SPSAMMI | DECIMAL(13,0) | N |  |
| 21 | CFP_SPSTASS | DECIMAL(13,0) | N |  |
| 22 | CFP_SPSAMPL | DECIMAL(13,0) | N |  |
| 23 | CFP_PRTACQS | DECIMAL(13,3) | N |  |
| 24 | CFP_PRTACQL | DECIMAL(13,3) | N |  |
| 25 | CFP_PRTACQT | DECIMAL(13,3) | N |  |
| 26 | CFP_PRTRIFS | DECIMAL(13,3) | N |  |
| 27 | CFP_PRTLIQD | DECIMAL(13,3) | N |  |
| 28 | CFP_PRTCRTF | DECIMAL(13,3) | N |  |
| 29 | CFP_ILIQASS | DECIMAL(13,0) | N |  |
| 30 | CFP_PRTCEDT | DECIMAL(13,3) | N |  |
| 31 | CFP_ISPSLIQ | DECIMAL(13,0) | N |  |
| 32 | CFP_IMPRICEURO | DECIMAL(15,5) | N |  |
| 33 | CFP_VALNOMNEURO | DECIMAL(15,2) | N |  |
| 34 | CFP_RATAIMPEURO | DECIMAL(15,2) | N |  |
| 35 | CFP_RETE | CHAR(1) | N |  |
| 36 | CFP_PRTVINC | DECIMAL(13,3) | N |  |
| 37 | CFP_RATATIP | CHAR(1) |  |  |
| 38 | CFP_NUMURIT | SMALLINT |  |  |
| 39 | CFP_PAGABIL | DECIMAL(13,0) |  |  |
| 40 | CFP_ERRORE | DECIMAL(13,0) |  |  |
| 41 | CFP_FLUTTUA | DECIMAL(13,0) |  |  |
| 42 | CFP_NETINVS | DECIMAL(13,0) |  |  |
| 43 | CFP_LASTMOV | SMALLINT |  |  |
| 44 | CFP_NUMRSPS | SMALLINT |  |  |
| 45 | CFP_NUMRSPST | SMALLINT |  |  |
| 46 | CFP_DSCAPAG | DECIMAL(9,0) |  |  |
| 47 | CFP_PERCLIQ | DECIMAL(3,0) |  |  |
| 48 | CFP_CODDIV | CHAR(3) |  |  |
| 49 | CFP_DTCONEURO | DECIMAL(9,0) |  |  |
| 50 | CFP_IMPRICLEU | DECIMAL(13,2) |  |  |
| 51 | CFP_IMPRIFSEU | DECIMAL(13,2) |  |  |
| 52 | CFP_IMPLIQDEU | DECIMAL(13,2) |  |  |
| 53 | CFP_SPSSOTEU | DECIMAL(13,2) |  |  |
| 54 | CFP_SPSAMEU | DECIMAL(13,2) |  |  |
| 55 | CFP_SPSTAEU | DECIMAL(13,2) |  |  |
| 56 | CFP_SPSAMPLEU | DECIMAL(13,2) |  |  |
| 57 | CFP_PAGABILEU | DECIMAL(13,2) |  |  |
| 58 | CFP_ERROREU | DECIMAL(13,2) |  |  |
| 59 | CFP_FLUTTEU | DECIMAL(13,2) |  |  |
| 60 | CFP_NETINEU | DECIMAL(13,2) |  |  |
| 61 | CFP_ILIQASEU | DECIMAL(13,2) |  |  |
| 62 | CFP_ISPSLIQEU | DECIMAL(13,2) |  |  |

Indici:

- `ASN_CCFP_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFUL_CD5

*Tabella* – righe: 0
– change data della tabella `CCFUL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFUL_CODCONF | CHAR(11) | N |  |
| 6 | CFUL_CODPROD | CHAR(2) | N |  |
| 7 | CFUL_SUBPROD | CHAR(5) | N |  |
| 8 | CFUL_BLOCCO | CHAR(1) | N |  |
| 9 | CFUL_IMPRICV | DECIMAL(15,2) | N |  |
| 10 | CFUL_SPSSOTT | DECIMAL(15,2) | N |  |
| 11 | CFUL_PRTACQS | DECIMAL(13,3) | N |  |
| 12 | CFUL_PRTLIQD | DECIMAL(13,3) | N |  |
| 13 | CFUL_PRTRIFS | DECIMAL(13,3) | N |  |
| 14 | CFUL_PRTACQT | DECIMAL(13,3) | N |  |
| 15 | CFUL_IMPRIFS | DECIMAL(15,2) | N |  |
| 16 | CFUL_LIQUID | DECIMAL(15,2) | N |  |
| 17 | CFUL_INVEST | DECIMAL(15,2) | N |  |
| 18 | CFUL_RETE | CHAR(1) | N |  |
| 19 | CFUL_CAP_RIV | DECIMAL(11,2) | N | CAPITALE ASSICURATO |
| 20 | CFUL_RISERVA | DECIMAL(11,2) | N | RISERVA MATEMATICA |
| 21 | CFUL_DTEFFRIS | DECIMAL(9,0) | N | DATA EFFETTO RISERVA |
| 22 | CFUL_LINEAINV | CHAR(5) | N | LINEA INVESTIMENTO |
| 23 | CFUL_CAPGAREU | DECIMAL(15,2) | N | CAPITALE GARANTITO |
| 24 | CFUL_IGARCLEU | DECIMAL(15,2) | N | GARANZIA EROGATA |
| 25 | CFUL_SPSAMMI | DECIMAL(15,2) | N | SPESE AMMINISTRATIVE |
| 26 | CFUL_TASSE | DECIMAL(15,2) | N | TASSE |
| 27 | CFUL_DATA_RIV | DECIMAL(9,0) | N |  |
| 28 | CFUL_LASTMOV | SMALLINT |  |  |
| 29 | CFUL_ISPSLIQ | DECIMAL(15,2) |  |  |
| 30 | CFUL_FLUTTUA | DECIMAL(15,2) |  |  |
| 31 | CFUL_SALDOQUOTE | DECIMAL(15,7) |  |  |

Indici:

- `ASN_CCFUL_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCFZ_CD

*Tabella* – righe: 0
– change data della tabella `CCFZ`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CFZ_CODCONF | CHAR(11) | N |  |
| 5 | CFZ_CODPROD | CHAR(2) | N |  |
| 6 | CFZ_SUBPROD | CHAR(5) | N |  |
| 7 | CFZ_BLOCCO | CHAR(1) | N |  |
| 8 | CFZ_DTATTIV | DECIMAL(9,0) | N |  |
| 9 | CFZ_DTINI_SOSP | DECIMAL(9,0) | N |  |
| 10 | CFZ_DTFIN_SOSP | DECIMAL(9,0) | N |  |
| 11 | CFZ_DTREVOCA | DECIMAL(9,0) | N |  |
| 12 | CFZ_STATO_PRAT | CHAR(2) | N |  |
| 13 | CFZ_PERCESP | DECIMAL(7,3) | N |  |
| 14 | CFZ_FASCIA | CHAR(2) | N |  |
| 15 | CFZ_SPESE | DECIMAL(15,2) | N |  |
| 16 | CFZ_PAYIN | DECIMAL(15,2) | N |  |
| 17 | CFZ_PAYOUT | DECIMAL(15,2) | N |  |
| 18 | CFZ_IBAN | CHAR(27) | N |  |
| 19 | CFZ_CONTOCC | CHAR(12) | N |  |
| 20 | CFZ_CODCONF_SALV | CHAR(11) | N |  |
| 21 | CFZ_CODCONF_CC | CHAR(11) | N |  |
| 22 | CFZ_IMPORTO_FIDO | DECIMAL(15,2) | N |  |
| 23 | CFZ_TIPO_TASSO | CHAR(1) | N |  |
| 24 | CFZ_INDIC | DECIMAL(7,3) | N |  |
| 25 | CFZ_TIPOINDIC | CHAR(15) | N |  |
| 26 | CFZ_TAEG | DECIMAL(7,3) | N |  |
| 27 | CFZ_TAN | DECIMAL(7,3) | N |  |
| 28 | CFZ_SPREAD | DECIMAL(9,7) | N |  |
| 29 | CFZ_REDDITO_ANNUO1 | DECIMAL(15,2) | N |  |
| 30 | CFZ_REDDITO_ANNUO2 | DECIMAL(15,2) | N |  |
| 31 | CFZ_REDDITO_ANNUO3 | DECIMAL(15,2) | N |  |
| 32 | CFZ_REDDITO_ANNUO4 | DECIMAL(15,2) | N |  |
| 33 | CFZ_RETE | CHAR(1) | N |  |
| 34 | CFZ_ISTR_TIT | CHAR(2) | N |  |

Indici:

- `CCFZD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMA_CD5

*Tabella* – righe: 24
– change data della tabella `CCMA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMA_CODCONF | CHAR(11) | N |  |
| 5 | XCMA_CODCONF | CHAR(11) |  |  |
| 6 | CMA_PROGMOV | SMALLINT | N |  |
| 7 | XCMA_PROGMOV | SMALLINT |  |  |
| 8 | CMA_CODPROD | CHAR(2) | N |  |
| 9 | CMA_SUBPROD | CHAR(5) | N |  |
| 10 | XCMA_SUBPROD | CHAR(5) |  |  |
| 11 | CMA_TIPOPES | CHAR(2) | N |  |
| 12 | XCMA_TIPOPES | CHAR(2) |  |  |
| 13 | CMA_DVALCOMP | DECIMAL(9,0) | N |  |
| 14 | CMA_IMPOPER | DECIMAL(13,0) | N |  |
| 15 | CMA_IPREMPG | DECIMAL(13,0) | N |  |
| 16 | CMA_RATERIC | SMALLINT | N |  |
| 17 | CMA_PAYIN | DECIMAL(13,0) | N |  |
| 18 | CMA_PAYOUT | DECIMAL(13,0) | N |  |
| 19 | CMA_DTINCOP | DECIMAL(9,0) | N |  |
| 20 | XCMA_DTINCOP | DECIMAL(9,0) |  | DTINCOP BEFORE UPDATE |
| 21 | CMA_IMPEURO | DECIMAL(15,2) | N |  |
| 22 | CMA_EIPREMPG | DECIMAL(15,2) | N |  |
| 23 | CMA_EPAYIN | DECIMAL(15,2) | N |  |
| 24 | CMA_EPAYOUT | DECIMAL(15,2) | N |  |
| 25 | CMA_PERCCAR | DECIMAL(7,5) | N |  |
| 26 | CMA_IMPCAR | DECIMAL(11,2) | N |  |
| 27 | CMA_PREMIO_NETTO | DECIMAL(11,2) | N |  |
| 28 | CMA_FLUSSOIN | CHAR(8) | N |  |
| 29 | CMA_FLUSSORC | CHAR(8) | N |  |
| 30 | CMA_EPAYIN_STIMATO | DECIMAL(15,2) | N |  |
| 31 | CMA_BLOCCO | CHAR(1) |  |  |
| 32 | CMA_BLOCCOT | CHAR(1) |  |  |
| 33 | CMA_IMPACCS | DECIMAL(13,0) |  |  |
| 34 | CMA_PAGABIL | DECIMAL(13,0) |  |  |
| 35 | CMA_ERRORE | DECIMAL(13,0) |  |  |
| 36 | CMA_PAPROV | DECIMAL(13,0) |  |  |
| 37 | CMA_DTCASSA | DECIMAL(9,0) |  |  |
| 38 | CMA_IMPOSTE | DECIMAL(9,0) |  |  |
| 39 | CMA_RATEO | DECIMAL(9,0) |  |  |
| 40 | CMA_CODDIV | CHAR(3) |  |  |
| 41 | CMA_DTCONEURO | DECIMAL(9,0) |  |  |
| 42 | CMA_EIMPACCS | DECIMAL(15,2) |  |  |
| 43 | CMA_EPAGABIL | DECIMAL(15,2) |  |  |
| 44 | CMA_EERRORE | DECIMAL(15,2) |  |  |
| 45 | CMA_EPAPROV | DECIMAL(15,2) |  |  |
| 46 | CMA_EIMPOSTE | DECIMAL(15,2) |  |  |
| 47 | CMA_ERATEO | DECIMAL(15,2) |  |  |
| 48 | CMA_PAYIN_STIMATO | DECIMAL(13,0) |  |  |
| 49 | CMA_STATUS | CHAR(1) |  |  |
| 50 | CMA_CODTRASF | CHAR(11) |  |  |
| 51 | CMA_DTMARSH | DECIMAL(9,0) |  |  |
| 52 | CMA_DTVALID | DECIMAL(9,0) |  |  |
| 53 | CMA_DTRITIN | DECIMAL(9,0) |  |  |
| 54 | CMA_TIPOTIT | CHAR(1) |  |  |
| 55 | CMA_STRENCO | CHAR(1) |  |  |
| 56 | CMA_DTRENCO | DECIMAL(9,0) |  |  |
| 57 | CMA_DTFFID | DECIMAL(9,0) |  |  |
| 58 | CMA_TIPORIMB | CHAR(2) |  |  |
| 59 | CMA_NLV | DECIMAL(10,0) |  |  |
| 60 | CMA_FLAGCON | CHAR(1) |  |  |
| 61 | CMA_DTRIF | DECIMAL(9,0) |  |  |
| 62 | CMA_USERID | CHAR(8) |  |  |
| 63 | XCMA_CODPROD | CHAR(2) |  |  |
| 64 | CMA_COD_LIV2 | CHAR(5) |  |  |
| 65 | CMA_COD_LIV3 | CHAR(5) |  |  |

Indici:

- `CCMAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCML_CD5

*Tabella* – righe: 0
– change data della tabella `CCML`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CML_CODCONF | CHAR(11) | N |  |
| 6 | CML_SUBPROD | CHAR(5) | N |  |
| 7 | CML_PROGMOV | SMALLINT | N |  |
| 8 | CML_PROGOPE | SMALLINT | N |  |
| 9 | CML_TIPOPER | CHAR(2) | N |  |
| 10 | CML_TIPOPES | CHAR(2) | N |  |
| 11 | CML_DVALNAV | DECIMAL(9,0) | N |  |
| 12 | CML_IMPOPER | DECIMAL(13,0) | N |  |
| 13 | CML_SPSSOTT | DECIMAL(13,0) | N |  |
| 14 | CML_SPSSERV | DECIMAL(13,0) | N |  |
| 15 | CML_SPSAMMI | DECIMAL(13,0) | N |  |
| 16 | CML_ISPSLIQ | DECIMAL(13,0) | N |  |
| 17 | CML_VALNAV | DECIMAL(13,0) | N |  |
| 18 | CML_PRTOPER | DECIMAL(13,3) | N |  |
| 19 | CML_PERCAPPL | DECIMAL(9,5) | N |  |
| 20 | CML_PERCTIPO | CHAR(1) | N |  |
| 21 | CML_SPSTASS | DECIMAL(13,0) | N |  |
| 22 | CML_CODPROD | CHAR(2) | N |  |
| 23 | CML_DVALFND | DECIMAL(9,0) |  |  |
| 24 | CML_VALNAV5D | DECIMAL(15,5) | N |  |
| 25 | CML_BLOCCO | CHAR(1) |  |  |
| 26 | CML_BLOCCOT | CHAR(1) |  |  |
| 27 | CML_DTPROP | DECIMAL(9,0) |  |  |
| 28 | CML_SPSPRCA | DECIMAL(5,3) |  |  |
| 29 | CML_FLUTTUA | DECIMAL(13,0) |  |  |
| 30 | CML_TARSPS | CHAR(4) |  |  |
| 31 | CML_RIMTIPO | CHAR(1) |  |  |
| 32 | CML_IMPRICH | DECIMAL(13,0) |  |  |
| 33 | CML_IMPEURO | DECIMAL(15,2) |  |  |
| 34 | CML_CODDIV | CHAR(3) |  |  |
| 35 | CML_DTCONEURO | DECIMAL(9,0) |  |  |
| 36 | CML_IMPRICHEURO | DECIMAL(15,2) |  |  |
| 37 | CML_SPSSOTEU | DECIMAL(13,2) |  |  |
| 38 | CML_SPSSEREU | DECIMAL(13,2) |  |  |
| 39 | CML_SPSAMEU | DECIMAL(13,2) |  |  |
| 40 | CML_ISPSLIQEU | DECIMAL(13,2) |  |  |
| 41 | CML_FLUTTEU | DECIMAL(13,2) |  |  |
| 42 | CML_SPSTASEU | DECIMAL(13,2) |  |  |
| 43 | XCML_CODCONF | CHAR(11) |  |  |
| 44 | XCML_CODPROD | CHAR(2) |  |  |
| 45 | XCML_SUBPROD | CHAR(5) |  |  |
| 46 | XCML_PROGMOV | SMALLINT |  |  |
| 47 | XCML_PROGOPE | SMALLINT |  |  |
| 48 | XCML_TIPOPES | CHAR(2) |  |  |
| 49 | CML_RA | DECIMAL(15,2) | N | RITENUTA DI ACCONTO |
| 50 | CML_DVALPREV | DECIMAL(9,0) | N |  |

Indici:

- `ASN_CCML_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMM_CD5

*Tabella* – righe: 0
– change data della tabella `CCMM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CMM_CODCONF | CHAR(11) | N |  |
| 6 | CMM_PROGMOV | SMALLINT | N |  |
| 7 | CMM_TIPOPER | CHAR(2) | N |  |
| 8 | CMM_DACQUIS | DECIMAL(9,0) | N |  |
| 9 | CMM_DELABOR | DECIMAL(9,0) | N |  |
| 10 | CMM_IMPOPER | DECIMAL(13,0) | N |  |
| 11 | CMM_CODPROD | CHAR(2) | N |  |
| 12 | CMM_DT_WEB | DECIMAL(9,0) | N |  |
| 13 | CMM_N_WEB | DECIMAL(7,0) | N |  |
| 14 | CMM_RETE | CHAR(1) | N |  |
| 15 | CMM_DTPROP | DECIMAL(9,0) | N |  |
| 16 | CMM_STATUS | CHAR(1) | N |  |
| 17 | CMM_CODSOSP | CHAR(2) | N | CODICE DI SOSPENSIONE |
| 18 | CMM_BLOCCO | CHAR(1) |  |  |
| 19 | CMM_BLOCCOT | CHAR(1) |  |  |
| 20 | CMM_RIMTIPO | CHAR(1) |  |  |
| 21 | CMM_RIMRIFE | CHAR(10) |  |  |
| 22 | CMM_PAGABIL | DECIMAL(13,0) |  |  |
| 23 | CMM_ERRORE | DECIMAL(13,0) |  |  |
| 24 | CMM_ECCEDEN | DECIMAL(13,0) |  |  |
| 25 | CMM_CFTDATA | DECIMAL(9,0) |  |  |
| 26 | CMM_DTPROT | DECIMAL(9,0) |  |  |
| 27 | CMM_DELABSTR | DECIMAL(9,0) |  |  |
| 28 | CMM_DELABCOM | DECIMAL(9,0) |  |  |
| 29 | CMM_IMPEURO | DECIMAL(15,2) |  |  |
| 30 | CMM_CODDIV | CHAR(3) |  |  |
| 31 | CMM_DTCONEURO | DECIMAL(9,0) |  |  |
| 32 | CMM_DPREDIS | DECIMAL(9,0) |  |  |
| 33 | CMM_EPAGABIL | DECIMAL(15,2) |  |  |
| 34 | CMM_EERRORE | DECIMAL(15,2) |  |  |
| 35 | CMM_EECCEDEN | DECIMAL(15,2) |  |  |
| 36 | CMM_CODSIMUL | DECIMAL(10,0) |  |  |
| 37 | CMM_DTINRM | DECIMAL(9,0) |  |  |
| 38 | XCMM_CODCONF | CHAR(11) |  |  |
| 39 | XCMM_PROGMOV | SMALLINT |  |  |
| 40 | XCMM_CODPROD | CHAR(2) |  |  |

Indici:

- `ASN_CCMM_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMP_CD5

*Tabella* – righe: 0
– change data della tabella `CCMP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CMP_CODCONF | CHAR(11) | N |  |
| 6 | CMP_PROGMOV | SMALLINT | N |  |
| 7 | CMP_SUBPROD | CHAR(5) | N |  |
| 8 | CMP_TIPOPES | CHAR(2) | N |  |
| 9 | CMP_DVALNAV | DECIMAL(9,0) | N |  |
| 10 | CMP_IMPOPER | DECIMAL(13,0) | N |  |
| 11 | CMP_SPSSOTT | DECIMAL(13,0) | N |  |
| 12 | CMP_SPSAMMI | DECIMAL(13,0) | N |  |
| 13 | CMP_SPSTASS | DECIMAL(13,0) | N |  |
| 14 | CMP_RATERIC | SMALLINT | N |  |
| 15 | CMP_NETINVS | DECIMAL(13,0) | N |  |
| 16 | CMP_PRTOPER | DECIMAL(13,3) | N |  |
| 17 | CMP_VALNAV | DECIMAL(13,0) | N |  |
| 18 | CMP_PAYIN | DECIMAL(13,0) | N |  |
| 19 | CMP_PAYOUT | DECIMAL(13,0) | N |  |
| 20 | CMP_PROGOPE | SMALLINT | N |  |
| 21 | CMP_DVALFND | DECIMAL(9,0) |  |  |
| 22 | CMP_ISPSLIQ | DECIMAL(11,0) | N |  |
| 23 | CMP_CODPROD | CHAR(2) |  |  |
| 24 | CMP_BLOCCO | CHAR(1) |  |  |
| 25 | CMP_BLOCCOT | CHAR(1) |  |  |
| 26 | CMP_SPSPRCA | DECIMAL(5,2) |  |  |
| 27 | CMP_ECCEDEN | DECIMAL(13,0) |  |  |
| 28 | CMP_PAGABIL | DECIMAL(13,0) |  |  |
| 29 | CMP_ERRORE | DECIMAL(13,0) |  |  |
| 30 | CMP_FLUTTUA | DECIMAL(13,0) |  |  |
| 31 | CMP_PERCSPSE | DECIMAL(3,0) |  |  |
| 32 | CMP_VALNAV5D | DECIMAL(15,5) |  |  |
| 33 | CMP_IMPEURO | DECIMAL(15,2) |  |  |
| 34 | CMP_CODDIV | CHAR(3) |  |  |
| 35 | CMP_DTCONEURO | DECIMAL(9,0) |  |  |
| 36 | CMP_SPSSOTEU | DECIMAL(13,2) |  |  |
| 37 | CMP_SPSAMEU | DECIMAL(13,2) |  |  |
| 38 | CMP_SPSTASEU | DECIMAL(13,2) |  |  |
| 39 | CMP_ECCEDEU | DECIMAL(13,2) |  |  |
| 40 | CMP_PAGABILEU | DECIMAL(13,2) |  |  |
| 41 | CMP_ERROREU | DECIMAL(13,2) |  |  |
| 42 | CMP_FLUTTEU | DECIMAL(13,2) |  |  |
| 43 | CMP_NETINEU | DECIMAL(13,2) |  |  |
| 44 | CMP_PAYINEU | DECIMAL(13,2) |  |  |
| 45 | CMP_PAYOUEU | DECIMAL(13,2) |  |  |
| 46 | CMP_ISPSLIQEU | DECIMAL(11,2) |  |  |
| 47 | CCMP_RA | DECIMAL(15,2) | N |  |

Indici:

- `ASN_CCMP_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMSP_CD

*Tabella* – righe: 0
– change data della tabella `CCMSP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CCMSP_CODCONF | CHAR(11) | N |  |
| 5 | CCMSP_PROGMOV | SMALLINT | N |  |
| 6 | CCMSP_CODPROD | CHAR(2) | N |  |
| 7 | CCMSP_SUBPROD | CHAR(5) | N |  |
| 8 | CCMSP_TIPOPES | CHAR(2) | N |  |
| 9 | CCMSP_VALNOMN | DECIMAL(13,0) | N |  |
| 10 | CCMSP_SPSPRC | DECIMAL(5,3) | N |  |
| 11 | CCMSP_PAYIN | DECIMAL(13,0) | N |  |
| 12 | CCMSP_PAYOUT | DECIMAL(13,0) | N |  |
| 13 | CCMSP_PRATICA | CHAR(6) | N |  |
| 14 | CCMSP_DURATA | DECIMAL(3,0) | N |  |

Indici:

- `CCMSPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMUL_CD5

*Tabella* – righe: 0
– change data della tabella `CCMUL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XCMUL_CODCONF | CHAR(11) |  |  |
| 6 | XCMUL_CODPROD | CHAR(2) |  |  |
| 7 | XCMUL_SUBPROD | CHAR(5) |  |  |
| 8 | XCMUL_PROGMOV | SMALLINT |  |  |
| 9 | XCMUL_PROGOPE | SMALLINT |  |  |
| 10 | XCMUL_TIPOPES | CHAR(2) |  |  |
| 11 | CMUL_CODCONF | CHAR(11) | N |  |
| 12 | CMUL_CODPROD | CHAR(2) | N |  |
| 13 | CMUL_SUBPROD | CHAR(5) | N |  |
| 14 | CMUL_PROGMOV | SMALLINT | N |  |
| 15 | CMUL_PROGOPE | SMALLINT | N |  |
| 16 | CMUL_TIPOPER | CHAR(2) | N |  |
| 17 | CMUL_TIPOPES | CHAR(2) | N |  |
| 18 | CMUL_BLOCCO | CHAR(1) | N |  |
| 19 | CMUL_DVALNAV | DECIMAL(9,0) | N |  |
| 20 | CMUL_DVALFND | DECIMAL(9,0) | N |  |
| 21 | CMUL_IMPOPER | DECIMAL(15,2) | N |  |
| 22 | CMUL_SPSSOTT | DECIMAL(15,2) | N |  |
| 23 | CMUL_PRTOPER | DECIMAL(11,3) | N |  |
| 24 | CMUL_VALNAV | DECIMAL(11,2) | N |  |
| 25 | CMUL_PAYIN | DECIMAL(15,2) | N |  |
| 26 | CMUL_PAYOUT | DECIMAL(15,2) | N |  |
| 27 | CMUL_TASSE | DECIMAL(15,2) | N |  |
| 28 | CMUL_PREMIO_NETTO | DECIMAL(15,2) | N |  |
| 29 | CMUL_PREMIO_PURO | DECIMAL(15,2) | N |  |
| 30 | CMUL_ISPSLIQ | DECIMAL(15,2) | N |  |
| 31 | CMUL_TIPCONTR | CHAR(1) | N |  |
| 32 | CMUL_SPSAMMI | DECIMAL(15,2) | N |  |
| 33 | CMUL_TIPOANT | CHAR(1) | N |  |
| 34 | CMUL_DETR_RED | CHAR(1) | N |  |
| 35 | CMUL_DETR_FAM | CHAR(1) | N |  |
| 36 | CMUL_DVALCOMP | DECIMAL(9,0) | N |  |
| 37 | CMUL_IMPCAP | DECIMAL(15,2) | N |  |
| 38 | CMUL_PERCTIPO | CHAR(1) | N |  |
| 39 | CMUL_IMPREND | DECIMAL(11,2) | N |  |
| 40 | CMUL_PERC_REND | DECIMAL(9,5) | N |  |
| 41 | CMUL_BLOCCOT | CHAR(1) |  |  |
| 42 | CMUL_FLUTTUA | DECIMAL(15,2) |  |  |
| 43 | CMUL_PRECONTO | DECIMAL(15,2) |  |  |
| 44 | CMUL_DTSCORPORO | DECIMAL(9,0) |  |  |
| 45 | CMUL_DTCASSA | DECIMAL(9,0) |  |  |
| 46 | CMUL_PERC_CAR | DECIMAL(7,5) |  |  |
| 47 | CMUL_PAYIN_ACQ | DECIMAL(15,2) |  |  |
| 48 | CMUL_PAYIN_RIC | DECIMAL(15,2) |  |  |
| 49 | CMUL_SBIPRO | DECIMAL(15,2) |  |  |
| 50 | CMUL_TIPOPROVV | CHAR(1) |  |  |
| 51 | CMUL_COMM_ACQUISTO | DECIMAL(15,2) |  |  |
| 52 | CMUL_COMM_INCASSO | DECIMAL(15,2) |  |  |
| 53 | CMUL_DIFF_PAYOUT | DECIMAL(15,2) |  |  |
| 54 | CMUL_FLUSSOIN | CHAR(8) |  |  |
| 55 | CMUL_FLUSSORC | CHAR(8) |  |  |
| 56 | CMUL_CODTRASF | CHAR(11) |  |  |
| 57 | CMUL_PAYIN_STIMATO | DECIMAL(13,0) |  |  |
| 58 | CMUL_EPAYIN_STIM | DECIMAL(15,2) |  |  |
| 59 | CMUL_DTMARSH | DECIMAL(9,0) |  |  |
| 60 | CMUL_DTVALID | DECIMAL(9,0) |  |  |
| 61 | CMUL_DTRITIN | DECIMAL(9,0) |  |  |
| 62 | CMUL_PERCAPPL | DECIMAL(9,5) |  |  |
| 63 | CMUL_LINEAINV | CHAR(5) |  |  |
| 64 | CMUL_PROGTIT | SMALLINT |  |  |
| 65 | CMUL_STRENCO | CHAR(1) |  |  |
| 66 | CMUL_DTRENCO | DECIMAL(9,0) |  |  |
| 67 | CMUL_DTFFID | DECIMAL(9,0) |  |  |
| 68 | CMUL_TIPORIMB | CHAR(2) |  |  |
| 69 | CMUL_STATO | CHAR(1) |  |  |
| 70 | CMUL_PRTOPER7D | DECIMAL(15,7) |  |  |
| 71 | CMUL_VALNAV7D | DECIMAL(15,7) |  |  |
| 72 | CMUL_IMPCCM | DECIMAL(15,2) |  |  |
| 73 | CMUL_TRANSACTION | CHAR(9) |  |  |
| 74 | CMUL_NLV | DECIMAL(10,0) |  |  |
| 75 | CMUL_FLAGCON | CHAR(1) |  |  |
| 76 | CMUL_DTRIF | DECIMAL(9,0) |  |  |
| 77 | CMUL_USERID | CHAR(8) |  |  |
| 78 | CMUL_REVERSE | CHAR(9) |  |  |
| 79 | CMUL_FLAGDEC | CHAR(2) | N |  |
| 80 | CMUL_IMPSCG | DECIMAL(15,2) | N | IMP. COMM GEST |
| 81 | CMUL_PRTBONUS | DECIMAL(11,3) | N |  |
| 82 | CMUL_BONUS | DECIMAL(15,2) | N |  |

Indici:

- `ASN_CCMUL_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CCMV_CD

*Tabella* – righe: 0
– change data della tabella `CCMV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMV_CODCONF | CHAR(11) | N |  |
| 5 | CMV_PROGMOV | SMALLINT | N |  |
| 6 | CMV_CODPROD | CHAR(2) | N |  |
| 7 | CMV_SUBPROD | CHAR(5) | N |  |
| 8 | CMV_TIPOPES | CHAR(2) | N |  |
| 9 | CMV_BLOCCO | CHAR(1) | N |  |
| 10 | CMV_BLOCCOT | CHAR(1) | N |  |
| 11 | CMV_IMPRICV | DECIMAL(13,0) | N |  |
| 12 | CMV_DVALUTA | DECIMAL(9,0) | N |  |
| 13 | CMV_PRCPAYO | DECIMAL(5,2) | N |  |
| 14 | CMV_PAYIN | DECIMAL(13,0) | N |  |
| 15 | CMV_PAYOUT | DECIMAL(13,0) | N |  |
| 16 | CMV_NMRIFER | CHAR(6) | N |  |
| 17 | CMV_VALNOMN | DECIMAL(13,0) | N |  |
| 18 | CMV_DURATA | DECIMAL(3,0) | N |  |
| 19 | CMV_INDFRAZ | CHAR(1) | N |  |
| 20 | CMV_IMPCAP | DECIMAL(15,3) | N |  |
| 21 | CMV_IMPAMM | DECIMAL(15,3) | N |  |
| 22 | CMV_IMPMOR | DECIMAL(15,3) | N |  |
| 23 | CMV_CAMBIO | DECIMAL(15,3) | N |  |
| 24 | CMV_DIVISA | CHAR(3) | N |  |
| 25 | CMV_DTSCAD | DECIMAL(9,0) | N |  |
| 26 | CMV_IMPRICEURO | DECIMAL(13,2) | N |  |
| 27 | CMV_PAYIN_EURO | DECIMAL(13,2) | N |  |
| 28 | CMV_PAYOUT_EURO | DECIMAL(13,2) | N |  |

Indici:

- `CCMVD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CFB_CD5

*Tabella* – righe: 0
– change data della tabella `CFB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFB_CODCONF | CHAR(11) | N |  |
| 6 | CFB_CODPROD | CHAR(2) | N |  |
| 7 | CFB_SUBPROD | CHAR(5) | N |  |
| 8 | CFB_BLOCCO | CHAR(1) | N |  |
| 9 | CFB_FASCIA | CHAR(2) | N |  |
| 10 | CFB_ABI | CHAR(5) | N |  |
| 11 | CFB_CAB | CHAR(5) | N |  |
| 12 | CFB_CONTO | CHAR(12) | N |  |
| 13 | CFB_ISRTIT | CHAR(2) | N |  |
| 14 | CFB_SERVIZI | CHAR(8) | N |  |
| 15 | CFB_CACLI | CHAR(2) | N |  |
| 16 | CFB_DULELAB | DECIMAL(9,0) | N |  |
| 17 | CFB_RETE | CHAR(1) | N |  |
| 18 | CFB_FLAGFIDO | CHAR(1) | N | ADESIONE ALL'AFFIDAMENTO |
| 19 | CFB_DTFIDO | DECIMAL(9,0) | N | DATA DI DECORRENZA DELL'AFFIDAMENTO |
| 20 | CFB_DAPERCC | DECIMAL(9,0) | N |  |
| 21 | CFB_CODCONF_CLG | CHAR(11) |  |  |

Indici:

- `ASN_CFB_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CFG_CD5

*Tabella* – righe: 0
– change data della tabella `CFG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFG_CODCONF | CHAR(11) | N |  |
| 6 | CFG_CODPROD | CHAR(2) | N |  |
| 7 | CFG_SUBPROD | CHAR(5) | N |  |
| 8 | CFG_BLOCCO | CHAR(1) | N |  |
| 9 | CFG_INDDIVI | CHAR(1) | N |  |
| 10 | CFG_IMPRICV | DECIMAL(13,0) | N |  |
| 11 | CFG_IMPRICL | DECIMAL(13,0) | N |  |
| 12 | CFG_IMPRIFS | DECIMAL(13,0) | N |  |
| 13 | CFG_IMPLIQD | DECIMAL(13,0) | N |  |
| 14 | CFG_SPSSOTT | DECIMAL(13,0) | N |  |
| 15 | CFG_SPSAMMI | DECIMAL(13,0) | N |  |
| 16 | CFG_SPSTASS | DECIMAL(13,0) | N |  |
| 17 | CFG_PRTACQS | DECIMAL(13,3) | N |  |
| 18 | CFG_PRTACQL | DECIMAL(13,3) | N |  |
| 19 | CFG_PRTACQT | DECIMAL(13,3) | N |  |
| 20 | CFG_PRTRIFS | DECIMAL(13,3) | N |  |
| 21 | CFG_PRTLIQD | DECIMAL(13,3) | N |  |
| 22 | CFG_PRTCRTF | DECIMAL(13,3) | N |  |
| 23 | CFG_PRTCEDT | DECIMAL(13,3) | N |  |
| 24 | CFG_PRTBLVI | DECIMAL(13,3) | N |  |
| 25 | CFG_ISPSLIQ | DECIMAL(13,0) | N |  |
| 26 | CFG_IMPRICEURO | DECIMAL(15,2) | N |  |
| 27 | CFG_RETE | CHAR(1) | N |  |

Indici:

- `ASN_CFG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CFO_CD

*Tabella* – righe: 0
– change data della tabella `CFO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CFO_CODCONF | CHAR(11) | N |  |
| 5 | CFO_CODPROD | CHAR(2) | N |  |
| 6 | CFO_SUBPROD | CHAR(5) | N |  |
| 7 | CFO_BLOCCO | CHAR(1) | N |  |
| 8 | CFO_TIPOTIT | CHAR(2) | N |  |
| 9 | CFO_VALNOMN | DECIMAL(15,3) | N |  |
| 10 | CFO_TITACQ | INTEGER | N |  |
| 11 | CFO_IMPRICV | DECIMAL(15,3) | N |  |
| 12 | CFO_TITLIQ | INTEGER | N |  |
| 13 | CFO_IMPLIQ | DECIMAL(15,3) | N |  |
| 14 | CFO_TITRIF | INTEGER | N |  |
| 15 | CFO_IMPRIF | DECIMAL(15,3) | N |  |
| 16 | CFO_TITCONS | INTEGER | N |  |
| 17 | CFO_IMPCONS | DECIMAL(15,3) | N |  |
| 18 | CFO_TITGAR | INTEGER | N |  |
| 19 | CFO_IMPGAR | DECIMAL(15,3) | N |  |
| 20 | CFO_PAGABIL | DECIMAL(15,3) | N |  |
| 21 | CFO_ERRORE | DECIMAL(15,3) | N |  |
| 22 | CFO_ECCEDEN | DECIMAL(15,3) | N |  |
| 23 | CFO_NETINVS | DECIMAL(15,3) | N |  |
| 24 | CFO_RITACC | DECIMAL(15,3) | N |  |
| 25 | CFO_RITFISC | DECIMAL(15,3) | N |  |
| 26 | CFO_SPSCONS | DECIMAL(15,3) | N |  |
| 27 | CFO_SPSSPED | DECIMAL(15,3) | N |  |
| 28 | CFO_SPSSOTT | DECIMAL(15,3) | N |  |
| 29 | CFO_SPSAMMI | DECIMAL(15,3) | N |  |
| 30 | CFO_SPSTASS | DECIMAL(15,3) | N |  |
| 31 | CFO_LASTMOV | SMALLINT | N |  |
| 32 | CFO_DIFFPOS | DECIMAL(9,0) | N |  |
| 33 | CFO_DIFFNEG | DECIMAL(9,0) | N |  |
| 34 | CFO_TITVAR | INTEGER | N |  |
| 35 | CFO_IMPVAR | DECIMAL(15,3) | N |  |
| 36 | CFO_DTALLIN | DECIMAL(9,0) | N |  |

Indici:

- `CFOD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CFS_CD5

*Tabella* – righe: 0
– change data della tabella `CFS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CFS_CODCONF | CHAR(11) | N |  |
| 6 | CFS_CODPROD | CHAR(2) | N |  |
| 7 | CFS_SUBPROD | CHAR(5) | N |  |
| 8 | CFS_NCONTO | CHAR(9) | N |  |
| 9 | CFS_LIQINTER | CHAR(1) | N |  |
| 10 | CFS_DVALORIZ | DECIMAL(9,0) | N |  |
| 11 | CFS_NQUEST | CHAR(16) | N |  |
| 12 | CFS_TCAPGAIN | CHAR(1) | N |  |
| 13 | CFS_TDIVID | CHAR(1) | N |  |
| 14 | CFS_CCT | CHAR(1) | N |  |
| 15 | CFS_BOT | CHAR(1) | N |  |
| 16 | CFS_BTP | CHAR(1) | N |  |
| 17 | CFS_TARSPS | CHAR(1) | N |  |
| 18 | CFS_IMPDICH | DECIMAL(13,0) | N |  |
| 19 | CFS_DTCHIU | DECIMAL(9,0) | N |  |
| 20 | CFS_DTREVOC | DECIMAL(9,0) | N |  |
| 21 | CFS_IMPRICV | DECIMAL(13,0) | N |  |
| 22 | CFS_NETINVS | DECIMAL(13,0) | N |  |
| 23 | CFS_IMPLIQD | DECIMAL(13,0) | N |  |
| 24 | CFS_IMPRIFS | DECIMAL(13,0) | N |  |
| 25 | CFS_SPSSOTT | DECIMAL(11,0) | N |  |
| 26 | CFS_SPEGEST | DECIMAL(11,0) | N |  |
| 27 | CFS_SPEFID | DECIMAL(11,0) | N |  |
| 28 | CFS_SPESIG | DECIMAL(11,0) | N |  |
| 29 | CFS_SPSAMMI | DECIMAL(11,0) | N |  |
| 30 | CFS_EIMPRICV | DECIMAL(13,2) | N |  |
| 31 | CFS_EIMPLIQD | DECIMAL(13,2) | N |  |
| 32 | CFS_ESPEGEST | DECIMAL(11,2) | N |  |
| 33 | CFS_EIMPDICH | DECIMAL(13,2) | N |  |
| 34 | CFS_RETE | CHAR(1) | N |  |
| 35 | CFS_EIMPIFU | DECIMAL(13,2) | N |  |
| 36 | CFS_CVN | DECIMAL(15,2) | N |  |
| 37 | CFS_CAPPROT | DECIMAL(15,2) | N | CAPITALE PROTETTO |
| 38 | CFS_LINEAGEO | CHAR(1) | N |  |
| 39 | CFS_LINEA | CHAR(5) | N | INDICATIVO LINEA DI INVESTIMENTO |
| 40 | CFS_PLUSVALENZE | DECIMAL(15,2) | N | PLUSVALENZE |
| 41 | CFS_PROVENTI | DECIMAL(15,2) | N | PROVENTI |
| 42 | CFS_ONERI | DECIMAL(15,2) | N | ONERI |
| 43 | CFS_CVN_CONT | DECIMAL(15,2) | N | CLASSE VERSAMENTI NETTI PER CONTRATTO CONTENITORE |
| 44 | CFS_EPATRN | DECIMAL(15,2) | N | PATRIMONIO |
| 45 | CFS_REND | CHAR(1) | N | CADENZA RENDICONTAZIONE |
| 46 | CFS_NUMMODL | CHAR(11) |  |  |
| 47 | CFS_BLOCCO | CHAR(1) |  |  |
| 48 | CFS_CTRVLIQ | DECIMAL(15,0) |  |  |
| 49 | CFS_CTRVRF | DECIMAL(15,0) |  |  |
| 50 | CFS_CTRVAZ | DECIMAL(15,0) |  |  |
| 51 | CFS_PATRN | DECIMAL(15,0) |  |  |
| 52 | CFS_LASTMOV | SMALLINT |  |  |
| 53 | CFS_CTRFONDI_NON | DECIMAL(15,0) |  |  |
| 54 | CFS_CTRFONDI_IMI | DECIMAL(15,0) |  |  |
| 55 | CFS_SPEMOVIM | DECIMAL(11,0) |  |  |
| 56 | CFS_IMPIFU | DECIMAL(13,0) |  |  |
| 57 | CFS_IMPBOT | DECIMAL(13,0) |  |  |
| 58 | CFS_IMPBTP | DECIMAL(13,0) |  |  |
| 59 | CFS_IMPCCT | DECIMAL(13,0) |  |  |
| 60 | CFS_SPREAD | DECIMAL(7,4) |  |  |
| 61 | CFS_DURATA | SMALLINT |  |  |
| 62 | CFS_PROGFAM | DECIMAL(5,0) |  |  |
| 63 | CFS_ECTRVLIQ | DECIMAL(15,2) |  |  |
| 64 | CFS_ECTRVAZ | DECIMAL(15,2) |  |  |
| 65 | CFS_CODDIV | CHAR(3) |  |  |
| 66 | CFS_DTBOLL | DECIMAL(9,0) |  |  |
| 67 | CFS_RCPRO | CHAR(1) |  |  |
| 68 | CFS_ESPSSOTT | DECIMAL(15,2) |  |  |
| 69 | CFS_VOLMED | CHAR(20) |  |  |
| 70 | CFS_VOLMAX | CHAR(20) |  |  |
| 71 | CFS_EIMPFDT | DECIMAL(15,2) |  |  |
| 72 | CFS_EIMPTIT | DECIMAL(15,2) |  |  |
| 73 | CFS_EIMPFOI | DECIMAL(15,2) |  |  |
| 74 | CFS_NSERIE | CHAR(11) |  |  |
| 75 | CFS_REGIME | CHAR(1) |  |  |
| 76 | CFS_CONTR_SPI | CHAR(10) |  |  |
| 77 | CFS_MARGINI | DECIMAL(15,2) |  |  |
| 78 | CFS_MFIDR4 | CHAR(1) |  |  |
| 79 | CFS_DTREND | DECIMAL(9,0) |  |  |
| 80 | CFS_IVA | DECIMAL(15,2) | N | IVA |
| 81 | CFS_DTSCAD_PCP | DECIMAL(9,0) | N | DTSCAD_PCP |
| 82 | CFS_EIMPST_PCP | DECIMAL(15,2) | N | EIMPST_PCP |
| 83 | CFS_NEW_REGIME | CHAR(1) |  |  |
| 84 | CFS_DTVALID_NEWREG | DECIMAL(9,0) |  |  |
| 85 | CFS_IDPROD_PERS | DECIMAL(12,0) |  |  |

Indici:

- `ASN_CFS_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMB_CD

*Tabella* – righe: 0
– change data della tabella `CMB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMB_CODCONF | CHAR(11) | N |  |
| 5 | CMB_PROGMOV | SMALLINT | N |  |
| 6 | CMB_CODPROD | CHAR(2) | N |  |
| 7 | CMB_SUBPROD | CHAR(5) | N |  |
| 8 | CMB_TIPOPES | CHAR(2) | N |  |
| 9 | CMB_BLOCCO | CHAR(1) | N |  |
| 10 | CMB_BLOCCOT | CHAR(1) | N |  |
| 11 | CMB_DVALUTA | DECIMAL(9,0) | N |  |
| 12 | CMB_DVALEFF | DECIMAL(9,0) | N |  |
| 13 | CMB_IMPOPER | DECIMAL(13,0) | N |  |
| 14 | CMB_PAYIN | DECIMAL(15,3) | N |  |
| 15 | CMB_PAYOUT | DECIMAL(15,3) | N |  |
| 16 | CMB_SUBSPROD | CHAR(5) | N |  |

Indici:

- `CMBD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMCCL_CD

*Tabella* – righe: 0
– change data della tabella `CMCCL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMCCL_CODCONF | CHAR(11) | N |  |
| 5 | CMCCL_PROGMOV | SMALLINT | N |  |
| 6 | CMCCL_CODPROD | CHAR(2) | N |  |
| 7 | CMCCL_SUBPROD | CHAR(5) | N |  |
| 8 | CMCCL_TIPOPES | CHAR(2) | N |  |
| 9 | CMCCL_DELABOR | DECIMAL(9,0) | N |  |
| 10 | CMCCL_DPERFEZ | DECIMAL(9,0) | N |  |
| 11 | CMCCL_VALNOMN | DECIMAL(13,0) | N |  |
| 12 | CMCCL_SCTASSO | DECIMAL(5,3) | N |  |
| 13 | CMCCL_PRPROVC | DECIMAL(5,3) | N |  |
| 14 | CMCCL_PRPROVE | DECIMAL(5,3) | N |  |
| 15 | CMCCL_PAYINC | DECIMAL(13,0) | N |  |
| 16 | CMCCL_PAYINE | DECIMAL(13,0) | N |  |
| 17 | CMCCL_PAYOUT | DECIMAL(13,0) | N |  |

Indici:

- `CMCCLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMG_CD5

*Tabella* – righe: 0
– change data della tabella `CMG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CMG_CODCONF | CHAR(11) | N |  |
| 6 | CMG_PROGMOV | SMALLINT | N |  |
| 7 | CMG_SUBPROD | CHAR(5) | N |  |
| 8 | CMG_TIPOPES | CHAR(2) | N |  |
| 9 | CMG_DVALNAV | DECIMAL(9,0) | N |  |
| 10 | CMG_IMPOPER | DECIMAL(13,0) | N |  |
| 11 | CMG_SPSSOTT | DECIMAL(13,0) | N |  |
| 12 | CMG_SPSAMMI | DECIMAL(13,0) | N |  |
| 13 | CMG_SPSTASS | DECIMAL(13,0) | N |  |
| 14 | CMG_NETINVS | DECIMAL(13,0) | N |  |
| 15 | CMG_PRTOPER | DECIMAL(13,3) | N |  |
| 16 | CMG_VALNAV | DECIMAL(13,0) | N |  |
| 17 | CMG_PAYIN | DECIMAL(13,0) | N |  |
| 18 | CMG_PAYOUT | DECIMAL(13,0) | N |  |
| 19 | CMG_PROGOPE | SMALLINT | N |  |
| 20 | CMG_DVALFND | DECIMAL(9,0) | N |  |
| 21 | CMG_ISPSLIQ | DECIMAL(11,0) | N |  |
| 22 | CMG_CODPROD | CHAR(2) |  |  |
| 23 | CMG_BLOCCO | CHAR(1) |  |  |
| 24 | CMG_BLOCCOT | CHAR(1) |  |  |
| 25 | CMG_PAGABIL | DECIMAL(13,0) |  |  |
| 26 | CMG_ERRORE | DECIMAL(13,0) |  |  |
| 27 | CMG_FLUTTUA | DECIMAL(13,0) |  |  |
| 28 | CMG_SPSPRCA | DECIMAL(5,2) |  |  |
| 29 | CMG_DVALSEN | DECIMAL(9,0) |  |  |
| 30 | CMG_PERCSPSE | DECIMAL(3,0) |  |  |
| 31 | CMG_IVOLADD | DECIMAL(13,0) |  |  |
| 32 | CMG_VALNAV5D | DECIMAL(15,5) |  |  |
| 33 | CMG_IMPEURO | DECIMAL(15,2) |  |  |
| 34 | CMG_CODDIV | CHAR(3) |  |  |
| 35 | CMG_DTCONEURO | DECIMAL(9,0) |  |  |
| 36 | CMG_SPSSOTEU | DECIMAL(13,2) |  |  |
| 37 | CMG_SPSAMEU | DECIMAL(13,2) |  |  |
| 38 | CMG_SPSTASEU | DECIMAL(13,2) |  |  |
| 39 | CMG_PAGABILEU | DECIMAL(13,2) |  |  |
| 40 | CMG_ERROREU | DECIMAL(13,2) |  |  |
| 41 | CMG_FLUTTEU | DECIMAL(13,2) |  |  |
| 42 | CMG_NETINEU | DECIMAL(13,2) |  |  |
| 43 | CMG_PAYINEU | DECIMAL(13,2) |  |  |
| 44 | CMG_PAYOUEU | DECIMAL(13,2) |  |  |
| 45 | CMG_IVOLADEU | DECIMAL(13,2) |  |  |
| 46 | CMG_ISPSLIQEU | DECIMAL(11,2) |  |  |
| 47 | CMG_RA | DECIMAL(15,2) | N |  |

Indici:

- `ASN_CMG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMO_CD

*Tabella* – righe: 0
– change data della tabella `CMO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMO_CODCONF | CHAR(11) | N |  |
| 5 | CMO_PROGMOV | SMALLINT | N |  |
| 6 | CMO_CODPROD | CHAR(2) | N |  |
| 7 | CMO_SUBPROD | CHAR(5) | N |  |
| 8 | CMO_TIPOPES | CHAR(2) | N |  |
| 9 | CMO_BLOCCO | CHAR(1) | N |  |
| 10 | CMO_BLOCCOT | CHAR(1) | N |  |
| 11 | CMO_MERCATO | CHAR(1) | N |  |
| 12 | CMO_DATVAL | INTEGER | N |  |
| 13 | CMO_IMPOPER | DECIMAL(15,3) | N |  |
| 14 | CMO_PAGABIL | DECIMAL(15,3) | N |  |
| 15 | CMO_ERRORE | DECIMAL(15,3) | N |  |
| 16 | CMO_ECCEDEN | DECIMAL(15,3) | N |  |
| 17 | CMO_NETINVS | DECIMAL(15,3) | N |  |
| 18 | CMO_NUMTIT | INTEGER | N |  |
| 19 | CMO_RITACC | DECIMAL(15,3) | N |  |
| 20 | CMO_RITFISC | DECIMAL(15,3) | N |  |
| 21 | CMO_DIETIMI | DECIMAL(15,3) | N |  |
| 22 | CMO_SPSCONS | DECIMAL(15,3) | N |  |
| 23 | CMO_SPSSPED | DECIMAL(15,3) | N |  |
| 24 | CMO_SPSSOTT | DECIMAL(15,3) | N |  |
| 25 | CMO_SPSAMMI | DECIMAL(15,3) | N |  |
| 26 | CMO_SPSTASS | DECIMAL(15,3) | N |  |
| 27 | CMO_ESENBOL | CHAR(1) | N |  |
| 28 | CMO_FISSOBOL | CHAR(1) | N |  |
| 29 | CMO_DIFFPRZ | DECIMAL(15,3) | N |  |
| 30 | CMO_PREZZO | DECIMAL(15,3) | N |  |
| 31 | CMO_BASPRO | DECIMAL(7,3) | N |  |
| 32 | CMO_PAYIN | DECIMAL(15,3) | N |  |
| 33 | CMO_PAYOUT | DECIMAL(15,3) | N |  |
| 34 | CMO_VALNOMN | DECIMAL(15,3) | N |  |
| 35 | CMO_DIFFPOS | DECIMAL(9,0) | N |  |
| 36 | CMO_DIFFNEG | DECIMAL(9,0) | N |  |
| 37 | CMO_SUBSPROD | CHAR(5) | N |  |
| 38 | CMO_PROGOPER | SMALLINT | N |  |
| 39 | CMO_NUMREG | DECIMAL(13,0) | N |  |
| 40 | CMO_NREGIS | CHAR(24) | N |  |
| 41 | CMO_IMPOPER_DIV | DECIMAL(15,3) | N |  |

Indici:

- `CMOD03` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMS_CD5

*Tabella* – righe: 0
– change data della tabella `CMS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CMS_CODCONF | CHAR(11) | N |  |
| 6 | CMS_PROGMOV | SMALLINT | N |  |
| 7 | CMS_CODPROD | CHAR(2) | N |  |
| 8 | CMS_SUBPROD | CHAR(5) | N |  |
| 9 | CMS_TIPOPES | CHAR(2) | N |  |
| 10 | CMS_SPSSOTT | DECIMAL(13,0) | N |  |
| 11 | CMS_SPEGEST | DECIMAL(13,0) | N |  |
| 12 | CMS_SPEFID | DECIMAL(13,0) | N |  |
| 13 | CMS_SPESIG | DECIMAL(13,0) | N |  |
| 14 | CMS_SPSAMMI | DECIMAL(11,0) | N |  |
| 15 | CMS_NETINVS | DECIMAL(13,0) | N |  |
| 16 | CMS_DVALORIZ | DECIMAL(9,0) | N |  |
| 17 | CMS_PATRN | DECIMAL(15,0) | N |  |
| 18 | CMS_PAYIN | DECIMAL(13,0) | N |  |
| 19 | CMS_PAYOUT | DECIMAL(13,0) | N |  |
| 20 | CMS_IMPLIQD | DECIMAL(13,0) | N |  |
| 21 | CMS_DELABOR | DECIMAL(9,0) | N |  |
| 22 | CMS_DVALUTA | DECIMAL(9,0) | N |  |
| 23 | CMS_IMPRICV | DECIMAL(13,0) | N |  |
| 24 | CMS_CODSPSE | CHAR(1) | N |  |
| 25 | CMS_PERCSP | DECIMAL(7,5) | N |  |
| 26 | CMS_GIORNI | DECIMAL(3,0) | N |  |
| 27 | CMS_NRIFER | DECIMAL(13,0) | N |  |
| 28 | CMS_NRIFSTO | DECIMAL(13,0) | N |  |
| 29 | CMS_TIPOTIT | CHAR(3) | N |  |
| 30 | CMS_PROGOPE | SMALLINT | N |  |
| 31 | CMS_RIMTIPO | CHAR(1) | N |  |
| 32 | CMS_DVALUTACC | DECIMAL(9,0) | N |  |
| 33 | CMS_CODTIT | CHAR(12) | N |  |
| 34 | CMS_QTA | DECIMAL(15,3) | N |  |
| 35 | CMS_PREZZO | DECIMAL(15,5) | N |  |
| 36 | CMS_CAMBIO | DECIMAL(15,5) | N |  |
| 37 | CMS_DIVISA | CHAR(3) | N |  |
| 38 | CMS_TASSE | DECIMAL(15,0) | N |  |
| 39 | CMS_BOLLI | DECIMAL(15,0) | N |  |
| 40 | CMS_EIMPRICV | DECIMAL(13,2) | N |  |
| 41 | CMS_EIMPLIQD | DECIMAL(13,2) | N |  |
| 42 | CMS_ESPEGEST | DECIMAL(13,2) | N |  |
| 43 | CMS_EPAYIN | DECIMAL(13,2) | N |  |
| 44 | CMS_EPAYOUT | DECIMAL(13,2) | N |  |
| 45 | CMS_EBOLLI | DECIMAL(15,2) | N |  |
| 46 | CMS_DTACCR | DECIMAL(9,0) | N |  |
| 47 | CMS_DSALDO | DECIMAL(9,0) | N |  |
| 48 | XCMS_CODCONF | CHAR(11) |  | CONTRATTO OLD |
| 49 | XCMS_PROGMOV | SMALLINT |  | PROGMOV   OLD |
| 50 | XCMS_TIPOPES | CHAR(2) |  | TIPOPES   OLD |
| 51 | XCMS_CODPROD | CHAR(2) |  | CODPROD   OLD |
| 52 | XCMS_SUBPROD | CHAR(5) |  | SUBPROD   OLD |
| 53 | XCMS_PROGOPE | SMALLINT |  | PROGOPE   OLD |
| 54 | CMS_VALNAV5D | DECIMAL(15,5) |  |  |
| 55 | CMS_CODDIV | CHAR(3) |  |  |
| 56 | CMS_RETE | CHAR(1) |  |  |
| 57 | CMS_CVN | DECIMAL(15,2) |  |  |
| 58 | CMS_PRSCONTO | DECIMAL(5,2) |  |  |
| 59 | CMS_ESPSSOTT | DECIMAL(15,2) |  |  |
| 60 | CMS_PRSPSSOTT | DECIMAL(5,2) |  |  |
| 61 | CMS_DRENCO | DECIMAL(9,0) |  |  |
| 62 | CMS_PROGEC | CHAR(11) |  |  |
| 63 | CMS_IVA | DECIMAL(15,2) | N | IVA |

Indici:

- `ASN_CMS_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CMT_CD

*Tabella* – righe: 0
– change data della tabella `CMT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CMT_CODCONF | CHAR(11) | N |  |
| 5 | CMT_PROGMOV | SMALLINT | N |  |
| 6 | CMT_CODPROD | CHAR(2) | N |  |
| 7 | CMT_SUBPROD | CHAR(5) | N |  |
| 8 | CMT_DREGOL | DECIMAL(9,0) | N |  |
| 9 | CMT_TIPOPER | CHAR(2) | N |  |
| 10 | CMT_BLOCCO | CHAR(1) | N |  |
| 11 | CMT_BLOCCOT | CHAR(1) | N |  |
| 12 | CMT_IMPOPER | DECIMAL(13,0) | N |  |
| 13 | CMT_TASPROV | DECIMAL(7,4) | N |  |
| 14 | CMT_IMPPROV | DECIMAL(13,0) | N |  |
| 15 | CMT_PAYIN | DECIMAL(13,0) | N |  |
| 16 | CMT_PAYOUT | DECIMAL(13,0) | N |  |

Indici:

- `CMTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_COAGM_CD

*Tabella* – righe: 11.587
– change data della tabella `COAGM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | COAGM_RETE | CHAR(1) | N |  |
| 5 | COAGM_CODAGE | CHAR(6) | N |  |
| 6 | XCOAGM_CODAGE | CHAR(6) |  |  |
| 7 | COAGM_CODCONF | CHAR(11) | N |  |
| 8 | XCOAGM_CODCONF | CHAR(11) |  |  |
| 9 | COAGM_DVALINI | DECIMAL(9,0) | N |  |
| 10 | COAGM_DVALFIN | DECIMAL(9,0) | N |  |
| 11 | XCOAGM_DVALFIN | DECIMAL(9,0) |  |  |
| 12 | COAGM_TIPAGE | CHAR(1) | N |  |
| 13 | XCOAGM_TIPAGE | CHAR(1) |  |  |
| 14 | COAGM_PRCAGE | SMALLINT | N |  |

Indici:

- `IXCDCOAGM` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_COAGSPI_CD

*Tabella* – righe: 3.099
– change data della tabella `COAGSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | COAGSPI_CODAGE | CHAR(6) | N |  |
| 6 | XCOAGSPI_CODAGE | CHAR(6) |  |  |
| 7 | COAGSPI_CODCONF | CHAR(11) | N |  |
| 8 | XCOAGSPI_CODCONF | CHAR(11) |  |  |
| 9 | COAGSPI_DVALINI | DECIMAL(9,0) | N |  |
| 10 | COAGSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 11 | XCOAGSPI_DVALFIN | DECIMAL(9,0) |  |  |
| 12 | COAGSPI_TIPAGE | CHAR(1) | N |  |
| 13 | XCOAGSPI_TIPAGE | CHAR(1) |  |  |
| 14 | COAGSPI_PRCAGE | SMALLINT | N |  |

Indici:

- `COAGSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_COAG_CD5

*Tabella* – righe: 0
– change data della tabella `COAG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XCOAG_CODAGE | CHAR(6) |  |  |
| 6 | XCOAG_CODCONF | CHAR(11) |  |  |
| 7 | XCOAG_DVALFIN | DECIMAL(9,0) |  |  |
| 8 | XCOAG_TIPAGE | CHAR(1) |  |  |
| 9 | COAG_CODAGE | CHAR(6) | N |  |
| 10 | COAG_CODCONF | CHAR(11) | N |  |
| 11 | COAG_DVALINI | DECIMAL(9,0) | N |  |
| 12 | COAG_DVALFIN | DECIMAL(9,0) | N |  |
| 13 | COAG_TIPAGE | CHAR(1) | N |  |
| 14 | COAG_PRCAGE | SMALLINT | N |  |

Indici:

- `ASN_COAG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_COCF_CD

*Tabella* – righe: 24
– change data della tabella `COCF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | COCF_CODCONF | CHAR(11) | N |  |
| 5 | COCF_CODPROD | CHAR(2) | N |  |
| 6 | COCF_SUBPROD | CHAR(5) | N |  |
| 7 | COCF_DTADES | DECIMAL(9,0) | N |  |
| 8 | COCF_IMPOPER | DECIMAL(15,2) | N |  |
| 9 | COCF_IVA | DECIMAL(15,2) | N |  |
| 10 | COCF_PAYIN | DECIMAL(15,2) | N |  |
| 11 | COCF_PAYOUT | DECIMAL(15,2) | N |  |
| 12 | COCF_RETE | CHAR(1) | N |  |
| 13 | COCF_BLOCCO | CHAR(1) | N |  |
| 14 | COCF_MONITORAGGIO | CHAR(1) | N |  |
| 15 | COCF_DIAGNOSI | CHAR(1) | N |  |
| 16 | COCF_ABI | CHAR(5) | N |  |
| 17 | COCF_CAB | CHAR(5) | N |  |
| 18 | COCF_CC | CHAR(12) | N |  |
| 19 | COCF_IBAN | CHAR(27) | N |  |
| 20 | COCF_CPP | CHAR(4) | N |  |
| 21 | COCF_EMAIL | CHAR(50) | N |  |
| 22 | COCF_FATTURA | CHAR(1) | N |  |
| 23 | COCF_DTLETBENV | DECIMAL(9,0) | N |  |

Indici:

- `COCFD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_COCM_CD

*Tabella* – righe: 2
– change data della tabella `COCM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | COCM_CODCONF | CHAR(11) | N |  |
| 5 | COCM_CODPROD | CHAR(2) | N |  |
| 6 | COCM_SUBPROD | CHAR(5) | N |  |
| 7 | COCM_PROGMOV | SMALLINT | N |  |
| 8 | COCM_PROGOPE | SMALLINT | N |  |
| 9 | COCM_DTINTRIM | DECIMAL(9,0) | N |  |
| 10 | COCM_DTFITRIM | DECIMAL(9,0) | N |  |
| 11 | COCM_TIPOPER | CHAR(2) | N |  |
| 12 | COCM_TIPOPES | CHAR(2) | N |  |
| 13 | COCM_IMPOPER | DECIMAL(15,2) | N |  |
| 14 | COCM_IVA | DECIMAL(15,2) | N |  |
| 15 | COCM_PAYIN | DECIMAL(15,2) | N |  |
| 16 | COCM_PAYOUT | DECIMAL(15,2) | N |  |
| 17 | COCM_CPP | CHAR(4) | N |  |
| 18 | COCM_PERCSPE | DECIMAL(5,2) | N |  |
| 19 | COCM_PERCAG | DECIMAL(5,2) | N |  |
| 20 | COCM_RFA | DECIMAL(15,2) | N |  |
| 21 | COCM_DTVALADD | DECIMAL(9,0) | N |  |
| 22 | COCM_IMPOSTA | DECIMAL(15,2) |  |  |
| 23 | COCM_IMPOPER_LOR | DECIMAL(15,2) |  |  |
| 24 | XCOCM_CODCONF | CHAR(11) |  |  |
| 25 | XCOCM_CODPROD | CHAR(2) |  |  |
| 26 | XCOCM_SUBPROD | CHAR(5) |  |  |
| 27 | XCOCM_PROGMOV | SMALLINT |  |  |
| 28 | XCOCM_PROGOPE | SMALLINT |  |  |

Indici:

- `COCMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CONSR_CD

*Tabella* – righe: 854.918
– change data della tabella `CONSR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CONSR_CODCONF | CHAR(11) | N |  |
| 5 | CONSR_CODAGE | CHAR(6) | N |  |
| 6 | CONSR_DT_ACQSPE | DECIMAL(9,0) | N |  |
| 7 | CONSR_ORA_ACQSPE | DECIMAL(9,0) | N |  |
| 8 | CONSR_DT_VALIDAZ | DECIMAL(9,0) | N |  |
| 9 | CONSR_DT_ATTIVAZ | DECIMAL(9,0) | N |  |
| 10 | CONSR_DT_REVOCA | DECIMAL(9,0) | N |  |
| 11 | CONSR_BLOCCO | CHAR(1) | N |  |
| 12 | CONSR_RFA6_ACQSPE | DECIMAL(15,2) | N |  |
| 13 | CONSR_RFA6_FAC | DECIMAL(15,2) | N |  |
| 14 | CONSR_RFA6_FAS | DECIMAL(15,2) | N |  |
| 15 | CONSR_SCONTO_SOT | CHAR(2) | N |  |
| 16 | CONSR_SCONTO_SPS | CHAR(2) | N |  |
| 17 | CONSR_DT_SCAD_SPS | DECIMAL(9,0) | N |  |
| 18 | CONSR_CPP_DATA | CHAR(4) | N |  |
| 19 | CONSR_CPP_FAC | CHAR(4) | N |  |
| 20 | CONSR_CPP_FAS | CHAR(4) | N |  |
| 21 | CONSR_CPP_SOTTOS | CHAR(4) | N |  |
| 22 | CONSR_DT_SOTTOS | DECIMAL(9,0) | N |  |
| 23 | CONSR_DT_RFA | DECIMAL(9,0) | N |  |
| 24 | CONSR_RFA_FMESE | DECIMAL(15,2) | N |  |
| 25 | CONSR_RETE | CHAR(1) | N |  |
| 26 | CONSR_CODSPSE | CHAR(1) | N |  |
| 27 | CONSR_SUBPROD | CHAR(5) | N |  |
| 28 | CONSR_PRCCOM | DECIMAL(5,2) |  |  |

Indici:

- `CONSRD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CORIC_CD

*Tabella* – righe: 15.092
– change data della tabella `CORIC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CORIC_CODCONF | CHAR(11) | N |  |
| 5 | CORIC_PROGRIC | SMALLINT | N |  |
| 6 | CORIC_STATORIC | CHAR(1) | N |  |
| 7 | CORIC_CAUSALE | CHAR(3) | N |  |
| 8 | CORIC_RETE | CHAR(1) | N |  |
| 9 | CORIC_DTINS | DECIMAL(9,0) | N |  |
| 10 | CORIC_DTVAL | DECIMAL(9,0) | N |  |
| 11 | CORIC_DTSTRALCIO | DECIMAL(9,0) | N |  |
| 12 | CORIC_DTEFFETTO | DECIMAL(9,0) | N |  |
| 13 | CORIC_MITT | CHAR(8) | N |  |
| 14 | CORIC_DTAGZ | CHAR(6) | N |  |
| 15 | CORIC_NPROGR | CHAR(2) | N |  |
| 16 | CORIC_BLOCCO | CHAR(1) | N |  |
| 17 | CORIC_MONITORAGGIO | CHAR(1) | N |  |
| 18 | CORIC_DIAGNOSI | CHAR(1) | N |  |
| 19 | CORIC_ABI | CHAR(5) | N |  |
| 20 | CORIC_CAB | CHAR(5) | N |  |
| 21 | CORIC_CC | CHAR(12) | N |  |
| 22 | CORIC_IBAN | CHAR(27) | N |  |
| 23 | CORIC_CPP | CHAR(4) | N |  |
| 24 | CORIC_PERCAG | DECIMAL(5,2) | N |  |
| 25 | CORIC_EMAIL | CHAR(50) | N |  |
| 26 | CORIC_FATTURA | CHAR(1) | N |  |
| 27 | CORIC_DTLETCC | DECIMAL(9,0) | N |  |
| 28 | CORIC_IMPOPER | DECIMAL(15,2) | N |  |
| 29 | CORIC_IVA | DECIMAL(15,2) | N |  |
| 30 | CORIC_TIPO_CONSUL | CHAR(4) |  |  |

Indici:

- `CORICD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CTRA_CD5

*Tabella* – righe: 0
– change data della tabella `CTRA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CTRA_CODCONFC | CHAR(11) | N |  |
| 6 | CTRA_CODCONFR | CHAR(11) | N |  |
| 7 | CTRA_PROGMOVC | SMALLINT | N |  |
| 8 | CTRA_PROGMOVR | SMALLINT | N |  |
| 9 | CTRA_CAUSALE | DECIMAL(5,0) | N |  |
| 10 | CTRA_DACQUIS | DECIMAL(9,0) | N |  |

Indici:

- `ASN_CTRA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CVNUL_CD5

*Tabella* – righe: 0
– change data della tabella `CVNUL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CVNUL_CODCONF | CHAR(11) | N |  |
| 6 | CVNUL_PROGMOV | SMALLINT | N |  |
| 7 | CVNUL_CODPROD | CHAR(2) | N |  |
| 8 | CVNUL_TIPOPER | CHAR(2) | N |  |
| 9 | CVNUL_IMPCVN | DECIMAL(15,2) | N |  |
| 10 | CVNUL_TOTCVN | DECIMAL(15,2) | N |  |
| 11 | CVNUL_DTCVN | DECIMAL(9,0) | N |  |
| 12 | CVNUL_IMPCVNPU | DECIMAL(15,2) | N |  |
| 13 | CVNUL_TOTCVNPU | DECIMAL(15,2) | N |  |

Indici:

- `ASN_CVNUL_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_CVN_CD5

*Tabella* – righe: 0
– change data della tabella `CVN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CVN_CODCONF | CHAR(11) | N |  |
| 6 | CVN_PROGMOV | SMALLINT | N |  |
| 7 | CVN_CODPROD | CHAR(2) | N |  |
| 8 | CVN_TIPOPER | CHAR(2) | N |  |
| 9 | CVN_IMPCVN | DECIMAL(13,0) | N |  |
| 10 | CVN_APPLCVN | DECIMAL(13,0) | N |  |
| 11 | CVN_TOTCVN | DECIMAL(13,0) | N |  |
| 12 | CVN_DTCVN | DECIMAL(9,0) | N |  |

Indici:

- `ASN_CVN_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_DBEN_CD

*Tabella* – righe: 0
– change data della tabella `DBEN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | DBEN_CODBNK | CHAR(7) | N |  |
| 6 | DBEN_DTBNK | DECIMAL(8,0) | N |  |
| 7 | DBEN_CODVAL | CHAR(3) | N |  |
| 8 | DBEN_VALLOR | DECIMAL(15,4) | N |  |
| 9 | DBEN_CODCAM | CHAR(7) | N |  |
| 10 | DBEN_EURLOR | DECIMAL(15,4) | N |  |
| 11 | DBEN_DATE | DECIMAL(8,0) | N |  |

Indici:

- `DBEND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_DFPORSPI_CD

*Tabella* – righe: 5
– change data della tabella `DFPORSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | DFPORSPI_AGETERM | CHAR(6) | N |  |
| 5 | XDFPORSPI_AGETERM | CHAR(6) |  |  |
| 6 | DFPORSPI_AGEATT | CHAR(6) | N |  |
| 7 | DFPORSPI_AGEDEST | CHAR(6) | N |  |
| 8 | DFPORSPI_CODCONF | CHAR(11) | N |  |
| 9 | XDFPORSPI_CODCONF | CHAR(11) |  |  |
| 10 | DFPORSPI_CODANA | CHAR(12) | N |  |
| 11 | DFPORSPI_CODFIS | CHAR(16) | N |  |
| 12 | DFPORSPI_DTRIASS | DECIMAL(9,0) | N |  |
| 13 | DFPORSPI_VALORIZZ | DECIMAL(15,2) | N |  |
| 14 | DFPORSPI_STATO | CHAR(1) | N |  |
| 15 | DFPORSPI_INDOLD | CHAR(1) | N |  |
| 16 | DFPORSPI_DATFINE | DECIMAL(9,0) | N |  |
| 17 | DFPORSPI_VALRIAS | DECIMAL(15,2) | N |  |
| 18 | DFPORSPI_FRENCO | CHAR(1) | N |  |
| 19 | DFPORSPI_PFCRITICO | CHAR(1) | N |  |
| 20 | DFPORSPI_CODAREA | CHAR(6) | N |  |
| 21 | DFPORSPI_VALORIZ_E | DECIMAL(15,2) | N |  |
| 22 | DFPORSPI_VALRIAS_E | DECIMAL(15,2) | N |  |

Indici:

- `DFPORSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_DFPOR_CD

*Tabella* – righe: 11.649
– change data della tabella `DFPOR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | DFPOR_AGETERM | CHAR(6) | N |  |
| 5 | XDFPOR_AGETERM | CHAR(6) |  |  |
| 6 | DFPOR_AGEATT | CHAR(6) | N |  |
| 7 | DFPOR_AGEDEST | CHAR(6) | N |  |
| 8 | DFPOR_CODCONF | CHAR(11) | N |  |
| 9 | XDFPOR_CODCONF | CHAR(11) |  |  |
| 10 | DFPOR_CODANA | CHAR(12) | N |  |
| 11 | DFPOR_CODFIS | CHAR(16) | N |  |
| 12 | DFPOR_DTRIASS | DECIMAL(9,0) | N |  |
| 13 | XDFPOR_DTRIASS | DECIMAL(9,0) |  |  |
| 14 | DFPOR_VALORIZZ | DECIMAL(15,2) | N |  |
| 15 | DFPOR_STATO | CHAR(1) | N |  |
| 16 | DFPOR_INDOLD | CHAR(1) | N |  |
| 17 | DFPOR_DATFINE | DECIMAL(9,0) | N |  |
| 18 | DFPOR_VALRIAS | DECIMAL(15,2) | N |  |
| 19 | DFPOR_FRENCO | CHAR(1) | N |  |
| 20 | DFPOR_PFCRITICO | CHAR(1) | N |  |
| 21 | DFPOR_CODAREA | CHAR(6) | N |  |
| 22 | DFPOR_VALORIZZ_E | DECIMAL(15,2) | N |  |
| 23 | DFPOR_VALRIAS_E | DECIMAL(15,2) | N |  |

Indici:

- `DFPORD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_DIVI_CD5

*Tabella* – righe: 0
– change data della tabella `DIVI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | DIVI_CODVAL | CHAR(3) | N |  |
| 6 | DIVI_NOMVAL | CHAR(30) | N |  |
| 7 | DIVI_DIVSIG | CHAR(3) | N |  |

Indici:

- `ASN_DIVI_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_DSIA_CD5

*Tabella* – righe: 0
– change data della tabella `DSIA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XDSIA_CODCONF | CHAR(11) |  |  |
| 6 | XDSIA_SUBPROD | CHAR(5) |  |  |
| 7 | DSIA_CODCONF | CHAR(11) | N |  |
| 8 | DSIA_CODPROD | CHAR(2) | N |  |
| 9 | DSIA_SUBPROD | CHAR(5) | N |  |
| 10 | DSIA_GGADDEB | DECIMAL(3,0) | N |  |
| 11 | DSIA_MMADDEB | DECIMAL(3,0) | N |  |
| 12 | DSIA_AAADDEB | DECIMAL(5,0) | N |  |
| 13 | DSIA_DREVOC | DECIMAL(9,0) | N |  |
| 14 | DSIA_PERIOD | SMALLINT | N |  |
| 15 | DSIA_RATA | DECIMAL(15,0) | N |  |
| 16 | DSIA_INCREM | DECIMAL(3,0) | N |  |
| 17 | DSIA_DTINCR | DECIMAL(9,0) | N |  |
| 18 | DSIA_POSMAND | CHAR(2) | N |  |
| 19 | DSIA_GGACCRE | DECIMAL(3,0) | N |  |
| 20 | DSIA_MMACCRE | DECIMAL(3,0) | N |  |
| 21 | DSIA_AAACCRE | DECIMAL(5,0) | N |  |
| 22 | DSIA_DACQUIS | DECIMAL(9,0) | N |  |
| 23 | DSIA_DVALID | DECIMAL(9,0) | N |  |
| 24 | DSIA_STATUS | CHAR(1) | N |  |
| 25 | DSIA_DTPROSADD | DECIMAL(9,0) |  |  |
| 26 | DSIA_NUM_RATE | DECIMAL(3,0) | N |  |
| 27 | DSIA_MESI_INCREM | DECIMAL(2,0) | N |  |
| 28 | DSIA_CAUREV | CHAR(10) | N |  |
| 29 | DSIA_RATADIV | DECIMAL(15,2) | N |  |
| 30 | DSIA_RATAEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_DSIA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ECAB_CD5

*Tabella* – righe: 0
– change data della tabella `ECAB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ECAB_ABI | CHAR(5) | N |  |
| 6 | ECAB_CAB | CHAR(5) | N |  |
| 7 | ECAB_DTFIN | INTEGER | N |  |
| 8 | ECAB_INDIR | CHAR(80) | N |  |
| 9 | ECAB_CAP | CHAR(5) | N |  |
| 10 | ECAB_COMUN | CHAR(40) | N |  |
| 11 | ECAB_PROV | CHAR(2) | N |  |
| 12 | ECAB_DTINI | INTEGER | N |  |
| 13 | ECAB_TIPMOD | CHAR(1) | N |  |
| 14 | ECAB_STATO | CHAR(1) | N |  |
| 15 | ECAB_FRAZIO | CHAR(40) | N |  |
| 16 | ECAB_LOCAL | CHAR(40) | N |  |

Indici:

- `ASN_ECAB_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ENCB_CD5

*Tabella* – righe: 0
– change data della tabella `ENCB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XENCB_ABI | CHAR(5) |  |  |
| 6 | ENCB_ABI | CHAR(5) | N |  |
| 7 | ENCB_TIPO | CHAR(2) | N |  |
| 8 | ENCB_DTINI | INTEGER | N |  |
| 9 | ENCB_DTFIN | INTEGER | N |  |
| 10 | ENCB_DENOM | CHAR(80) | N |  |
| 11 | ENCB_STATO | CHAR(1) | N |  |
| 12 | ENCB_SIA | CHAR(1) | N |  |
| 13 | ENCB_ABINEW | CHAR(5) | N |  |
| 14 | ENCB_DTREVOC | INTEGER | N |  |

Indici:

- `ASN_ENCB_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_FFOI_CD5

*Tabella* – righe: 0
– change data della tabella `FFOI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | FFOI_CODCONF | CHAR(11) | N |  |
| 6 | FFOI_CODPROD | CHAR(2) | N |  |
| 7 | FFOI_SPSSERV | DECIMAL(13,0) | N |  |
| 8 | FFOI_TOTCVN | DECIMAL(13,0) | N |  |
| 9 | FFOI_CODBLC | CHAR(1) | N |  |
| 10 | FFOI_IMPDIFF | DECIMAL(13,0) | N |  |
| 11 | FFOI_IMPUTIL | DECIMAL(13,0) | N |  |
| 12 | FFOI_CONTRTIPO | CHAR(1) | N |  |
| 13 | FFOI_INDRGM | CHAR(1) | N |  |
| 14 | FFOI_DATRGM | DECIMAL(9,0) | N |  |
| 15 | FFOI_IMPDIFFEURO | DECIMAL(15,2) | N |  |
| 16 | FFOI_RETE | CHAR(1) | N |  |
| 17 | FFOI_PROVTIPO | CHAR(1) |  |  |
| 18 | FFOI_RATATIP | CHAR(1) |  |  |
| 19 | FFOI_DULTMOV | DECIMAL(9,0) |  |  |
| 20 | FFOI_AGEVTIPO | CHAR(1) |  |  |
| 21 | FFOI_DTCONEURO | DECIMAL(9,0) |  |  |
| 22 | FFOI_CODDIV | CHAR(3) |  |  |
| 23 | FFOI_DECTRIM | DECIMAL(9,0) |  |  |
| 24 | FFOI_DATCMS | DECIMAL(9,0) |  |  |
| 25 | FFOI_SPSSEREU | DECIMAL(13,2) |  |  |
| 26 | FFOI_TOTCVNEU | DECIMAL(13,2) |  |  |
| 27 | FFOI_IMPUTILEU | DECIMAL(13,2) |  |  |
| 28 | FFOI_DATBLC | DECIMAL(9,0) |  |  |
| 29 | FFOI_CODPIANO | CHAR(20) | N |  |
| 30 | FFOI_NRATEP | DECIMAL(15,3) | N |  |
| 31 | FFOI_NRATEV | DECIMAL(15,3) | N |  |
| 32 | FFOI_PRCESE | DECIMAL(3,0) | N |  |
| 33 | FFOI_FMIGR | CHAR(2) | N |  |

Indici:

- `ASN_FFOI_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_FFUL_CD5

*Tabella* – righe: 0
– change data della tabella `FFUL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | FFUL_CODCONF | CHAR(11) | N |  |
| 5 | FFUL_CODPROD | CHAR(2) | N |  |
| 6 | FFUL_TARSPS | CHAR(1) | N |  |
| 7 | FFUL_GARMIN | DECIMAL(15,2) | N |  |
| 8 | FFUL_CODBLC | CHAR(1) | N |  |
| 9 | FFUL_RATATIP | CHAR(1) | N |  |
| 10 | FFUL_TASSE | DECIMAL(15,2) | N |  |
| 11 | FFUL_PREMIO_NETTO | DECIMAL(15,2) | N |  |
| 12 | FFUL_PREMIO_PURO | DECIMAL(15,2) | N |  |
| 13 | FFUL_DURANNI | SMALLINT | N |  |
| 14 | FFUL_RATAFRZ | SMALLINT | N |  |
| 15 | FFUL_INDBENV | CHAR(1) | N |  |
| 16 | FFUL_INDBENM | CHAR(1) | N |  |
| 17 | FFUL_DECPOL | DECIMAL(9,0) | N |  |
| 18 | FFUL_DSCADENZA | DECIMAL(9,0) | N |  |
| 19 | FFUL_PRANTOT | DECIMAL(15,2) | N |  |
| 20 | FFUL_IMPDIFF | DECIMAL(15,2) | N |  |
| 21 | FFUL_TOTCVN | DECIMAL(15,2) | N |  |
| 22 | FFUL_PRECONTO | DECIMAL(15,2) | N |  |
| 23 | FFUL_CONTRTIPO | CHAR(1) | N |  |
| 24 | FFUL_ETA | CHAR(3) | N |  |
| 25 | FFUL_PERCARPN | DECIMAL(5,2) | N |  |
| 26 | FFUL_NUMPOL | CHAR(7) | N |  |
| 27 | FFUL_PERC_REND | DECIMAL(3,0) | N |  |
| 28 | FFUL_CODLAV | CHAR(2) | N |  |
| 29 | FFUL_CODFP | CHAR(4) | N |  |
| 30 | FFUL_DTCONTRDIFF | DECIMAL(9,0) | N |  |
| 31 | FFUL_DTEMIPOL | DECIMAL(9,0) | N |  |
| 32 | FFUL_CAPITALE | DECIMAL(15,2) | N |  |
| 33 | FFUL_DURATA_PIANO | SMALLINT | N |  |
| 34 | FFUL_VALORE_PIANO | DECIMAL(15,2) | N |  |
| 35 | FFUL_DTCONV | DECIMAL(9,0) | N |  |
| 36 | FFUL_PREMIOUNICO | DECIMAL(15,2) | N |  |
| 37 | FFUL_CAPITALE_PU | DECIMAL(15,2) | N |  |
| 38 | FFUL_PERCCARAS | DECIMAL(5,2) | N |  |
| 39 | FFUL_PERCCARPU | DECIMAL(5,2) | N |  |
| 40 | FFUL_LINEAINV | CHAR(2) | N |  |
| 41 | FFUL_SBIPRO | DECIMAL(15,2) | N |  |
| 42 | FFUL_TOTCVN_TRASF | DECIMAL(15,2) | N |  |
| 43 | FFUL_NUMPOLBF | CHAR(11) | N | NUMERO POLIZZA DI 11 CARATTERI |
| 44 | FFUL_CAPGAR | DECIMAL(15,2) | N |  |
| 45 | FFUL_PRODEST | CHAR(5) | N |  |
| 46 | FFUL_STATOPOL | CHAR(5) | N |  |
| 47 | FFUL_IMPCAP | DECIMAL(15,2) | N | IMP.CAPITALE A SCADENZA |
| 48 | FFUL_IMPREND | DECIMAL(11,2) | N | IMP.RENDITA A SCADENZA |
| 49 | FFUL_BONUS | DECIMAL(15,2) | N | WELCOME BONUS |
| 50 | FFUL_CLASSE | CHAR(2) | N | CLASSE FREE ENTRY - EXIT |
| 51 | FFUL_DTSCAOLD | DECIMAL(9,0) |  |  |
| 52 | FFUL_DTSCAEFF | DECIMAL(9,0) |  |  |
| 53 | FFUL_PIANO_VERS | DECIMAL(15,2) | N |  |
| 54 | FFUL_NCAMLIN | DECIMAL(3,0) | N |  |
| 55 | FFUL_NSWITCH | DECIMAL(3,0) | N |  |
| 56 | FFUL_TOTCVN_DECUM | DECIMAL(15,2) | N |  |
| 57 | FFUL_DTCVNDEC | DECIMAL(9,0) | N |  |
| 58 | FFUL_OPZDEC | CHAR(1) | N |  |
| 59 | FFUL_RIALLOCAZIONE | CHAR(5) | N |  |
| 60 | FFUL_COPERTURA_CM | CHAR(1) |  |  |
| 61 | FFUL_DT_MBONUS | DECIMAL(9,0) | N |  |
| 62 | FFUL_CLASSE_FINT | CHAR(2) | N |  |
| 63 | FFUL_CLASSE_FEST | CHAR(2) | N |  |
| 64 | FFUL_DT_BLOCCO | DECIMAL(9,0) | N |  |

Indici:

- `ASN_FFUL_IX5` (non unico): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_FVOC1_CD

*Tabella* – righe: 0
– change data della tabella `FVOC1`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | FVOC1_VOC3 | CHAR(3) | N |  |
| 5 | FVOC1_TIPO | CHAR(7) | N |  |
| 6 | FVOC1_ATTIVITA | CHAR(1) | N |  |
| 7 | FVOC1_BOLLO | CHAR(1) | N |  |
| 8 | FVOC1_CAUSALE | CHAR(1) | N |  |
| 9 | FVOC1_CAUDESCR | CHAR(60) | N |  |

Indici:

- `FVOC1D01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_FVOC2_CD

*Tabella* – righe: 0
– change data della tabella `FVOC2`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | FVOC2_VOC3 | CHAR(3) | N |  |
| 5 | FVOC2_SEGNO | CHAR(1) | N |  |
| 6 | FVOC2_VOCTOT | CHAR(3) | N |  |

Indici:

- `FVOC2D01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GARASS_CD

*Tabella* – righe: 0
– change data della tabella `GARASS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | GARASS_CODCONF | CHAR(11) | N |  |
| 5 | GARASS_CODPROD | CHAR(2) | N |  |
| 6 | GARASS_GARANZIA | CHAR(5) | N |  |
| 7 | GARASS_POS_ASSICURATO | CHAR(2) | N |  |
| 8 | GARASS_PERCGAR | DECIMAL(5,2) | N |  |
| 9 | GARASS_MASSIMALE | DECIMAL(13,2) | N |  |
| 10 | GARASS_PREMIO_LORDO_ANNUO | DECIMAL(13,2) | N |  |
| 11 | GARASS_PREMIO_NETTO_ANNUO | DECIMAL(13,2) | N |  |
| 12 | GARASS_IMPOSTE_PREMIO_ANNUO | DECIMAL(13,2) | N |  |
| 13 | GARASS_IMP_PREST_LORDO | DECIMAL(13,2) | N |  |
| 14 | GARASS_IMP_PREST_NETTO | DECIMAL(13,2) | N |  |
| 15 | GARASS_IMPOSTE_PRESTAZ | DECIMAL(13,2) | N |  |
| 16 | GARASS_PREMIO_LORDO_MENSILE | DECIMAL(13,2) | N |  |
| 17 | GARASS_PREMIO_NETTO_MENSILE | DECIMAL(13,2) | N |  |
| 18 | GARASS_IMPOSTE_MENSILI | DECIMAL(13,2) | N |  |

Indici:

- `GARASSD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GARD_CD5

*Tabella* – righe: 0
– change data della tabella `GARD` (FJBM: TABELLA GARANZIE FIDEURAM ASSICURAZIONI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | GARD_CODCONF | CHAR(11) | N |  |
| 6 | GARD_RAMO | CHAR(2) | N |  |
| 7 | GARD_NUMPOL | CHAR(10) | N |  |
| 8 | GARD_CODAGE | CHAR(6) | N |  |
| 9 | GARD_TIPGAR | CHAR(5) | N |  |
| 10 | GARD_PROGASS | DECIMAL(3,0) | N |  |
| 11 | GARD_NOMASS | CHAR(30) | N |  |
| 12 | GARD_TIPASS | CHAR(1) | N |  |
| 13 | GARD_CAPASS | DECIMAL(15,0) | N |  |
| 14 | GARD_DTAGG | DECIMAL(9,0) | N |  |
| 15 | GARD_CAEURO | DECIMAL(15,2) |  |  |

Indici:

- `ASN_GARD_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GCF_CD5

*Tabella* – righe: 0
– change data della tabella `GCF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | GCF_CODCONF | CHAR(11) | N |  |
| 6 | GCF_CODPROD | CHAR(2) | N |  |
| 7 | GCF_TIPOPER | CHAR(2) | N |  |
| 8 | GCF_ABI | CHAR(5) | N |  |
| 9 | GCF_CAB | CHAR(5) | N |  |
| 10 | GCF_CONTO | CHAR(12) | N |  |
| 11 | GCF_CODCAU | CHAR(2) | N |  |
| 12 | GCF_CODCONFR | CHAR(11) | N |  |
| 13 | GCF_IMP | DECIMAL(13,0) | N |  |
| 14 | GCF_PROGPAG | SMALLINT | N |  |
| 15 | GCF_SUBPROD | CHAR(5) | N |  |
| 16 | GCF_DACQUIS | DECIMAL(9,0) | N |  |
| 17 | GCF_IMPOPAG | DECIMAL(15,2) | N |  |
| 18 | GCF_IMPEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_GCF_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GPFRANGE_CD

*Tabella* – righe: 0
– change data della tabella `GPFRANGE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | GPFRANGE_CODPROD | CHAR(2) | N |  |
| 5 | GPFRANGE_RETE | CHAR(3) | N |  |
| 6 | GPFRANGE_INIZIOMOD | CHAR(11) | N |  |
| 7 | GPFRANGE_FINEMOD | CHAR(11) | N |  |
| 8 | GPFRANGE_DTINIZIO | DECIMAL(9,0) | N |  |
| 9 | GPFRANGE_DTFINE | DECIMAL(9,0) | N |  |
| 10 | GPFRANGE_LINEAINV | CHAR(1) | N |  |
| 11 | GPFRANGE_DESCR | CHAR(25) | N |  |
| 12 | GPFRANGE_DSCATRA | DECIMAL(9,0) | N |  |
| 13 | GPFRANGE_DINITRA | DECIMAL(9,0) | N |  |
| 14 | GPFRANGE_DINISOT | DECIMAL(9,0) | N |  |
| 15 | GPFRANGE_DSCASOT | DECIMAL(9,0) | N |  |
| 16 | GPFRANGE_DINISTART | DECIMAL(9,0) | N |  |
| 17 | GPFRANGE_DSCASTART | DECIMAL(9,0) | N |  |
| 18 | GPFRANGE_PERCPROT | DECIMAL(5,2) | N |  |
| 19 | GPFRANGE_SUBPROD | CHAR(5) | N |  |

Indici:

- `GPFRANGED01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GPLINEA_CD

*Tabella* – righe: 12
– change data della tabella `GPLINEA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | GPLINEA_CODCONF | CHAR(11) | N |  |
| 5 | XGPLINEA_CODCONF | CHAR(11) |  |  |
| 6 | GPLINEA_CODPROD | CHAR(2) | N |  |
| 7 | GPLINEA_SUBPROD | CHAR(5) | N |  |
| 8 | XGPLINEA_SUBPROD | CHAR(5) |  |  |
| 9 | GPLINEA_LINEA | CHAR(1) | N |  |
| 10 | XGPLINEA_LINEA | CHAR(1) |  |  |
| 11 | GPLINEA_DTINIZIO | DECIMAL(9,0) | N |  |
| 12 | XGPLINEA_DTINIZIO | DECIMAL(9,0) |  |  |
| 13 | GPLINEA_DTFINE | DECIMAL(9,0) | N |  |
| 14 | XGPLINEA_DTFINE | DECIMAL(9,0) |  |  |

Indici:

- `GPLINEAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GPMMOV_CD

*Tabella* – righe: 0
– change data della tabella `GPMMOV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | GPMMOV_CODCONF | CHAR(11) | N |  |
| 5 | XGPMMOV_CODCONF | CHAR(11) |  |  |
| 6 | GPMMOV_CODPROD | CHAR(2) | N |  |
| 7 | XGPMMOV_CODPROD | CHAR(2) |  |  |
| 8 | GPMMOV_SUBPROD | CHAR(5) | N |  |
| 9 | XGPMMOV_SUBPROD | CHAR(5) |  |  |
| 10 | GPMMOV_TIPOPER | CHAR(2) | N |  |
| 11 | GPMMOV_TIPOPES | CHAR(2) | N |  |
| 12 | GPMMOV_ISIN | CHAR(12) | N |  |
| 13 | XGPMMOV_ISIN | CHAR(12) |  |  |
| 14 | GPMMOV_CAUSALE | CHAR(4) | N |  |
| 15 | XGPMMOV_CAUSALE | CHAR(4) |  |  |
| 16 | GPMMOV_DTVAL | DECIMAL(9,0) | N |  |
| 17 | GPMMOV_DATANAV | DECIMAL(9,0) | N |  |
| 18 | GPMMOV_DTOPER | DECIMAL(9,0) | N |  |
| 19 | GPMMOV_DELABOR | DECIMAL(9,0) | N |  |
| 20 | GPMMOV_DVALORIZ | DECIMAL(9,0) | N |  |
| 21 | XGPMMOV_DVALORIZ | DECIMAL(9,0) |  |  |
| 22 | GPMMOV_AREAFIN | CHAR(11) | N |  |
| 23 | GPMMOV_QTA | DECIMAL(15,3) | N |  |
| 24 | GPMMOV_CTRVNETTO | DECIMAL(15,2) | N |  |
| 25 | GPMMOV_CCAL | DECIMAL(3,0) | N |  |
| 26 | GPMMOV_CODDIV | CHAR(3) | N |  |
| 27 | GPMMOV_CAMBIO | DECIMAL(15,5) | N |  |
| 28 | GPMMOV_NOPER | CHAR(8) | N |  |
| 29 | XGPMMOV_NOPER | CHAR(8) |  |  |
| 30 | GPMMOV_MAF | CHAR(14) | N |  |
| 31 | GPMMOV_CODINT | CHAR(5) | N |  |
| 32 | GPMMOV_PREZZO | DECIMAL(15,3) | N |  |
| 33 | GPMMOV_RETE | CHAR(1) | N |  |
| 34 | GPMMOV_BASKET | CHAR(5) | N |  |
| 35 | GPMMOV_PROGR | DECIMAL(5,0) |  |  |
| 36 | XGPMMOV_PROGR | DECIMAL(5,0) |  |  |

Indici:

- `GPMMOVD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GPMSAL_CD

*Tabella* – righe: 0
– change data della tabella `GPMSAL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | GPMSAL_CODCONF | CHAR(11) | N |  |
| 5 | XGPMSAL_CODCONF | CHAR(11) |  |  |
| 6 | GPMSAL_CODPROD | CHAR(2) | N |  |
| 7 | XGPMSAL_CODPROD | CHAR(2) |  |  |
| 8 | GPMSAL_SUBPROD | CHAR(5) | N |  |
| 9 | XGPMSAL_SUBPROD | CHAR(5) |  |  |
| 10 | GPMSAL_AREAFIN | CHAR(11) | N |  |
| 11 | XGPMSAL_AREAFIN | CHAR(11) |  |  |
| 12 | GPMSAL_ISIN | CHAR(12) | N |  |
| 13 | GPMSAL_STATO | CHAR(1) | N |  |
| 14 | GPMSAL_DESCR | CHAR(20) | N |  |
| 15 | GPMSAL_ENT | CHAR(3) | N |  |
| 16 | GPMSAL_GRP | CHAR(3) | N |  |
| 17 | GPMSAL_SGRP | CHAR(3) | N |  |
| 18 | GPMSAL_DTSCATIT | DECIMAL(9,0) | N |  |
| 19 | GPMSAL_QTA | DECIMAL(15,3) | N |  |
| 20 | GPMSAL_CODDIVEMI | CHAR(3) | N |  |
| 21 | GPMSAL_CAMBIO | DECIMAL(15,5) | N |  |
| 22 | GPMSAL_DTCAMBIO | DECIMAL(9,0) | N |  |
| 23 | GPMSAL_PREZZOMED | DECIMAL(15,3) | N |  |
| 24 | GPMSAL_PREZZO | DECIMAL(15,3) | N |  |
| 25 | GPMSAL_DATANAV | DECIMAL(9,0) | N |  |
| 26 | GPMSAL_FQUOT | CHAR(1) | N |  |
| 27 | GPMSAL_IMPCED | DECIMAL(15,2) | N |  |
| 28 | GPMSAL_DTSCACED | DECIMAL(9,0) | N |  |
| 29 | GPMSAL_PERCED | CHAR(1) | N |  |
| 30 | GPMSAL_CTRVIMPLIQ | DECIMAL(15,2) | N |  |
| 31 | GPMSAL_RATEO | DECIMAL(15,2) | N |  |
| 32 | GPMSAL_CCAL | DECIMAL(3,0) | N |  |
| 33 | GPMSAL_TIPSAL | CHAR(3) | N |  |
| 34 | GPMSAL_COEFFIND | DECIMAL(15,9) | N |  |
| 35 | GPMSAL_RETE | CHAR(1) | N |  |
| 36 | GPMSAL_DVALORIZ | DECIMAL(9,0) | N |  |
| 37 | GPMSAL_MAF | CHAR(14) | N |  |
| 38 | XGPMSAL_MAF | CHAR(14) |  |  |
| 39 | GPMSAL_MERCATO | CHAR(6) | N | MERCATO |
| 40 | XGPMSAL_MERCATO | CHAR(6) |  |  |
| 41 | XGPMSAL_ISIN | CHAR(12) |  |  |
| 42 | GPMSAL_TIPO | CHAR(5) | N | CODICE SUBPROD |
| 43 | GPMSAL_PREZZO_MAX | DECIMAL(15,3) |  |  |
| 44 | GPMSAL_DTPREZZO_MAX | DECIMAL(9,0) |  |  |
| 45 | GPMSAL_PREZZO_PROT | DECIMAL(15,3) |  |  |
| 46 | GPMSAL_CTRVIMPPROT | DECIMAL(15,3) |  |  |
| 47 | GPMSAL_BASKET | CHAR(5) |  |  |
| 48 | XGPMSAL_BASKET | CHAR(5) |  |  |

Indici:

- `GPMSALD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_GSEP_CD

*Tabella* – righe: 0
– change data della tabella `GSEP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | GSEP_CODGS | CHAR(5) | N |  |
| 6 | GSEP_DESCR | CHAR(50) | N |  |
| 7 | GSEP_DESC_BREVE | CHAR(24) | N |  |
| 8 | GSEP_SALDOQ | DECIMAL(15,3) |  |  |
| 9 | GSEP_DTAP | DATE | N |  |
| 10 | GSEP_DTCH | DATE | N |  |
| 11 | GSEP_ELBOINS | INTEGER |  |  |
| 12 | GSEP_ELBOAGG | INTEGER |  |  |
| 13 | GSEP_CODFAM | CHAR(1) | N |  |
| 14 | GSEP_SALDOQ_COL | DECIMAL(15,3) | N |  |

Indici:

- `GSEPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_IVA_CD

*Tabella* – righe: 0
– change data della tabella `IVA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | IVA_VOCTOT | CHAR(3) | N |  |
| 5 | IVA_PERC | DECIMAL(7,5) | N |  |
| 6 | IVA_VOCIVA | CHAR(3) | N |  |

Indici:

- `IVAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_IVFD_CD5

*Tabella* – righe: 0
– change data della tabella `IVFD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | IVFD_CODCONF | CHAR(11) | N |  |
| 6 | IVFD_CODPROD | CHAR(2) | N |  |
| 7 | IVFD_ANNO | DECIMAL(5,0) | N |  |
| 8 | IVFD_IMPVERS | DECIMAL(15,3) | N |  |
| 9 | IVFD_IMPVERSEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_IVFD_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_KEYSPI_CD

*Tabella* – righe: 0
– change data della tabella `KEYSPI` (FJBM: RELAZIONE CHIAVI DEL CONTRATTO B.F. E SPI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 5 | KEYSPI_CODCONF | CHAR(11) | N |  |
| 6 | KEYSPI_CODPROD | CHAR(2) | N |  |
| 7 | KEYSPI_SUBPROD | CHAR(5) | N |  |
| 8 | KEYSPI_POSCONF | CHAR(20) | N |  |
| 9 | KEYSPI_PRODGEN | CHAR(4) | N |  |
| 10 | KEYSPI_PRODSPE | CHAR(4) | N |  |
| 11 | KEYSPI_PRDCSPI | CHAR(10) | N |  |
| 12 | KEYSPI_CODCONF_BF | CHAR(11) | N |  |
| 13 | KEYSPI_CODPROD_BF | CHAR(2) | N |  |
| 14 | KEYSPI_SUBPROD_BF | CHAR(5) | N |  |
| 15 | KEYSPI_POSIZIONE | CHAR(20) | N |  |

Indici:

- `KEYSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MDIR_CD

*Tabella* – righe: 0
– change data della tabella `MDIR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MDIR_FASCINI | DECIMAL(15,2) | N |  |
| 5 | MDIR_FASCFIN | DECIMAL(15,2) | N |  |
| 6 | MDIR_PERC | DECIMAL(9,5) | N |  |
| 7 | MDIR_DVALINI | DECIMAL(9,0) | N |  |
| 8 | MDIR_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | MDIR_TIPCOM | CHAR(2) | N |  |
| 10 | MDIR_FASCINI_EURO | DECIMAL(15,2) | N |  |
| 11 | MDIR_FASCFIN_EURO | DECIMAL(15,2) | N |  |
| 12 | MDIR_RETE | CHAR(1) | N |  |
| 13 | MDIR_INDBC | CHAR(2) | N |  |
| 14 | MDIR_REGDIS | CHAR(4) | N |  |

Indici:

- `MDIRD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MFSFDT_CD

*Tabella* – righe: 0
– change data della tabella `MFSFDT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MFSFDT_NOMEFLU | CHAR(8) | N |  |
| 5 | MFSFDT_CODPROD | CHAR(2) | N |  |
| 6 | MFSFDT_SUBPROD | CHAR(5) | N |  |
| 7 | MFSFDT_ISIN | CHAR(12) | N |  |
| 8 | MFSFDT_DATCOM | DECIMAL(7,0) | N |  |
| 9 | MFSFDT_DVALUTA | DECIMAL(9,0) | N |  |
| 10 | MFSFDT_PAYIN | DECIMAL(15,2) | N |  |
| 11 | MFSFDT_PATRIMONIO | DECIMAL(15,2) | N |  |
| 12 | MFSFDT_REGIMP | DECIMAL(15,2) | N |  |
| 13 | MFSFDT_STATO | CHAR(1) | N |  |
| 14 | MFSFDT_RETE | CHAR(1) | N |  |
| 15 | MFSFDT_PERC_COMLOR | DECIMAL(5,3) | N |  |
| 16 | MFSFDT_PERC_REBA | DECIMAL(5,3) | N |  |
| 17 | MFSFDT_DTCONTAB | DECIMAL(9,0) | N |  |
| 18 | MFSFDT_DTINV | DECIMAL(9,0) | N |  |
| 19 | MFSFDT_DTVALID_PI | DECIMAL(9,0) | N |  |
| 20 | MFSFDT_KEY | INTEGER | N |  |
| 21 | MFSFDT_DTCONTABSPI | DECIMAL(9,0) | N |  |
| 22 | MFSFDT_PAYIN_LORDO | DECIMAL(15,2) | N |  |

Indici:

- `MFSFDTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MFSGR_CD

*Tabella* – righe: 0
– change data della tabella `MFSGR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MFSGR_CODSGR | CHAR(2) | N |  |
| 5 | MFSGR_DESSGR | CHAR(30) | N |  |
| 6 | MFSGR_CODPROD | CHAR(2) | N |  |
| 7 | MFSGR_DVALINI | DECIMAL(9,0) | N |  |
| 8 | MFSGR_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | MFSGR_BASE | CHAR(2) | N |  |
| 10 | MFSGR_PERIOD | DECIMAL(2,0) | N |  |
| 11 | MFSGR_TIPO | CHAR(2) | N |  |
| 12 | MFSGR_FLECCE | CHAR(2) | N |  |

Indici:

- `MFSGRD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MFSPE_CD

*Tabella* – righe: 956
– change data della tabella `MFSPE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MFSPE_CODFON | CHAR(4) | N |  |
| 5 | MFSPE_DATCOM | DECIMAL(7,0) | N |  |
| 6 | MFSPE_DTREG | DECIMAL(9,0) | N |  |
| 7 | MFSPE_REGIMP | DECIMAL(15,2) | N |  |
| 8 | MFSPE_REGIMPSPI | DECIMAL(15,2) | N |  |
| 9 | MFSPE_DATASPE | DECIMAL(9,0) | N |  |
| 10 | MFSPE_REGINVE | DECIMAL(15,2) | N |  |
| 11 | MFSPE_REGSYMPH | DECIMAL(15,2) | N |  |
| 12 | MFSPE_REGALTRO | DECIMAL(15,2) | N |  |
| 13 | MFSPE_ISIN | CHAR(12) | N |  |
| 14 | MFSPE_GPBF | DECIMAL(15,2) | N |  |
| 15 | MFSPE_GPSPI | DECIMAL(15,2) | N |  |
| 16 | MFSPE_REGSYMBF | DECIMAL(15,2) | N |  |
| 17 | MFSPE_SKANDIA | DECIMAL(15,2) | N |  |
| 18 | MFSPE_SKANDIASPI | DECIMAL(15,2) | N |  |
| 19 | MFSPE_PAYINSPI | DECIMAL(15,2) | N |  |
| 20 | MFSPE_DTCONTAB | DECIMAL(9,0) | N |  |
| 21 | MFSPE_DTCONTABSPI | DECIMAL(9,0) | N |  |
| 22 | MFSPE_DATASPE_SPI | DECIMAL(9,0) | N |  |
| 23 | MFSPE_REGIMP_ISPB | DECIMAL(15,2) |  |  |
| 24 | MFSPE_DTCONTAB_ISPB | DECIMAL(9,0) |  |  |
| 25 | MFSPE_DATASPE_ISPB | DECIMAL(9,0) |  |  |

Indici:

- `MFSPED01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MFTUN_CD

*Tabella* – righe: 145.117
– change data della tabella `MFTUN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MFTUN_CODCONF | CHAR(11) | N |  |
| 5 | MFTUN_CODPROD | CHAR(2) | N |  |
| 6 | MFTUN_SUBPROD | CHAR(5) | N |  |
| 7 | MFTUN_ISIN | CHAR(12) | N |  |
| 8 | MFTUN_DATA | DECIMAL(9,0) | N |  |
| 9 | MFTUN_QUOTEPRE | DECIMAL(15,3) | N |  |
| 10 | MFTUN_QUOTETUN | DECIMAL(15,3) | N |  |
| 11 | MFTUN_QUOTEPOST | DECIMAL(15,3) | N |  |
| 12 | MFTUN_QUOTEOUT | DECIMAL(15,3) | N |  |
| 13 | MFTUN_RETE | CHAR(1) | N |  |

Indici:

- `MFTUND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MGPL_CD

*Tabella* – righe: 0
– change data della tabella `MGPL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | MGPL_CODAGE | CHAR(6) | N |  |
| 6 | MGPL_PATRIM_E | DECIMAL(15,2) | N |  |
| 7 | MGPL_PATRNI_E | DECIMAL(15,2) | N |  |
| 8 | MGPL_DATFOTO | DECIMAL(9,0) | N |  |
| 9 | MGPL_INDFTRIM | CHAR(1) | N |  |
| 10 | MGPL_DTABIL | DECIMAL(9,0) | N |  |
| 11 | MGPL_DTREVOC | DECIMAL(9,0) | N |  |
| 12 | MGPL_PATRHF_E | DECIMAL(15,2) | N |  |
| 13 | MGPL_PATSAFE_E | DECIMAL(15,2) | N |  |
| 14 | MGPL_PATFDT_E | DECIMAL(15,2) | N | PATRIMONIO FONDI TERZI ESTERI |
| 15 | MGPL_RETE | CHAR(1) | N | RETE |
| 16 | MGPL_PATMUL_E | DECIMAL(15,2) | N |  |
| 17 | MGPL_MUL_OMEGA | DECIMAL(15,2) | N | PATRIMONIO MULTIMANAGER OMEGA |
| 18 | MGPL_MUL_ALTRE | DECIMAL(15,2) | N | PATRIMONIO MULTIMANAGER ALTRE |
| 19 | MGPL_SAFE_H | DECIMAL(15,2) | N | PATRIMONIO SAFE HIGH   ADVICE |
| 20 | MGPL_SAFE_M | DECIMAL(15,2) | N | PATRIMONIO SAFE MEDIUM ADVICE |
| 21 | MGPL_SAFE_L | DECIMAL(15,2) | N | PATRIMONIO SAFE LOW    ADVICE |
| 22 | MGPL_SAFE_MON | DECIMAL(15,2) | N | PATRIMONIO SAFE MONETARIO |
| 23 | MGPL_FDT_H | DECIMAL(15,2) | N | PATRIMONIO FONDI DI TERZI HIGH ADVICE |
| 24 | MGPL_FDT_M | DECIMAL(15,2) | N | PATRIMON.FONDI DI TERZI MEDIUM ADVICE |
| 25 | MGPL_FDT_L | DECIMAL(15,2) | N | PATRIMONIO FONDI DI TERZI LOW  ADVICE |
| 26 | MGPL_FDT_MON | DECIMAL(15,2) | N | PATRIMONIO FONDI DI TERZI MONETARIO |

Indici:

- `MGPLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MLIV1A_CD

*Tabella* – righe: 1.405.170
– change data della tabella `MLIV1A`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MLIV1A_CODCONF | CHAR(11) | N |  |
| 5 | XMLIV1A_CODCONF | CHAR(11) |  |  |
| 6 | MLIV1A_CODPROD | CHAR(2) | N |  |
| 7 | XMLIV1A_CODPROD | CHAR(2) |  |  |
| 8 | MLIV1A_PROGMOV | DECIMAL(5,0) | N |  |
| 9 | XMLIV1A_PROGMOV | DECIMAL(5,0) |  |  |
| 10 | MLIV1A_COD_LIV3 | CHAR(5) | N |  |
| 11 | MLIV1A_COD_LIV2 | CHAR(5) | N |  |
| 12 | XMLIV1A_COD_LIV2 | CHAR(5) |  |  |
| 13 | MLIV1A_SUBPROD | CHAR(5) | N |  |
| 14 | XMLIV1A_SUBPROD | CHAR(5) |  |  |
| 15 | MLIV1A_PROGOPE | DECIMAL(5,0) | N |  |
| 16 | XMLIV1A_PROGOPE | DECIMAL(5,0) |  |  |
| 17 | MLIV1A_TIPOPER | CHAR(2) | N |  |
| 18 | MLIV1A_TIPOPES | CHAR(2) | N |  |
| 19 | XMLIV1A_TIPOPES | CHAR(2) |  |  |
| 20 | MLIV1A_COD_STATO | CHAR(1) | N |  |
| 21 | MLIV1A_PRC_SUBPROD | DECIMAL(7,3) | N |  |
| 22 | MLIV1A_PRC_CARICAM | DECIMAL(7,3) | N |  |
| 23 | MLIV1A_COD_RETE | CHAR(1) | N |  |
| 24 | MLIV1A_DT_VALFND | DECIMAL(9,0) | N |  |
| 25 | MLIV1A_DT_VALNAV | DECIMAL(9,0) | N |  |
| 26 | MLIV1A_DT_NAVAL | DECIMAL(9,0) | N |  |
| 27 | MLIV1A_IMP_LORDO | DECIMAL(15,2) | N |  |
| 28 | MLIV1A_QUOTE | DECIMAL(15,7) | N |  |
| 29 | MLIV1A_VALNAV | DECIMAL(13,5) | N |  |
| 30 | MLIV1A_IMP_PAYIN_STIM | DECIMAL(15,2) | N |  |
| 31 | MLIV1A_IMP_PAYIN | DECIMAL(15,2) | N |  |
| 32 | MLIV1A_IMP_PAYOUT | DECIMAL(15,2) | N |  |
| 33 | MLIV1A_IMP_PRECONTO | DECIMAL(15,2) | N |  |
| 34 | MLIV1A_IMP_CARICAM | DECIMAL(15,2) | N |  |
| 35 | MLIV1A_IMP_TASSE | DECIMAL(15,2) | N |  |
| 36 | MLIV1A_IMP_SPSLIQ | DECIMAL(15,2) | N |  |
| 37 | MLIV1A_IMP_SPSAMMI | DECIMAL(15,2) | N |  |
| 38 | MLIV1A_IMP_CGEST | DECIMAL(15,2) | N |  |
| 39 | MLIV1A_IMP_CMORTE | DECIMAL(15,2) | N |  |
| 40 | MLIV1A_IMP_PENALI | DECIMAL(15,2) | N |  |
| 41 | MLIV1A_IMP_NETTO | DECIMAL(15,2) | N |  |
| 42 | MLIV1A_IMP_PURO | DECIMAL(15,2) | N |  |
| 43 | MLIV1A_DT_CASSA | DECIMAL(9,0) | N |  |
| 44 | MLIV1A_COD_TRANSAZIONE | CHAR(12) | N |  |
| 45 | MLIV1A_IND_DECUMULO | CHAR(1) | N |  |
| 46 | MLIV1A_IND_NAVRETRO | CHAR(1) | N |  |
| 47 | MLIV1A_IND_BONMATUR | CHAR(1) | N |  |
| 48 | MLIV1A_IND_SALV | CHAR(1) | N |  |
| 49 | MLIV1A_IND_TRASF | CHAR(1) | N |  |
| 50 | MLIV1A_IND_OPUFF | CHAR(1) | N |  |
| 51 | MLIV1A_IND_CONTEST | CHAR(1) | N |  |
| 52 | MLIV1A_IND_RENCO | CHAR(1) | N |  |
| 53 | MLIV1A_DT_RENCO | DECIMAL(9,0) | N |  |
| 54 | MLIV1A_FLUSSOIN | CHAR(8) | N |  |
| 55 | MLIV1A_FLUSSORC | CHAR(8) | N |  |

Indici:

- `MLIV1AD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MOVE_CD

*Tabella* – righe: 0
– change data della tabella `MOVE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MOVE_GRADO | CHAR(4) | N |  |
| 5 | MOVE_PERC | DECIMAL(9,5) | N |  |
| 6 | MOVE_DVALINI | DECIMAL(9,0) | N |  |
| 7 | MOVE_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | MOVE_TIPCOM | CHAR(2) | N |  |
| 9 | MOVE_RETE | CHAR(1) | N |  |
| 10 | MOVE_INDBC | CHAR(2) |  |  |
| 11 | MOVE_REGDIS | CHAR(4) |  |  |

Indici:

- `MOVED01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MOVTIT_CD

*Tabella* – righe: 236.819
– change data della tabella `MOVTIT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MOVTIT_CODCONF | CHAR(11) | N |  |
| 5 | MOVTIT_PROGMOV | SMALLINT | N |  |
| 6 | MOVTIT_DATA | DECIMAL(9,0) | N |  |
| 7 | MOVTIT_NDG | DECIMAL(9,0) | N |  |
| 8 | MOVTIT_CAGEDEP | DECIMAL(5,0) | N |  |
| 9 | MOVTIT_CPRGDEP | DECIMAL(7,0) | N |  |
| 10 | MOVTIT_CSDPDEP | DECIMAL(3,0) | N |  |
| 11 | MOVTIT_CONTO | CHAR(12) | N |  |
| 12 | XMOVTIT_CONTO | CHAR(12) |  |  |
| 13 | MOVTIT_CONTO_REG | CHAR(12) | N |  |
| 14 | MOVTIT_CATEGORIA | CHAR(1) | N |  |
| 15 | MOVTIT_RAGG_DEPO | DECIMAL(3,0) | N |  |
| 16 | MOVTIT_ABI | CHAR(8) | N |  |
| 17 | MOVTIT_ISIN | CHAR(12) | N |  |
| 18 | MOVTIT_DEX_TITOLO | CHAR(20) | N |  |
| 19 | MOVTIT_CENT | DECIMAL(3,0) | N |  |
| 20 | MOVTIT_CGRP | DECIMAL(3,0) | N |  |
| 21 | MOVTIT_CSOTGRP | DECIMAL(3,0) | N |  |
| 22 | MOVTIT_NGG_VITA | DECIMAL(5,0) | N |  |
| 23 | MOVTIT_FLAG_QUOT | CHAR(1) | N |  |
| 24 | MOVTIT_FLG_TITGRP | CHAR(1) | N |  |
| 25 | MOVTIT_CCAL | DECIMAL(3,0) | N |  |
| 26 | MOVTIT_DTSCA_TIT | DECIMAL(9,0) | N |  |
| 27 | MOVTIT_COD_DIVEMI | CHAR(3) | N |  |
| 28 | MOVTIT_COD_DIVTRA | CHAR(3) | N |  |
| 29 | MOVTIT_QTA | DECIMAL(15,3) | N |  |
| 30 | MOVTIT_CAUSALE | CHAR(4) | N |  |
| 31 | MOVTIT_DT_OPERAZ | DECIMAL(9,0) | N |  |
| 32 | MOVTIT_DT_VALUTA | DECIMAL(9,0) | N |  |
| 33 | MOVTIT_PREZZO | DECIMAL(15,5) | N |  |
| 34 | MOVTIT_PREZZOL | DECIMAL(15,5) | N |  |
| 35 | MOVTIT_CAMBIO | DECIMAL(15,5) | N |  |
| 36 | MOVTIT_TIPO_OPERAZ | CHAR(8) | N |  |
| 37 | MOVTIT_TIPO_PREMIO | CHAR(8) | N |  |
| 38 | MOVTIT_BASE_PREMIO | DECIMAL(15,5) | N |  |
| 39 | MOVTIT_MESE_PREMIO | DECIMAL(3,0) | N |  |
| 40 | MOVTIT_ANNO_PREMIO | DECIMAL(5,0) | N |  |
| 41 | MOVTIT_FLAG_STORNO | CHAR(1) | N |  |
| 42 | MOVTIT_NREGTER | CHAR(8) | N |  |
| 43 | XMOVTIT_NREGTER | CHAR(8) |  |  |
| 44 | MOVTIT_NREGANN | DECIMAL(3,0) | N |  |
| 45 | XMOVTIT_NREGANN | DECIMAL(3,0) |  |  |
| 46 | MOVTIT_NREGNUM | DECIMAL(9,0) | N |  |
| 47 | XMOVTIT_NREGNUM | DECIMAL(9,0) |  |  |
| 48 | MOVTIT_NREGSNR | DECIMAL(5,0) | N |  |
| 49 | XMOVTIT_NREGSNR | DECIMAL(5,0) |  |  |
| 50 | MOVTIT_NREGTER_ST | CHAR(8) | N |  |
| 51 | MOVTIT_NREGANN_ST | DECIMAL(3,0) | N |  |
| 52 | MOVTIT_NREGNUM_ST | DECIMAL(9,0) | N |  |
| 53 | MOVTIT_NREGSNR_ST | DECIMAL(5,0) | N |  |
| 54 | MOVTIT_FLG_INTERN | CHAR(1) | N |  |
| 55 | MOVTIT_COM_ATTIVE | DECIMAL(15,2) | N |  |
| 56 | MOVTIT_COM_PASSIVE | DECIMAL(15,2) | N |  |
| 57 | MOVTIT_PAYIN | DECIMAL(15,2) | N |  |
| 58 | MOVTIT_PAYOUT | DECIMAL(15,2) | N |  |
| 59 | MOVTIT_CTV_NETTO | DECIMAL(15,2) | N |  |
| 60 | MOVTIT_CTV_NETDIV | DECIMAL(15,2) | N |  |
| 61 | MOVTIT_CTV_RATEO | DECIMAL(15,2) | N |  |
| 62 | MOVTIT_CTV_IMPSOST | DECIMAL(15,2) | N |  |
| 63 | MOVTIT_CTV_SPEACC | DECIMAL(15,2) | N |  |
| 64 | MOVTIT_PCONTAS | DECIMAL(5,3) | N |  |
| 65 | MOVTIT_CPAE | CHAR(3) | N |  |
| 66 | MOVTIT_CPZA | CHAR(2) | N |  |
| 67 | MOVTIT_PRZ_RACNET | DECIMAL(15,5) | N |  |
| 68 | MOVTIT_CTV_RACNET | DECIMAL(15,2) | N |  |
| 69 | MOVTIT_STATO | CHAR(1) | N |  |
| 70 | MOVTIT_FIL_OPER | DECIMAL(5,0) | N |  |
| 71 | MOVTIT_RETE | CHAR(1) | N |  |
| 72 | MOVTIT_IND_RIMB | CHAR(2) | N |  |
| 73 | MOVTIT_IND_OBLOT | CHAR(1) | N |  |
| 74 | MOVTIT_VAL_LOTTO | DECIMAL(15,3) | N |  |
| 75 | MOVTIT_COEFF_DEC | DECIMAL(11,9) | N |  |
| 76 | MOVTIT_RUBRICAT | CHAR(3) | N |  |
| 77 | MOVTIT_COMM_CONTR | DECIMAL(15,3) | N |  |

Indici:

- `MOVTITD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MPAY_CD5

*Tabella* – righe: 0
– change data della tabella `MPAY`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XMPAY_PAYIN | DECIMAL(13,0) |  |  |
| 6 | XMPAY_PAYOUT | DECIMAL(13,0) |  |  |
| 7 | MPAY_CODCONF | CHAR(11) | N |  |
| 8 | MPAY_SUBPROD | CHAR(5) | N |  |
| 9 | MPAY_PROGMOV | SMALLINT | N |  |
| 10 | MPAY_PROGOPE | SMALLINT | N |  |
| 11 | MPAY_TIPOPER | CHAR(2) | N |  |
| 12 | MPAY_TIPOPES | CHAR(2) | N |  |
| 13 | MPAY_PAYIN | DECIMAL(13,0) | N |  |
| 14 | MPAY_PAYOUT | DECIMAL(13,0) | N |  |
| 15 | MPAY_PROGPAY | SMALLINT | N |  |
| 16 | MPAY_CODPROD | CHAR(2) |  |  |
| 17 | MPAY_TIPOPAY | CHAR(4) |  |  |
| 18 | MPAY_IMPOPER | DECIMAL(13,0) |  |  |
| 19 | MPAY_IMPCMS | DECIMAL(13,0) |  |  |
| 20 | MPAY_DTPAYO | DECIMAL(9,0) |  |  |
| 21 | MPAY_RFP | DECIMAL(15,2) |  |  |
| 22 | MPAY_DTRFP | DECIMAL(9,0) |  |  |
| 23 | MPAY_IMPEURO | DECIMAL(13,2) |  |  |
| 24 | MPAY_IMPCMSEU | DECIMAL(13,2) |  |  |
| 25 | MPAY_PAYINEU | DECIMAL(13,2) |  |  |
| 26 | MPAY_PAYOUEU | DECIMAL(13,2) |  |  |
| 27 | MPAY_RFPEURO | DECIMAL(15,2) |  |  |
| 28 | XMPAY_CODCONF | CHAR(11) |  |  |
| 29 | XMPAY_CODPROD | CHAR(2) |  |  |
| 30 | XMPAY_SUBPROD | CHAR(5) |  |  |
| 31 | XMPAY_PROGMOV | SMALLINT |  |  |
| 32 | XMPAY_PROGOPE | SMALLINT |  |  |
| 33 | XMPAY_PROGPAY | SMALLINT |  |  |
| 34 | XMPAY_TIPOPES | CHAR(2) |  |  |

Indici:

- `ASN_MPAY_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_MRFA_CD

*Tabella* – righe: 0
– change data della tabella `MRFA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | MRFA_CODAGE | CHAR(6) | N |  |
| 5 | MRFA_CODANA | CHAR(12) | N |  |
| 6 | MRFA_DATAGG | DECIMAL(9,0) | N |  |
| 7 | MRFA_IMPRFA | DECIMAL(15,2) | N |  |

Indici:

- `MRFAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NAVCONF_CD

*Tabella* – righe: 2.384
– change data della tabella `NAVCONF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | NAVCONF_ISIN | CHAR(12) | N |  |
| 5 | XNAVCONF_ISIN | CHAR(12) |  |  |
| 6 | NAVCONF_MAF | CHAR(14) | N |  |
| 7 | NAVCONF_DVALNAV | DECIMAL(9,0) | N |  |
| 8 | XNAVCONF_DVALNAV | DECIMAL(9,0) |  |  |
| 9 | NAVCONF_CODDIV | CHAR(3) | N |  |
| 10 | NAVCONF_NAVDIV | DECIMAL(13,3) | N |  |
| 11 | NAVCONF_NAVEURO | DECIMAL(15,3) | N |  |
| 12 | NAVCONF_CAMBIO | DECIMAL(13,5) | N |  |

Indici:

- `NAVCONFD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NAV_CD5

*Tabella* – righe: 0
– change data della tabella `NAV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | NAV_DVALNAV | DECIMAL(9,0) | N |  |
| 6 | NAV_CODPROD | CHAR(2) | N |  |
| 7 | NAV_VALNAV | DECIMAL(13,0) | N |  |
| 8 | NAV_SUBPROD | CHAR(5) | N |  |
| 9 | NAV_NAVEST | DECIMAL(8,2) | N |  |
| 10 | NAV_DNAVAL | DECIMAL(9,0) | N |  |
| 11 | NAV_NAVDIV | DECIMAL(13,3) | N |  |
| 12 | NAV_NAVEURO | DECIMAL(13,3) | N |  |
| 13 | NAV_VALNAV5D | DECIMAL(15,5) |  |  |
| 14 | NAV_CODDIV | CHAR(3) |  |  |
| 15 | NAV_CAMBIO | DECIMAL(13,5) |  |  |
| 16 | NAV_VALNAV7D | DECIMAL(15,7) |  |  |
| 17 | XNAV_DVALNAV | DECIMAL(9,0) |  |  |
| 18 | XNAV_CODPROD | CHAR(2) |  |  |
| 19 | XNAV_SUBPROD | CHAR(5) |  |  |
| 20 | XNAV_DNAVAL | DECIMAL(9,0) |  |  |
| 21 | NAV_NAVMAX | DECIMAL(13,3) | N | QUOTAZIONE MASSIMA RAGGIUNTA |
| 22 | NAV_DNAVMAX | DECIMAL(9,0) | N | DATA NAV DEL QUOTAZIONE MASSIMA RAGGIUNTA |
| 23 | NAV_NAVPROT | DECIMAL(13,3) | N | QUOTAZ. MAX. RAGGIUNTA COINCIDE NAV PROTETTO |

Indici:

- `ASN_NAV_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NOBPREZ_CD

*Tabella* – righe: 316
– change data della tabella `NOBPREZ`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | NOBPREZ_CDFIS | CHAR(16) | N |  |
| 5 | NOBPREZ_CODMAND | CHAR(32) | N |  |
| 6 | NOBPREZ_CODCONF | CHAR(11) | N |  |
| 7 | NOBPREZ_CODCONF_ES | CHAR(11) | N |  |
| 8 | NOBPREZ_DOSSIER | CHAR(15) | N |  |
| 9 | NOBPREZ_DTVALINI | DECIMAL(9,0) | N |  |
| 10 | NOBPREZ_DTVALFIN | DECIMAL(9,0) | N |  |
| 11 | NOBPREZ_RETE | CHAR(1) | N |  |
| 12 | NOBPREZ_PB | CHAR(6) | N |  |
| 13 | NOBPREZ_CC | CHAR(12) | N |  |
| 14 | NOBPREZ_DTEFFINI | DECIMAL(9,0) | N |  |
| 15 | NOBPREZ_DTEFFFIN | DECIMAL(9,0) | N |  |

Indici:

- `NOBPREZD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NRRIA_CD

*Tabella* – righe: 16.361
– change data della tabella `NRRIA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | NRRIA_RETE | CHAR(1) | N |  |
| 5 | NRRIA_CODCONF | CHAR(11) | N |  |
| 6 | NRRIA_DVALINI | DECIMAL(9,0) | N |  |
| 7 | NRRIA_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | NRRIA_CODAGE | CHAR(6) | N |  |
| 9 | NRRIA_RFA | DECIMAL(15,2) | N |  |
| 10 | NRRIA_MOTIVO | CHAR(1) | N |  |
| 11 | NRRIA_CESSIONE | CHAR(1) | N |  |
| 12 | NRRIA_TRA_PARENTI | CHAR(1) | N |  |
| 13 | NRRIA_CODANA | CHAR(12) | N |  |

Indici:

- `NRRIAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NSRSEI_CD

*Tabella* – righe: 4.459.949
– change data della tabella `NSRSEI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | NSRSEI_CODCONF | CHAR(11) | N |  |
| 5 | NSRSEI_DATARFA | DECIMAL(9,0) | N |  |
| 6 | NSRSEI_ACODAGE | CHAR(6) | N |  |
| 7 | NSRSEI_CODANA | CHAR(12) | N |  |
| 8 | NSRSEI_PRESSO | CHAR(32) | N |  |
| 9 | NSRSEI_RFA | DECIMAL(15,2) | N |  |
| 10 | NSRSEI_RETE | CHAR(1) | N |  |
| 11 | NSRSEI_CODCONF_SOT | CHAR(11) | N |  |
| 12 | NSRSEI_CODPROD | CHAR(2) | N |  |
| 13 | NSRSEI_SUBPROD | CHAR(5) | N |  |
| 14 | NSRSEI_SOT_ESC | CHAR(1) | N |  |

Indici:

- `NSRSEID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_NVGS_CD

*Tabella* – righe: 0
– change data della tabella `NVGS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | NVGS_CODGS | CHAR(5) | N |  |
| 5 | NVGS_DTRIFNAV | DATE | N |  |
| 6 | NVGS_NAV | DECIMAL(7,3) |  |  |
| 7 | NVGS_COMISS | DECIMAL(15,2) |  |  |
| 8 | NVGS_ELBOINS | INTEGER |  |  |
| 9 | NVGS_ELBOAGG | INTEGER |  |  |
| 10 | NVGS_RETE | CHAR(3) | N |  |

Indici:

- `NVGSD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_OCSA_CD5

*Tabella* – righe: 0
– change data della tabella `OCSA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | OCSA_CODCONF | CHAR(11) | N |  |
| 6 | OCSA_SUBPROD | CHAR(5) | N |  |
| 7 | OCSA_CODPROD | CHAR(2) | N |  |
| 8 | OCSA_IMPACCS | DECIMAL(13,0) | N |  |
| 9 | OCSA_IPREMPG | DECIMAL(13,0) | N |  |
| 10 | OCSA_NMOV | SMALLINT | N |  |
| 11 | OCSA_NUMPOL | CHAR(7) | N |  |
| 12 | OCSA_RATAIMP | DECIMAL(11,0) | N |  |
| 13 | OCSA_EIMPACCS | DECIMAL(15,2) | N |  |
| 14 | OCSA_EIPREMPG | DECIMAL(15,2) | N |  |
| 15 | OCSA_ERATAIMP | DECIMAL(15,2) | N |  |

Indici:

- `ASN_OCSA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_OGAR_CD5

*Tabella* – righe: 0
– change data della tabella `OGAR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | OGAR_NUMPOL | CHAR(7) | N |  |
| 6 | OGAR_CODTRF | CHAR(3) | N |  |
| 7 | OGAR_NUMAPP | DECIMAL(3,0) | N |  |
| 8 | OGAR_CODCONF | CHAR(11) | N |  |
| 9 | OGAR_CAPITALE | DECIMAL(11,0) | N |  |
| 10 | OGAR_RENDITA | DECIMAL(11,0) | N |  |
| 11 | OGAR_PRECAS | DECIMAL(11,0) | N |  |
| 12 | OGAR_CAPITALER | DECIMAL(11,0) | N |  |
| 13 | OGAR_RENDITAR | DECIMAL(11,0) | N |  |
| 14 | OGAR_PRECASR | DECIMAL(11,0) | N |  |
| 15 | OGAR_DTULTRIV | DECIMAL(8,0) | N |  |
| 16 | OGAR_TASRIV | DECIMAL(5,2) | N |  |
| 17 | OGAR_DTDECRI | DECIMAL(8,0) | N |  |
| 18 | OGAR_DTSCARI | DECIMAL(8,0) | N |  |
| 19 | OGAR_DTFNPAG | DECIMAL(8,0) | N |  |
| 20 | OGAR_DTFNDIF | DECIMAL(8,0) | N |  |
| 21 | OGAR_DTFNCOP | DECIMAL(8,0) | N |  |
| 22 | OGAR_DTINGRI | DECIMAL(8,0) | N |  |
| 23 | OGAR_CDFRZRE | CHAR(2) | N |  |
| 24 | OGAR_TIPGAR | CHAR(1) | N |  |
| 25 | OGAR_CDBENVI | CHAR(2) | N |  |
| 26 | OGAR_CDBENMO | CHAR(2) | N |  |
| 27 | OGAR_ETAAA | DECIMAL(2,0) | N |  |
| 28 | OGAR_ETAMM | DECIMAL(2,0) | N |  |
| 29 | OGAR_CDINGRI | CHAR(2) | N |  |
| 30 | OGAR_CDGRUCAL | CHAR(1) | N |  |
| 31 | OGAR_DTSCAPP | DECIMAL(8,0) | N |  |
| 32 | OGAR_ECAPITALE | DECIMAL(15,2) | N |  |
| 33 | OGAR_ERENDITA | DECIMAL(15,2) | N |  |
| 34 | OGAR_EPRECAS | DECIMAL(15,2) | N |  |
| 35 | OGAR_ECAPITALER | DECIMAL(15,2) | N |  |
| 36 | OGAR_ERENDITAR | DECIMAL(15,2) | N |  |
| 37 | OGAR_EPRECASR | DECIMAL(15,2) | N |  |

Indici:

- `ASN_OGAR_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_OPRT_CD5

*Tabella* – righe: 0
– change data della tabella `OPRT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | OPRT_NUMPOL | CHAR(7) | N |  |
| 6 | OPRT_CODCONF | CHAR(11) | N |  |
| 7 | OPRT_INDSTA1 | CHAR(2) | N |  |
| 8 | OPRT_INDSTA2 | CHAR(2) | N |  |
| 9 | OPRT_DTEMIPOL | DECIMAL(8,0) | N |  |
| 10 | OPRT_CDFRZRI | DECIMAL(2,0) | N |  |
| 11 | OPRT_DTDECPOL | DECIMAL(8,0) | N |  |
| 12 | OPRT_TRFBASE | CHAR(3) | N |  |
| 13 | OPRT_INDRIDUZ | CHAR(1) | N |  |
| 14 | OPRT_DTSYS | DECIMAL(8,0) | N |  |
| 15 | OPRT_RISMAT_INT | DECIMAL(11,0) | N |  |
| 16 | OPRT_DTSYSRIS | DECIMAL(10,0) | N |  |
| 17 | OPRT_NUMCOL | CHAR(4) | N |  |
| 18 | OPRT_TRFNEW | CHAR(3) | N |  |
| 19 | OPRT_ERISMAT_INT | DECIMAL(15,2) | N |  |

Indici:

- `ASN_OPRT_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_OREG_CD5

*Tabella* – righe: 0
– change data della tabella `OREG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | OREG_NUMREG | DECIMAL(9,0) | N |  |
| 6 | OREG_NUMPOL | CHAR(7) | N |  |
| 7 | OREG_CODTRF | CHAR(3) | N |  |
| 8 | OREG_NUMAPP | DECIMAL(3,0) | N |  |
| 9 | OREG_CODCONF | CHAR(11) | N |  |
| 10 | OREG_DTINCOP | DECIMAL(8,0) | N |  |
| 11 | OREG_CDSTATI | CHAR(2) | N |  |
| 12 | OREG_DTPAG | DECIMAL(8,0) | N |  |
| 13 | OREG_RATLOR | DECIMAL(11,0) | N |  |
| 14 | OREG_CDTITIT | CHAR(2) | N |  |
| 15 | OREG_DTSYS | DECIMAL(8,0) | N |  |
| 16 | OREG_ERATLOR | DECIMAL(15,2) | N |  |

Indici:

- `ASN_OREG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PAG_CD5

*Tabella* – righe: 0
– change data della tabella `PAG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PAG_CODCONF | CHAR(11) | N |  |
| 6 | PAG_CODPROD | CHAR(2) | N |  |
| 7 | PAG_TIPOPER | CHAR(2) | N |  |
| 8 | PAG_PROGMOV | SMALLINT | N |  |
| 9 | PAG_CODPAG | CHAR(2) | N |  |
| 10 | PAG_SUBPROD | CHAR(5) | N |  |
| 11 | PAG_DACQUIS | DECIMAL(9,0) | N |  |
| 12 | PAG_DELABOR | DECIMAL(9,0) | N |  |
| 13 | PAG_STATO | CHAR(1) | N |  |
| 14 | PAG_DEFFACC | DECIMAL(9,0) | N |  |
| 15 | PAG_DEFFADD | DECIMAL(9,0) | N |  |
| 16 | PAG_RETE | CHAR(1) | N |  |
| 17 | PAG_TES | CHAR(3) |  |  |
| 18 | PAG_DESCAU | VARCHAR(70) |  |  |
| 19 | PAG_DADDGES | DECIMAL(9,0) |  |  |
| 20 | PAG_DACCBEN | DECIMAL(9,0) |  |  |
| 21 | PAG_CODUTE | CHAR(4) |  |  |
| 22 | PAG_DATVAR | DECIMAL(9,0) |  |  |
| 23 | PAG_ORAVAR | DECIMAL(7,0) |  |  |
| 24 | PAG_LASTPAG | SMALLINT |  |  |
| 25 | PAG_INDACQ | CHAR(1) |  |  |
| 26 | PAG_DATAVAL | DECIMAL(9,0) |  |  |
| 27 | PAG_FLAGDIV | CHAR(1) |  |  |
| 28 | XPAG_CODCONF | CHAR(11) |  |  |
| 29 | XPAG_CODPROD | CHAR(2) |  |  |
| 30 | XPAG_TIPOPER | CHAR(2) |  |  |
| 31 | XPAG_CODPAG | CHAR(2) |  |  |
| 32 | XPAG_SUBPROD | CHAR(5) |  |  |
| 33 | XPAG_DACQUIS | DECIMAL(9,0) |  |  |

Indici:

- `ASN_PAG_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PCOMRT_CD

*Tabella* – righe: 0
– change data della tabella `PCOMRT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PCOMRT_CODPROD | CHAR(2) | N |  |
| 5 | PCOMRT_SUBPROD | CHAR(5) | N |  |
| 6 | PCOMRT_RETE | CHAR(1) | N |  |
| 7 | PCOMRT_DVALINI | DECIMAL(9,0) | N |  |
| 8 | PCOMRT_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | PCOMRT_COMGESR | DECIMAL(5,2) | N |  |
| 10 | PCOMRT_PRCPAYO | DECIMAL(5,2) | N |  |
| 11 | PCOMRT_PRCPATR | DECIMAL(7,3) | N |  |
| 12 | PCOMRT_COMDISR | DECIMAL(5,2) | N |  |
| 13 | PCOMRT_PAYINGES | DECIMAL(5,2) | N |  |
| 14 | PCOMRT_PAYINDIS | DECIMAL(5,2) | N |  |
| 15 | PCOMRT_PERIODO | CHAR(2) | N |  |
| 16 | PCOMRT_COMTOTR | DECIMAL(5,2) | N |  |
| 17 | PCOMRT_PAYINTOT | DECIMAL(5,2) | N |  |

Indici:

- `PCOMRTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PDE_CD5

*Tabella* – righe: 0
– change data della tabella `PDE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PDE_ABI_GE | CHAR(5) | N |  |
| 6 | PDE_PDE | CHAR(3) | N |  |
| 7 | PDE_CAB_GE | CHAR(5) | N |  |
| 8 | PDE_DESCR | CHAR(60) | N |  |
| 9 | PDE_PTEL | CHAR(5) | N |  |
| 10 | PDE_NTEL | CHAR(10) | N |  |
| 11 | PDE_NTEL2 | CHAR(10) | N |  |
| 12 | PDE_FAX | CHAR(10) | N |  |
| 13 | PDE_TELABBR | CHAR(7) | N |  |
| 14 | PDE_INDCZONA | CHAR(1) | N |  |

Indici:

- `ASN_PDE_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PDRETE_CD

*Tabella* – righe: 419
– change data della tabella `PDRETE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PDRETE_CODPROD | CHAR(2) | N |  |
| 5 | PDRETE_RETE | CHAR(1) | N |  |
| 6 | PDRETE_SUBPROD | CHAR(5) | N |  |
| 7 | PDRETE_TIPOPER | CHAR(2) | N |  |
| 8 | PDRETE_TIPOPES | CHAR(2) | N |  |
| 9 | PDRETE_DVALINI | DECIMAL(9,0) | N |  |
| 10 | PDRETE_DVALFIN | DECIMAL(9,0) | N |  |
| 11 | PDRETE_INDFREE | CHAR(1) | N |  |

Indici:

- `PDRETED01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PFIPSPI_CD

*Tabella* – righe: 0
– change data della tabella `PFIPSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PFIPSPI_SIGLA | CHAR(4) | N |  |
| 5 | PFIPSPI_AGECED | CHAR(6) | N |  |
| 6 | PFIPSPI_AGESUB | CHAR(6) | N |  |
| 7 | PFIPSPI_DVALINI | DECIMAL(9,0) | N |  |
| 8 | PFIPSPI_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | PFIPSPI_DTCARIC | DECIMAL(9,0) | N |  |
| 10 | PFIPSPI_CODIFICA | CHAR(3) | N |  |
| 11 | PFIPSPI_NOTE | CHAR(70) | N |  |

Indici:

- `PFIPSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PFIP_CD

*Tabella* – righe: 8
– change data della tabella `PFIP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PFIP_AGECED | CHAR(6) | N |  |
| 5 | PFIP_AGESUB | CHAR(6) | N |  |
| 6 | PFIP_DVALINI | DECIMAL(9,0) | N |  |
| 7 | PFIP_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | PFIP_DTCARIC | DECIMAL(9,0) | N |  |
| 9 | PFIP_CODIFICA | CHAR(3) | N |  |
| 10 | PFIP_NOTE | CHAR(70) | N |  |

Indici:

- `PFIPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_POLD_CD5

*Tabella* – righe: 0
– change data della tabella `POLD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | POLD_CODCONF | CHAR(11) | N |  |
| 6 | POLD_CODANA | CHAR(12) | N |  |
| 7 | POLD_RAMO | CHAR(2) | N |  |
| 8 | POLD_NUMPOL | CHAR(10) | N |  |
| 9 | POLD_CODPROD | CHAR(2) | N |  |
| 10 | POLD_CDFIS | CHAR(16) | N |  |
| 11 | POLD_CODAGE | CHAR(6) | N |  |
| 12 | POLD_DTEFF | DECIMAL(9,0) | N |  |
| 13 | POLD_DTEFFP | DECIMAL(9,0) | N |  |
| 14 | POLD_PREMIO | DECIMAL(13,0) | N |  |
| 15 | POLD_NUMTES | DECIMAL(3,0) | N |  |
| 16 | POLD_DTDEC | DECIMAL(9,0) | N |  |
| 17 | POLD_DTSCAD | DECIMAL(9,0) | N |  |
| 18 | POLD_DTAGG | DECIMAL(9,0) | N |  |
| 19 | POLD_PREURO | DECIMAL(13,2) |  |  |
| 20 | POLD_FLGVAL | CHAR(1) | N |  |

Indici:

- `ASN_POLD_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PRESCA_CD

*Tabella* – righe: 13
– change data della tabella `PRESCA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PRESCA_CODCONF | CHAR(11) | N |  |
| 5 | PRESCA_CODPROD | CHAR(2) | N |  |
| 6 | PRESCA_SUBPROD | CHAR(5) | N |  |
| 7 | PRESCA_DTSCA | DECIMAL(9,0) | N |  |
| 8 | PRESCA_IMPORTO | DECIMAL(15,2) | N |  |
| 9 | PRESCA_STATO | CHAR(2) | N |  |
| 10 | PRESCA_DTINCASSO | DECIMAL(9,0) | N |  |
| 11 | PRESCA_IMPODIV | DECIMAL(15,2) | N |  |
| 12 | PRESCA_DIVISA | CHAR(3) | N |  |
| 13 | PRESCA_DATACAM | DECIMAL(9,0) | N |  |
| 14 | PRESCA_VALORE | DECIMAL(9,6) | N |  |
| 15 | PRESCA_TIMER | DECIMAL(13,0) | N |  |
| 16 | PRESCA_PROGMOV | SMALLINT | N |  |
| 17 | PRESCA_RETE | CHAR(1) | N |  |
| 18 | PRESCA_PRC_INDIC_AP | DECIMAL(7,3) |  |  |
| 19 | PRESCA_PRC_INDIC_AS | DECIMAL(7,3) |  |  |

Indici:

- `PRESCAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PRESTAZ_CD

*Tabella* – righe: 2
– change data della tabella `PRESTAZ`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PRESTAZ_CODCONF | CHAR(11) | N |  |
| 5 | PRESTAZ_NUMPOL | CHAR(11) | N |  |
| 6 | PRESTAZ_CODPROD | CHAR(2) | N |  |
| 7 | PRESTAZ_CODTRF | CHAR(5) | N |  |
| 8 | PRESTAZ_NUMAPP | CHAR(10) | N |  |
| 9 | PRESTAZ_TIPGAR | CHAR(5) | N |  |
| 10 | PRESTAZ_DTINGRI | DECIMAL(9,0) | N |  |
| 11 | PRESTAZ_DTDECRI | DECIMAL(9,0) | N |  |
| 12 | PRESTAZ_DTSCARI | DECIMAL(9,0) | N |  |
| 13 | PRESTAZ_DTSCAPP | DECIMAL(9,0) | N |  |
| 14 | PRESTAZ_CAPITALER | DECIMAL(15,2) | N |  |
| 15 | PRESTAZ_CNTRASCAR | DECIMAL(15,2) | N |  |
| 16 | PRESTAZ_RENDITAR | DECIMAL(15,2) | N |  |
| 17 | PRESTAZ_CNTRASRER | DECIMAL(15,2) | N |  |
| 18 | PRESTAZ_DTULTRIV | DECIMAL(9,0) | N |  |
| 19 | PRESTAZ_TASRIVN | DECIMAL(8,3) | N |  |
| 20 | PRESTAZ_TASRIVL | DECIMAL(8,3) | N |  |
| 21 | PRESTAZ_DTFNDIF | DECIMAL(9,0) | N |  |
| 22 | PRESTAZ_DTFNPAG | DECIMAL(9,0) | N |  |
| 23 | PRESTAZ_DTFNCOP | DECIMAL(9,0) | N |  |

Indici:

- `PRESTAZD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PROVCG_CD

*Tabella* – righe: 0
– change data della tabella `PROVCG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PROVCG_CODAGVEN | CHAR(6) | N |  |
| 5 | PROVCG_CODANA | CHAR(12) | N |  |
| 6 | PROVCG_CODCONF | CHAR(11) | N |  |
| 7 | PROVCG_PROGMOV | SMALLINT | N |  |
| 8 | PROVCG_TIPOPER | CHAR(2) | N |  |
| 9 | PROVCG_TIPOPES | CHAR(2) | N |  |
| 10 | PROVCG_CODPROD | CHAR(2) | N |  |
| 11 | PROVCG_SUBPROD | CHAR(5) | N |  |
| 12 | PROVCG_TITOLO | CHAR(5) | N |  |
| 13 | PROVCG_ISIN | CHAR(12) | N |  |
| 14 | PROVCG_DELABCOM | DECIMAL(9,0) | N |  |
| 15 | PROVCG_VOCE | CHAR(3) | N |  |
| 16 | PROVCG_TIPOCOMM | CHAR(2) | N |  |
| 17 | PROVCG_PAYIN | DECIMAL(15,2) | N |  |
| 18 | PROVCG_TIPO_DISTR | CHAR(2) | N |  |
| 19 | PROVCG_CODAGE | CHAR(6) | N |  |
| 20 | PROVCG_PAYOUT | DECIMAL(15,2) | N |  |
| 21 | PROVCG_TIPO_PAYOUT | CHAR(3) | N |  |
| 22 | PROVCG_RETE | CHAR(1) | N |  |
| 23 | PROVCG_FASE | CHAR(3) | N |  |
| 24 | PROVCG_PROVENIENZA | CHAR(5) | N |  |
| 25 | PROVCG_TIPO_PREMIO | CHAR(1) | N |  |
| 26 | PROVCG_TIPO_ANN | CHAR(1) | N |  |
| 27 | PROVCG_KEYNUMBER | DECIMAL(15,0) | N |  |
| 28 | PROVCG_DT_INVIO | DECIMAL(9,0) | N |  |
| 29 | PROVCG_DCOMPBIL | DECIMAL(9,0) | N |  |
| 30 | PROVCG_PAYIN_DISTR | DECIMAL(15,2) | N |  |
| 31 | PROVCG_PAYIN_IVA | DECIMAL(15,2) |  |  |

Indici:

- `PROVCGD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PROVCT_CD5

*Tabella* – righe: 0
– change data della tabella `PROVCT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | CHAR(10) | N |  |
| 2 | IBMSNAP_INTENTSEQ | CHAR(10) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PROVCT_CODCONF | CHAR(11) | N |  |
| 6 | PROVCT_PROGMOV | DECIMAL(5,0) | N |  |
| 7 | PROVCT_CODPROD | CHAR(2) | N |  |
| 8 | PROVCT_SUBPROD | CHAR(5) | N |  |
| 9 | PROVCT_TIPOPER | CHAR(2) | N |  |
| 10 | PROVCT_TIPOPES | CHAR(2) | N |  |
| 11 | PROVCT_CODAGE | CHAR(6) | N |  |
| 12 | PROVCT_PERCSPLIT | DECIMAL(5,2) | N |  |
| 13 | PROVCT_PAYIN | DECIMAL(15,2) | N |  |
| 14 | PROVCT_PAYOUT_TOT | DECIMAL(15,2) | N |  |
| 15 | PROVCT_IMPPROV_TOT | DECIMAL(15,2) | N |  |
| 16 | PROVCT_DELABINV | DECIMAL(9,0) | N |  |
| 17 | PROVCT_DELABCOM | DECIMAL(9,0) | N |  |
| 18 | PROVCT_DELABSTR | DECIMAL(9,0) | N |  |
| 19 | PROVCT_DCOMPBIL | DECIMAL(9,0) | N |  |
| 20 | PROVCT_INDMAN | CHAR(2) | N |  |
| 21 | PROVCT_COD_DESCR | DECIMAL(7,0) | N |  |
| 22 | PROVCT_COD_TITOLO | CHAR(5) | N |  |
| 23 | PROVCT_KEYNUMBER | DECIMAL(15,0) | N |  |

Indici:

- `ASN_PROVCT_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PROVOCE_CD5

*Tabella* – righe: 0
– change data della tabella `PROVOCE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | CHAR(10) | N |  |
| 2 | IBMSNAP_INTENTSEQ | CHAR(10) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PROVOCE_CODAGE | CHAR(6) | N |  |
| 6 | PROVOCE_VOCE | CHAR(3) | N |  |
| 7 | PROVOCE_IMPPROV | DECIMAL(15,2) | N |  |
| 8 | PROVOCE_DELABCOM | DECIMAL(9,0) | N |  |
| 9 | PROVOCE_DFATTURA | DECIMAL(9,0) | N |  |
| 10 | PROVOCE_DCOMPBIL | DECIMAL(9,0) | N |  |
| 11 | PROVOCE_TIPO_PROV | CHAR(1) | N |  |
| 12 | PROVOCE_INDMAN | CHAR(2) | N |  |
| 13 | PROVOCE_INDFATT | CHAR(1) | N |  |
| 14 | PROVOCE_COD_DESCR | DECIMAL(7,0) | N |  |
| 15 | PROVOCE_RECNUMBER | DECIMAL(15,0) | N |  |

Indici:

- `ASN_PROVOCE_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PRVCSPB_CD

*Tabella* – righe: 0
– change data della tabella `PRVCSPB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | CHAR(10) | N |  |
| 2 | IBMSNAP_INTENTSEQ | CHAR(10) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PRVCSPB_CODAGE | CHAR(6) | N |  |
| 5 | PRVCSPB_VOCE | CHAR(3) | N |  |
| 6 | PRVCSPB_IMPPROV | DECIMAL(15,2) | N |  |
| 7 | PRVCSPB_DELABCOM | DECIMAL(9,0) | N |  |
| 8 | PRVCSPB_DFATTURA | DECIMAL(9,0) | N |  |
| 9 | PRVCSPB_DCOMPBIL | DECIMAL(9,0) | N |  |
| 10 | PRVCSPB_TIPO_PROV | CHAR(1) | N |  |
| 11 | PRVCSPB_INDMAN | CHAR(2) | N |  |
| 12 | PRVCSPB_INDFATT | CHAR(1) | N |  |
| 13 | PRVCSPB_COD_DESCR | DECIMAL(7,0) | N |  |
| 14 | PRVCSPB_RECNUMBER | DECIMAL(15,0) | N |  |
| 15 | PRVCSPB_DTSTRALC | DECIMAL(9,0) | N |  |

Indici:

- `PRVCSPBD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PRVCTSPI_CD

*Tabella* – righe: 0
– change data della tabella `PRVCTSPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | CHAR(10) | N |  |
| 2 | IBMSNAP_INTENTSEQ | CHAR(10) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PRVCTSPI_CODCONF | CHAR(11) | N |  |
| 5 | PRVCTSPI_PROGMOV | DECIMAL(5,0) | N |  |
| 6 | PRVCTSPI_CODPROD | CHAR(2) | N |  |
| 7 | PRVCTSPI_SUBPROD | CHAR(5) | N |  |
| 8 | PRVCTSPI_TIPOPER | CHAR(2) | N |  |
| 9 | PRVCTSPI_TIPOPES | CHAR(2) | N |  |
| 10 | PRVCTSPI_CODAGE | CHAR(6) | N |  |
| 11 | PRVCTSPI_PERCSPLIT | DECIMAL(5,2) | N |  |
| 12 | PRVCTSPI_PAYIN | DECIMAL(15,2) | N |  |
| 13 | PRVCTSPI_PAYOUT_T | DECIMAL(15,2) | N |  |
| 14 | PRVCTSPI_IMPPROV_T | DECIMAL(15,2) | N |  |
| 15 | PRVCTSPI_DELABINV | DECIMAL(9,0) | N |  |
| 16 | PRVCTSPI_DELABCOM | DECIMAL(9,0) | N |  |
| 17 | PRVCTSPI_DELABSTR | DECIMAL(9,0) | N |  |
| 18 | PRVCTSPI_DCOMPBIL | DECIMAL(9,0) | N |  |
| 19 | PRVCTSPI_INDMAN | CHAR(2) | N |  |
| 20 | PRVCTSPI_COD_DESCR | DECIMAL(7,0) | N |  |
| 21 | PRVCTSPI_CODTITOLO | CHAR(5) | N |  |
| 22 | PRVCTSPI_KEYNUMBER | DECIMAL(15,0) | N |  |

Indici:

- `PRVCTSPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PRZTIT_CD

*Tabella* – righe: 297.264
– change data della tabella `PRZTIT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PRZTIT_MAF | CHAR(14) | N |  |
| 5 | PRZTIT_ISIN | CHAR(12) | N |  |
| 6 | PRZTIT_DATAPRZ | DECIMAL(9,0) | N |  |
| 7 | PRZTIT_COD_DIV | CHAR(3) | N |  |
| 8 | PRZTIT_PREZZO_DIV | DECIMAL(15,7) | N |  |
| 9 | PRZTIT_PREZZO_EUR | DECIMAL(15,3) | N |  |
| 10 | PRZTIT_CAMBIO | DECIMAL(13,5) | N |  |

Indici:

- `PRZTITD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTCFL_CD

*Tabella* – righe: 179.716
– change data della tabella `PTCFL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PTCFL_CODCONF | CHAR(11) | N |  |
| 6 | PTCFL_CODPROD | CHAR(2) | N |  |
| 7 | PTCFL_SUBPROD | CHAR(5) | N |  |
| 8 | PTCFL_STATO | CHAR(1) | N |  |
| 9 | PTCFL_IMPRICV | DECIMAL(15,2) | N |  |
| 10 | PTCFL_IMPLIQD | DECIMAL(15,2) | N |  |
| 11 | PTCFL_SPSSOTT | DECIMAL(15,2) | N |  |
| 12 | PTCFL_SPSSGR | DECIMAL(15,2) | N |  |
| 13 | PTCFL_PRTACQS | DECIMAL(13,3) | N |  |
| 14 | PTCFL_PRTLIQD | DECIMAL(13,3) | N |  |
| 15 | PTCFL_PRTAGPO | DECIMAL(13,3) | N |  |
| 16 | PTCFL_PRTAGNE | DECIMAL(13,3) | N |  |
| 17 | PTCFL_CAPGAIN | DECIMAL(15,2) | N |  |
| 18 | PTCFL_DULELAB | DECIMAL(9,0) | N |  |
| 19 | PTCFL_RETE | CHAR(1) | N |  |
| 20 | PTCFL_VALNOM | DECIMAL(15,2) | N |  |
| 21 | PTCFL_INDPROV | CHAR(1) |  |  |
| 22 | PTCFL_VALNOM_QTA | DECIMAL(15,3) |  |  |
| 23 | PTCFL_PRTACQS6D | DECIMAL(13,6) |  |  |
| 24 | PTCFL_PRTLIQD6D | DECIMAL(13,6) |  |  |
| 25 | PTCFL_PRTAGPO6D | DECIMAL(13,6) |  |  |
| 26 | PTCFL_PRTAGNE6D | DECIMAL(13,6) |  |  |
| 27 | PTCFL_PRTVINC | DECIMAL(13,3) | N | QUOTE VINCOLATE |

Indici:

- `PTCFLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTCFM_CD

*Tabella* – righe: 4.821
– change data della tabella `PTCFM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 5 | PTCFM_CODCONF | CHAR(11) | N |  |
| 6 | PTCFM_CODPROD | CHAR(2) | N |  |
| 7 | PTCFM_DOSSIERBK | CHAR(20) | N |  |
| 8 | PTCFM_CODPRATICA | CHAR(20) | N |  |
| 9 | PTCFM_NUMDA | CHAR(8) | N |  |
| 10 | PTCFM_CONTRTIPO | CHAR(1) |  |  |

Indici:

- `PTCFMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTCML_CD

*Tabella* – righe: 343.763
– change data della tabella `PTCML`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | PTCML_CODCONF | CHAR(11) | N |  |
| 6 | PTCML_CODPROD | CHAR(2) | N |  |
| 7 | PTCML_SUBPROD | CHAR(5) | N |  |
| 8 | PTCML_PROGMOV | SMALLINT | N |  |
| 9 | PTCML_PROGOPE | SMALLINT | N |  |
| 10 | PTCML_STATO | CHAR(1) | N |  |
| 11 | PTCML_TIPOPER | CHAR(2) | N |  |
| 12 | PTCML_TIPOPES | CHAR(2) | N |  |
| 13 | PTCML_DVALFND | DECIMAL(9,0) | N |  |
| 14 | PTCML_IMPACQ | DECIMAL(15,2) | N |  |
| 15 | PTCML_IMPORTO | DECIMAL(15,2) | N |  |
| 16 | PTCML_SPSPERC | DECIMAL(5,2) | N |  |
| 17 | PTCML_SPSSOTT | DECIMAL(15,2) | N |  |
| 18 | PTCML_SPSSGR | DECIMAL(15,2) | N |  |
| 19 | PTCML_NETINVS | DECIMAL(15,2) | N |  |
| 20 | PTCML_DVALNAV | DECIMAL(9,0) | N |  |
| 21 | PTCML_VALNAV | DECIMAL(15,3) | N |  |
| 22 | PTCML_PRTACQ | DECIMAL(13,3) | N |  |
| 23 | PTCML_PRTOPER | DECIMAL(13,3) | N |  |
| 24 | PTCML_CAPGAIN | DECIMAL(15,2) | N |  |
| 25 | PTCML_PAYIN | DECIMAL(15,2) | N |  |
| 26 | PTCML_PAYOUT | DECIMAL(15,2) | N |  |
| 27 | PTCML_FLUSSOIN | CHAR(8) | N |  |
| 28 | PTCML_FLUSSORC | CHAR(8) | N |  |
| 29 | PTCML_CAMBIO | DECIMAL(13,5) | N |  |
| 30 | PTCML_DTCAMBIO | DECIMAL(9,0) | N |  |
| 31 | PTCML_DTOPERBK | DECIMAL(9,0) | N |  |
| 32 | PTCML_CODTIT | CHAR(10) | N |  |
| 33 | PTCML_DTACCR | DECIMAL(9,0) | N | DATA VALUTA EFF. ACCREDITO |
| 34 | XPTCML_CODCONF | CHAR(11) |  | CONTRATTO OLD |
| 35 | XPTCML_CODPROD | CHAR(2) |  | CODPROD   OLD |
| 36 | XPTCML_SUBPROD | CHAR(5) |  | SUBPROD   OLD |
| 37 | XPTCML_PROGMOV | SMALLINT |  | PROGMOV   OLD |
| 38 | XPTCML_PROGOPE | SMALLINT |  | PROGOPE   OLD |
| 39 | PTCML_IMPORTO_CDIV | CHAR(3) |  |  |
| 40 | PTCML_IMPORTO_DIV | DECIMAL(15,3) |  |  |
| 41 | PTCML_SPSSOTT_CDIV | CHAR(3) |  |  |
| 42 | PTCML_SPSSOTT_DIV | DECIMAL(15,3) |  |  |
| 43 | PTCML_SPSSGR_CDIV | CHAR(3) |  |  |
| 44 | PTCML_SPSSGR_DIV | DECIMAL(15,3) |  |  |
| 45 | PTCML_NETINVS_CDIV | CHAR(3) |  |  |
| 46 | PTCML_NETINVS_DIV | DECIMAL(15,3) |  |  |
| 47 | PTCML_NAV_CODDIV | CHAR(3) |  |  |
| 48 | PTCML_NAV_DIV | DECIMAL(15,3) |  |  |
| 49 | PTCML_SPSSOTT_CAL | DECIMAL(15,3) |  |  |
| 50 | PTCML_MINPLUS | DECIMAL(15,2) |  |  |
| 51 | PTCML_COMMVAL | DECIMAL(15,2) |  |  |
| 52 | PTCML_CODPIANO | CHAR(20) |  |  |
| 53 | PTCML_NRATEV | DECIMAL(3,0) |  |  |
| 54 | PTCML_NORD | DECIMAL(9,0) |  |  |
| 55 | PTCML_PRTACQ6D | DECIMAL(13,6) |  |  |
| 56 | PTCML_PRTOPER6D | DECIMAL(13,6) |  |  |
| 57 | PTCML_SPSFND | DECIMAL(15,3) | N | SPESE FDT |

Indici:

- `PTCMLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTCMM_CD

*Tabella* – righe: 201.805
– change data della tabella `PTCMM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PTCMM_CODCONF | CHAR(11) | N |  |
| 5 | PTCMM_CODPROD | CHAR(2) | N |  |
| 6 | PTCMM_PROGMOV | SMALLINT | N |  |
| 7 | PTCMM_TIPOPER | CHAR(2) | N |  |
| 8 | PTCMM_DACQUIS | DECIMAL(9,0) | N |  |
| 9 | PTCMM_DTPROT | DECIMAL(9,0) | N |  |
| 10 | PTCMM_STATO | CHAR(1) | N |  |
| 11 | PTCMM_PRCESE | DECIMAL(3,0) | N |  |
| 12 | PTCMM_TIPOACQ | CHAR(1) | N |  |
| 13 | PTCMM_DATEACQ | DECIMAL(9,0) | N |  |
| 14 | PTCMM_TIMEACQ | DECIMAL(7,0) | N |  |
| 15 | PTCMM_CRO | CHAR(12) | N |  |
| 16 | PTCMM_RAESEN | CHAR(1) | N |  |

Indici:

- `PTCMMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTDIV_CD

*Tabella* – righe: 9.887
– change data della tabella `PTDIV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PTDIV_CODCONF | CHAR(11) | N |  |
| 5 | PTDIV_CODPROD | CHAR(2) | N |  |
| 6 | PTDIV_SUBPROD | CHAR(5) | N |  |
| 7 | PTDIV_TIPODISTR | CHAR(1) | N |  |
| 8 | PTDIV_CIN | CHAR(1) | N |  |
| 9 | PTDIV_ABI | CHAR(5) | N |  |
| 10 | PTDIV_CAB | CHAR(5) | N |  |
| 11 | PTDIV_NUMCC | CHAR(12) | N |  |
| 12 | PTDIV_NAZIOIBAN | CHAR(2) | N |  |
| 13 | PTDIV_CINIBAN | CHAR(2) | N |  |

Indici:

- `PTDIVD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTPIANI_CD

*Tabella* – righe: 54.145
– change data della tabella `PTPIANI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 5 | PTPIANI_CODCONF | CHAR(11) | N |  |
| 6 | PTPIANI_CODPROD | CHAR(2) | N |  |
| 7 | PTPIANI_CODPIANO | CHAR(20) | N |  |
| 8 | PTPIANI_PROGPIANO | CHAR(5) | N |  |
| 9 | PTPIANI_TIPOPIANO | CHAR(5) | N |  |
| 10 | PTPIANI_STATO | CHAR(1) | N |  |
| 11 | PTPIANI_TIPRATA | CHAR(2) | N |  |
| 12 | PTPIANI_PERIOD | CHAR(2) | N |  |
| 13 | PTPIANI_IMPINIZ | DECIMAL(15,3) | N |  |
| 14 | PTPIANI_IMPRATA | DECIMAL(15,3) | N |  |
| 15 | PTPIANI_NRATEP | DECIMAL(15,3) | N |  |
| 16 | PTPIANI_NRATEV | DECIMAL(15,3) | N |  |
| 17 | PTPIANI_MOPAG | CHAR(5) | N |  |
| 18 | PTPIANI_ABI | CHAR(5) | N |  |
| 19 | PTPIANI_CAB | CHAR(5) | N |  |
| 20 | PTPIANI_CC | CHAR(12) | N |  |
| 21 | PTPIANI_IMPVERSTOT | DECIMAL(15,3) | N |  |
| 22 | PTPIANI_DTDECOR | DECIMAL(9,0) | N |  |
| 23 | PTPIANI_DTINIZIO | DECIMAL(9,0) | N | DATA INIZIO |
| 24 | PTPIANI_DTFINE | DECIMAL(9,0) | N | DATA FINE |
| 25 | PTPIANI_QUOTERATA | DECIMAL(13,3) | N | QUOTE DA DISINVESTIRE PER PRS PSS |
| 26 | PTPIANI_DURATA | DECIMAL(3,0) | N |  |
| 27 | PTPIANI_PERCLIQ | DECIMAL(5,2) | N |  |
| 28 | PTPIANI_DTPROSDIS | DECIMAL(9,0) |  |  |
| 29 | XPTPIANI_CODCONF | CHAR(11) |  |  |
| 30 | XPTPIANI_CODPROD | CHAR(2) |  |  |
| 31 | XPTPIANI_CODPIANO | CHAR(20) |  |  |
| 32 | XPTPIANI_DTFINE | DECIMAL(9,0) |  |  |
| 33 | PTPIANI_COD_PORTMOD | CHAR(5) | N |  |

Indici:

- `PTPIANID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTSEN_CD

*Tabella* – righe: 1.133
– change data della tabella `PTSEN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PTSEN_CODCONF | CHAR(11) | N |  |
| 5 | PTSEN_CODPROD | CHAR(2) | N |  |
| 6 | PTSEN_SUBPROD | CHAR(5) | N |  |
| 7 | PTSEN_DSENIOR | DECIMAL(9,0) | N |  |
| 8 | PTSEN_PRTACQS | DECIMAL(15,3) | N |  |
| 9 | PTSEN_PRTLIQD | DECIMAL(15,3) | N |  |
| 10 | PTSEN_PRTAGPO | DECIMAL(15,3) | N |  |
| 11 | PTSEN_PRTAGNE | DECIMAL(15,3) | N |  |

Indici:

- `PTSEND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTSPIANI_CD

*Tabella* – righe: 68.425
– change data della tabella `PTSPIANI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 5 | PTSPIANI_CODCONF | CHAR(11) | N |  |
| 6 | PTSPIANI_CODPROD | CHAR(2) | N |  |
| 7 | PTSPIANI_CODPIANO | CHAR(20) | N |  |
| 8 | PTSPIANI_SUBPROD | CHAR(5) | N |  |
| 9 | PTSPIANI_CODTIT | CHAR(10) | N |  |
| 10 | PTSPIANI_PERC | CHAR(3) | N |  |
| 11 | PTSPIANI_SUBPRODR | CHAR(5) | N |  |
| 12 | PTSPIANI_IMPORTO | DECIMAL(15,3) | N |  |
| 13 | PTSPIANI_PERC_PCP | DECIMAL(5,2) |  |  |
| 14 | XPTSPIANI_CODCONF | CHAR(11) |  |  |
| 15 | XPTSPIANI_CODPROD | CHAR(2) |  |  |
| 16 | XPTSPIANI_CODPIANO | CHAR(20) |  |  |
| 17 | XPTSPIANI_SUBPROD | CHAR(5) |  |  |
| 18 | XPTSPIANI_SUBPRODR | CHAR(5) |  |  |
| 19 | PTSPIANI_COD_LIV2 | CHAR(5) |  |  |
| 20 | XPTSPIANI_COD_LIV2 | CHAR(5) |  |  |
| 21 | PTSPIANI_COD_LIV3 | CHAR(5) |  |  |
| 22 | PTSPIANI_DTINIZIO | DECIMAL(9,0) |  |  |
| 23 | XPTSPIANI_DTINIZIO | DECIMAL(9,0) |  |  |
| 24 | PTSPIANI_DTFINE | DECIMAL(9,0) |  |  |
| 25 | XPTSPIANI_DTFINE | DECIMAL(9,0) |  |  |
| 26 | XPTSPIANI_COD_LIV3 | CHAR(5) |  |  |
| 27 | PTSPIANI_FREQUENZA | CHAR(1) | N |  |
| 28 | PTSPIANI_ULLA | CHAR(6) | N |  |
| 29 | PTSPIANI_ISIN | CHAR(12) | N |  |
| 30 | PTSPIANI_LINEA | CHAR(5) | N |  |
| 31 | PTSPIANI_DECOR | DECIMAL(6,0) | N |  |

Indici:

- `PTSPIANID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_PTVCG_CD

*Tabella* – righe: 15.428
– change data della tabella `PTVCG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | PTVCG_CODCONF | CHAR(11) | N |  |
| 5 | PTVCG_CODPROD | CHAR(2) | N |  |
| 6 | PTVCG_SUBPROD | CHAR(5) | N |  |
| 7 | PTVCG_CODPIANO | CHAR(20) | N |  |
| 8 | PTVCG_TIPOVAR | CHAR(2) | N |  |
| 9 | PTVCG_STATO | CHAR(1) | N |  |
| 10 | PTVCG_DTINS | DECIMAL(9,0) | N |  |
| 11 | PTVCG_DTINV | DECIMAL(9,0) | N |  |
| 12 | PTVCG_DTESEG | DECIMAL(9,0) | N |  |
| 13 | PTVCG_FREQUENZA | CHAR(2) | N |  |
| 14 | PTVCG_DTATTIV | DECIMAL(9,0) | N |  |
| 15 | PTVCG_IMPORTO | DECIMAL(15,2) | N |  |
| 16 | PTVCG_MOPAG | CHAR(5) | N |  |
| 17 | PTVCG_CIN | CHAR(1) | N |  |
| 18 | PTVCG_ABI | CHAR(5) | N |  |
| 19 | PTVCG_CAB | CHAR(5) | N |  |
| 20 | PTVCG_CONTO | CHAR(12) | N |  |
| 21 | PTVCG_DURATA | DECIMAL(3,0) | N |  |
| 22 | PTVCG_SUBPNEW | CHAR(5) | N |  |
| 23 | PTVCG_FLUSSOIN | CHAR(8) | N |  |
| 24 | PTVCG_FLUSSORC | CHAR(8) | N |  |
| 25 | PTVCG_RETE | CHAR(1) | N |  |
| 26 | PTVCG_NAZIOIBAN | CHAR(2) | N |  |
| 27 | PTVCG_CINIBAN | CHAR(2) | N |  |
| 28 | PTVCG_DTFINE | DECIMAL(9,0) | N |  |

Indici:

- `PTVCGD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_QUOTEGP_CD

*Tabella* – righe: 153.947.574
– change data della tabella `QUOTEGP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | QUOTEGP_DVALUTA | DECIMAL(9,0) | N |  |
| 5 | QUOTEGP_CODCONF | CHAR(11) | N |  |
| 6 | QUOTEGP_CODPROD | CHAR(2) | N |  |
| 7 | QUOTEGP_SUBPROD | CHAR(5) | N |  |
| 8 | QUOTEGP_ISIN | CHAR(12) | N |  |
| 9 | QUOTEGP_QUOTE | DECIMAL(15,3) | N |  |
| 10 | QUOTEGP_CTRVALORE | DECIMAL(15,2) | N |  |
| 11 | QUOTEGP_RETE | CHAR(1) | N |  |
| 12 | QUOTEGP_TIPO | CHAR(3) | N |  |
| 13 | XQUOTEGP_DVALUTA | DECIMAL(9,0) |  |  |
| 14 | XQUOTEGP_CODCONF | CHAR(11) |  |  |
| 15 | XQUOTEGP_SUBPROD | CHAR(5) |  |  |
| 16 | XQUOTEGP_ISIN | CHAR(12) |  |  |
| 17 | XQUOTEGP_RETE | CHAR(1) |  |  |

Indici:

- `QUOTEGPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_QUOTESK_CD

*Tabella* – righe: 180.715
– change data della tabella `QUOTESK`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | QUOTESK_DVALNAV | DECIMAL(9,0) | N |  |
| 5 | QUOTESK_CODCONF | CHAR(11) | N |  |
| 6 | QUOTESK_CODPROD | CHAR(2) | N |  |
| 7 | QUOTESK_SUBPROD | CHAR(5) | N |  |
| 8 | QUOTESK_ISIN | CHAR(12) | N |  |
| 9 | QUOTESK_QUOTE | DECIMAL(15,7) | N |  |
| 10 | QUOTESK_CTRVALORE | DECIMAL(15,2) | N |  |
| 11 | QUOTESK_RETE | CHAR(1) | N |  |
| 12 | QUOTESK_TIPO | CHAR(3) | N |  |
| 13 | QUOTESK_DTCOMPMF | DECIMAL(9,0) | N |  |
| 14 | QUOTESK_CODULLA | CHAR(6) | N |  |
| 15 | QUOTESK_VALNAV | DECIMAL(15,7) | N |  |
| 16 | QUOTESK_DATAVAL | DECIMAL(9,0) | N |  |

Indici:

- `QUOTESKD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_QUOTE_CD

*Tabella* – righe: 1.987.849
– change data della tabella `QUOTE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | QUOTE_DVALNAV | DECIMAL(9,0) | N |  |
| 5 | QUOTE_CODCONF | CHAR(11) | N |  |
| 6 | QUOTE_CODPROD | CHAR(2) | N |  |
| 7 | QUOTE_SUBPROD | CHAR(5) | N |  |
| 8 | QUOTE_SALDO | DECIMAL(15,3) | N |  |
| 9 | QUOTE_RETE | CHAR(1) | N |  |
| 10 | QUOTE_COD_LIV3 | CHAR(5) | N |  |
| 11 | QUOTE_COD_LIV2 | CHAR(5) | N |  |
| 12 | XQUOTE_DVALNAV | DECIMAL(9,0) |  |  |
| 13 | XQUOTE_CODCONF | CHAR(11) |  |  |
| 14 | XQUOTE_SUBPROD | CHAR(5) |  |  |
| 15 | XQUOTE_RETE | CHAR(1) |  |  |
| 16 | XQUOTE_COD_LIV3 | CHAR(5) |  |  |
| 17 | XQUOTE_COD_LIV2 | CHAR(5) |  |  |

Indici:

- `QUOTED01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_QVALP_CD

*Tabella* – righe: 0
– change data della tabella `QVALP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | QVALP_CODCONF | CHAR(11) | N |  |
| 6 | QVALP_NUMPOL | CHAR(7) | N |  |
| 7 | QVALP_DVALORIZ | DATE | N |  |
| 8 | QVALP_VALPOL | DECIMAL(15,2) | N |  |
| 9 | QVALP_STATUS | CHAR(1) |  |  |

Indici:

- `QVALPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RAMO1_CD

*Tabella* – righe: 1.168
– change data della tabella `RAMO1`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RAMO1_CODCONF | CHAR(11) | N |  |
| 5 | RAMO1_CODPROD | CHAR(2) | N |  |
| 6 | RAMO1_NUMPOL | CHAR(11) | N |  |
| 7 | RAMO1_STATOPOL | CHAR(2) | N |  |
| 8 | RAMO1_STAPOLDET | CHAR(2) | N |  |
| 9 | RAMO1_PRODEST | CHAR(5) | N |  |
| 10 | RAMO1_DIVISA | CHAR(3) | N |  |
| 11 | RAMO1_IMPCAP | DECIMAL(15,2) | N |  |
| 12 | RAMO1_IMPREND | DECIMAL(15,2) | N |  |

Indici:

- `RAMO1D01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RAMODANNI_CD

*Tabella* – righe: 81
– change data della tabella `RAMODANNI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RAMODANNI_CODCONF | CHAR(11) | N |  |
| 5 | RAMODANNI_CODPROD | CHAR(2) | N |  |
| 6 | RAMODANNI_NUMPOL | CHAR(20) | N |  |
| 7 | RAMODANNI_NUMPRE | CHAR(11) | N |  |
| 8 | RAMODANNI_STATO | CHAR(1) | N |  |
| 9 | RAMODANNI_FRZ | SMALLINT | N |  |
| 10 | RAMODANNI_PERC_SCONTO | DECIMAL(5,2) | N |  |
| 11 | RAMODANNI_DT_DECORRENZA | DECIMAL(9,0) | N |  |
| 12 | RAMODANNI_ORA_DECORRENZA | DECIMAL(6,0) | N |  |
| 13 | RAMODANNI_DT_SOSPENSIONE | DECIMAL(9,0) | N |  |
| 14 | RAMODANNI_ORA_SOSPENSIONE | DECIMAL(6,0) | N |  |
| 15 | RAMODANNI_DT_SCADENZA | DECIMAL(9,0) | N |  |
| 16 | RAMODANNI_ORA_SCADENZA | DECIMAL(6,0) | N |  |
| 17 | RAMODANNI_PREMIO_LORDO_ANNUO | DECIMAL(13,2) | N |  |
| 18 | RAMODANNI_PREMIO_NETTO_ANNUO | DECIMAL(13,2) | N |  |
| 19 | RAMODANNI_IMPOSTE_PREMIO_ANNUO | DECIMAL(13,2) | N |  |
| 20 | RAMODANNI_IMP_PREST_LORDO | DECIMAL(13,2) | N |  |
| 21 | RAMODANNI_IMP_PREST_NETTO | DECIMAL(13,2) | N |  |
| 22 | RAMODANNI_IMPOSTE_PRESTAZ | DECIMAL(13,2) | N |  |
| 23 | RAMODANNI_PREMIO_LORDO_MENSILE | DECIMAL(13,2) | N |  |
| 24 | RAMODANNI_PREMIO_NETTO_MENSILE | DECIMAL(13,2) | N |  |
| 25 | RAMODANNI_IMPOSTE_MENSILI | DECIMAL(13,2) | N |  |
| 26 | RAMODANNI_PAYIN_STIMATO | DECIMAL(13,2) | N |  |
| 27 | RAMODANNI_PAYIN | DECIMAL(13,2) | N |  |
| 28 | RAMODANNI_PAYOUT | DECIMAL(13,2) | N |  |

Indici:

- `RAMODANNID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RAMOV_CD

*Tabella* – righe: 134.562
– change data della tabella `RAMOV`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RAMOV_CODCONF | CHAR(11) | N |  |
| 5 | RAMOV_CODPROD | CHAR(2) | N |  |
| 6 | RAMOV_SUBPROD | CHAR(5) | N |  |
| 7 | RAMOV_CSOCGES | CHAR(2) | N |  |
| 8 | RAMOV_PROGMOV | SMALLINT | N |  |
| 9 | RAMOV_PROGTEC | SMALLINT | N |  |
| 10 | RAMOV_RAGROP | CHAR(2) | N |  |
| 11 | RAMOV_CAUSALE | CHAR(10) | N |  |
| 12 | RAMOV_FLAGESE | CHAR(1) | N |  |
| 13 | RAMOV_DTESTRA | DECIMAL(9,0) | N |  |
| 14 | RAMOV_DNAVAL | DECIMAL(9,0) | N |  |
| 15 | RAMOV_DVALNAV | DECIMAL(9,0) | N |  |
| 16 | RAMOV_IMPOPER | DECIMAL(15,2) | N |  |
| 17 | RAMOV_SPESE | DECIMAL(15,2) | N |  |
| 18 | RAMOV_RA_CED | DECIMAL(15,2) | N |  |
| 19 | RAMOV_NETINVS | DECIMAL(15,2) | N |  |
| 20 | RAMOV_VALNAV | DECIMAL(15,3) | N |  |
| 21 | RAMOV_PRTOPER | DECIMAL(15,3) | N |  |
| 22 | RAMOV_OLD_SALQUO | DECIMAL(15,3) | N |  |
| 23 | RAMOV_NEW_SALQUO | DECIMAL(15,3) | N |  |
| 24 | RAMOV_OLD_PMC | DECIMAL(15,6) | N |  |
| 25 | RAMOV_NEW_PMC | DECIMAL(15,6) | N |  |
| 26 | RAMOV_PLUS | DECIMAL(15,2) | N |  |
| 27 | RAMOV_MINUS_TOT | DECIMAL(15,2) | N |  |
| 28 | RAMOV_MINUS | DECIMAL(15,2) | N |  |
| 29 | RAMOV_MINUS_SPS | DECIMAL(15,2) | N |  |
| 30 | RAMOV_IMPCERT | DECIMAL(15,2) | N |  |
| 31 | RAMOV_RA | DECIMAL(15,2) | N |  |
| 32 | RAMOV_IMPLIQ | DECIMAL(15,2) | N |  |
| 33 | RAMOV_OLD_SALSPE | DECIMAL(15,2) | N |  |
| 34 | RAMOV_NEW_SALSPE | DECIMAL(15,2) | N |  |
| 35 | RAMOV_OLD_PROQUO | DECIMAL(15,8) | N |  |
| 36 | RAMOV_NEW_PROQUO | DECIMAL(15,8) | N |  |
| 37 | RAMOV_IDMOVIM | CHAR(50) | N |  |
| 38 | RAMOV_DELABOR | DECIMAL(9,0) | N |  |
| 39 | RAMOV_TIPO_RA | CHAR(2) | N |  |
| 40 | RAMOV_ISPSLIQ | DECIMAL(15,2) | N |  |
| 41 | RAMOV_RETE | CHAR(1) | N |  |
| 42 | RAMOV_IMPOTAX | DECIMAL(15,2) | N |  |
| 43 | RAMOV_IMPOCAP | DECIMAL(15,2) | N |  |

Indici:

- `RAMOVD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RASAL_CD

*Tabella* – righe: 101.438
– change data della tabella `RASAL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RASAL_CODCONF | CHAR(11) | N |  |
| 5 | RASAL_CODPROD | CHAR(2) | N |  |
| 6 | RASAL_SUBPROD | CHAR(5) | N |  |
| 7 | RASAL_CSOCGES | CHAR(2) | N |  |
| 8 | RASAL_LASTMOV | SMALLINT | N |  |
| 9 | RASAL_LASTTEC | SMALLINT | N |  |
| 10 | RASAL_FLAGESE | CHAR(1) | N |  |
| 11 | RASAL_RFA | DECIMAL(15,2) | N |  |
| 12 | RASAL_SALSPE | DECIMAL(15,2) | N |  |
| 13 | RASAL_SALQUO | DECIMAL(15,3) | N |  |
| 14 | RASAL_PMC | DECIMAL(15,6) | N |  |
| 15 | RASAL_DVALNAV | DECIMAL(9,0) | N |  |
| 16 | RASAL_SALPLUS | DECIMAL(15,2) | N |  |
| 17 | RASAL_SALMINUS | DECIMAL(15,2) | N |  |
| 18 | RASAL_SALCERT | DECIMAL(15,2) | N |  |
| 19 | RASAL_SALRA | DECIMAL(15,2) | N |  |
| 20 | RASAL_LIQUID | DECIMAL(15,2) | N |  |
| 21 | RASAL_PROQUO | DECIMAL(15,8) | N |  |
| 22 | RASAL_DNAVAL | DECIMAL(9,0) | N |  |
| 23 | RASAL_VALNAV | DECIMAL(15,3) | N |  |
| 24 | RASAL_DATE | DECIMAL(9,0) | N |  |
| 25 | RASAL_RETE | CHAR(1) | N |  |
| 26 | RASAL_QUOTELIQ_IMPIANTO | DECIMAL(13,3) | N |  |
| 27 | RASAL_PROQUOTA_QUOTELIQ | DECIMAL(15,8) | N |  |

Indici:

- `RASALD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RCDMCC_CD

*Tabella* – righe: 2.445.748
– change data della tabella `RCDMCC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RCDMCC_CODAGE | CHAR(6) | N |  |
| 5 | RCDMCC_CODCONF | CHAR(11) | N |  |
| 6 | RCDMCC_CONTO | CHAR(12) | N |  |
| 7 | RCDMCC_DATAMOV | DECIMAL(8,0) | N |  |
| 8 | RCDMCC_DATACON | DECIMAL(8,0) | N |  |
| 9 | RCDMCC_IMPORTO | DECIMAL(15,2) | N |  |
| 10 | RCDMCC_CAUSALE | CHAR(3) | N |  |
| 11 | RCDMCC_FLAGRIASS | CHAR(1) | N |  |
| 12 | RCDMCC_OLDAGE | CHAR(6) | N |  |
| 13 | RCDMCC_COGNOME | CHAR(25) | N |  |
| 14 | RCDMCC_NOME | CHAR(25) | N |  |
| 15 | RCDMCC_NPROGM | CHAR(25) | N |  |
| 16 | RCDMCC_DTCARIC | DECIMAL(8,0) | N |  |
| 17 | RCDMCC_CACLI | CHAR(2) | N |  |
| 18 | RCDMCC_DTINCEN | DECIMAL(8,0) | N | DATA INCENTIVAZIONE |

Indici:

- `RCDMCCD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RENCO_CD

*Tabella* – righe: 648.853
– change data della tabella `RENCO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RENCO_CODAGE | CHAR(6) | N |  |
| 5 | XRENCO_CODAGE | CHAR(6) |  |  |
| 6 | RENCO_CODCONF | CHAR(11) | N |  |
| 7 | XRENCO_CODCONF | CHAR(11) |  |  |
| 8 | RENCO_CODPROD | CHAR(2) | N |  |
| 9 | XRENCO_CODPROD | CHAR(2) |  |  |
| 10 | RENCO_SUBPROD | CHAR(5) | N |  |
| 11 | XRENCO_SUBPROD | CHAR(5) |  |  |
| 12 | RENCO_PROGMOV | SMALLINT | N |  |
| 13 | XRENCO_PROGMOV | SMALLINT |  |  |
| 14 | RENCO_PROGOPE | SMALLINT | N |  |
| 15 | XRENCO_PROGOPE | SMALLINT |  |  |
| 16 | RENCO_TIPOPER | CHAR(2) | N |  |
| 17 | XRENCO_TIPOPER | CHAR(2) |  |  |
| 18 | RENCO_TIPOPES | CHAR(2) | N |  |
| 19 | XRENCO_TIPOPES | CHAR(2) |  |  |
| 20 | RENCO_DVALUTA | DECIMAL(9,0) | N |  |
| 21 | XRENCO_DVALUTA | DECIMAL(9,0) |  |  |
| 22 | RENCO_IMPORTO | DECIMAL(15,0) | N |  |
| 23 | RENCO_FLAGEL | CHAR(1) | N |  |
| 24 | RENCO_FAMPROD | CHAR(1) | N |  |
| 25 | RENCO_TIPROD | CHAR(1) | N |  |
| 26 | RENCO_TIPCON | CHAR(1) | N |  |
| 27 | RENCO_OPER | CHAR(1) | N |  |
| 28 | RENCO_MOPAG | CHAR(1) | N |  |
| 29 | XRENCO_MOPAG | CHAR(1) |  |  |
| 30 | RENCO_COGNOME | CHAR(25) | N |  |
| 31 | RENCO_NOME | CHAR(25) | N |  |
| 32 | RENCO_TIPVEN | CHAR(1) | N |  |
| 33 | RENCO_PRSPLIT | DECIMAL(3,0) | N |  |
| 34 | RENCO_DELABOR | DECIMAL(9,0) | N |  |
| 35 | RENCO_DVOLUME | DECIMAL(9,0) | N |  |
| 36 | RENCO_TIPRAC | CHAR(1) | N |  |
| 37 | RENCO_FLAGREN | CHAR(1) | N |  |
| 38 | RENCO_DTCAR | DECIMAL(9,0) | N |  |
| 39 | RENCO_DTRIASS | DECIMAL(9,0) | N |  |
| 40 | RENCO_FLAGRIASS | CHAR(1) | N |  |
| 41 | RENCO_IMPEURO | DECIMAL(15,2) | N |  |
| 42 | RENCO_CODDIV | CHAR(3) | N |  |
| 43 | RENCO_FLAGPCT | CHAR(1) | N |  |
| 44 | RENCO_DTFCN99 | DECIMAL(9,0) | N |  |
| 45 | RENCO_DISINV | CHAR(11) | N |  |
| 46 | RENCO_DTSPED | DECIMAL(9,0) | N |  |
| 47 | RENCO_ORASPED | DECIMAL(9,0) | N |  |
| 48 | RENCO_DTINCEN | DECIMAL(9,0) | N |  |
| 49 | RENCO_COD_LIV2 | CHAR(5) |  |  |
| 50 | XRENCO_COD_LIV2 | CHAR(5) |  |  |
| 51 | RENCO_CODAGE_RICH | CHAR(6) | N |  |

Indici:

- `RENCOD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RFAPBTOP_CD

*Tabella* – righe: 0
– change data della tabella `RFAPBTOP`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RETE | CHAR(1) | N |  |
| 5 | CODAGE | CHAR(6) | N |  |
| 6 | CODANA | CHAR(12) | N |  |
| 7 | PRESSO | CHAR(32) | N |  |
| 8 | DATARFA | DECIMAL(9,0) | N |  |
| 9 | RFA_GES_IST | DECIMAL(15,2) | N |  |
| 10 | RFA_GES_PRI | DECIMAL(15,2) | N |  |
| 11 | RFA_AMM_IST | DECIMAL(15,2) | N |  |
| 12 | RFA_AMM_PRI | DECIMAL(15,2) | N |  |
| 13 | RFA_SEI_IST | DECIMAL(15,2) | N |  |
| 14 | RFA_SEI_PRI | DECIMAL(15,2) | N |  |
| 15 | FLG_PROFILATO | CHAR(2) |  |  |
| 16 | RFA_VINC_IST | DECIMAL(15,2) |  |  |
| 17 | RFA_VINC_PRI | DECIMAL(15,2) |  |  |

Indici:

- `RFAPBTOPD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RGPF_CD5

*Tabella* – righe: 0
– change data della tabella `RGPF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | RGPF_CODCONF | CHAR(11) | N |  |
| 6 | RGPF_CCON | CHAR(8) | N |  |
| 7 | RGPF_DVALORIZ | DECIMAL(9,0) | N |  |
| 8 | RGPF_DTINIZ | DECIMAL(9,0) | N |  |
| 9 | RGPF_RENDINIZ | DECIMAL(7,4) | N |  |
| 10 | RGPF_DTANNO | DECIMAL(9,0) | N |  |
| 11 | RGPF_RENDANNO | DECIMAL(7,4) | N |  |
| 12 | RGPF_DTRUN | DECIMAL(9,0) | N |  |
| 13 | RGPF_RENDRUN | DECIMAL(7,4) | N |  |
| 14 | RGPF_PATRN | DECIMAL(15,0) | N |  |
| 15 | RGPF_BENCHINIZ | DECIMAL(7,4) | N |  |
| 16 | RGPF_BENCHANNO | DECIMAL(7,4) | N |  |
| 17 | RGPF_BENCHRUN | DECIMAL(7,4) | N |  |
| 18 | RGPF_EPATRN | DECIMAL(15,2) | N |  |
| 19 | RGPF_DTTRIM | DECIMAL(9,0) | N |  |
| 20 | RGPF_RENDTRIM | DECIMAL(7,4) | N |  |
| 21 | RGPF_BENCHTRIM | DECIMAL(7,4) | N |  |
| 22 | RGPF_RETE | CHAR(1) | N | INDICATORE RETE VENDITA |
| 23 | RGPF_SUBPROD | CHAR(5) | N | CODICE SOTTOPRODOTTO |

Indici:

- `ASN_RGPF_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RIC_CD

*Tabella* – righe: 83.202
– change data della tabella `RIC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RIC_NUMINV | CHAR(4) | N |  |
| 5 | RIC_PRGBON | CHAR(5) | N |  |
| 6 | RIC_PRGSPLIT | CHAR(6) | N |  |
| 7 | RIC_PRGGEN | CHAR(6) | N |  |
| 8 | RIC_DTINV | CHAR(8) | N |  |
| 9 | RIC_NMOD | CHAR(11) | N |  |
| 10 | RIC_NOM | CHAR(15) | N |  |
| 11 | RIC_COGN | CHAR(20) | N |  |
| 12 | RIC_IMP | DECIMAL(15,0) | N |  |
| 13 | RIC_DISINV | CHAR(11) | N |  |
| 14 | RIC_DTVAL | CHAR(8) | N |  |
| 15 | RIC_DTACQ | CHAR(8) | N |  |
| 16 | RIC_DTCONT | CHAR(8) | N |  |
| 17 | RIC_DTACFID | CHAR(8) | N |  |
| 18 | RIC_ABI | CHAR(5) | N |  |
| 19 | RIC_CAB | CHAR(5) | N |  |
| 20 | RIC_CONTOCLI | CHAR(30) | N |  |
| 21 | RIC_FELA | CHAR(1) | N |  |
| 22 | RIC_CONTR | CHAR(1) | N |  |
| 23 | RIC_DTELA | CHAR(8) | N |  |
| 24 | RIC_MOPAG | CHAR(1) | N |  |
| 25 | RIC_BAFID | CHAR(3) | N |  |
| 26 | RIC_DESCR | CHAR(20) | N |  |
| 27 | RIC_DTEL0 | CHAR(8) | N |  |
| 28 | RIC_CODBR01 | CHAR(4) | N |  |
| 29 | RIC_CODBR02 | CHAR(6) | N |  |
| 30 | RIC_CODBR03 | CHAR(10) | N |  |
| 31 | RIC_TIPOPER | CHAR(2) | N |  |
| 32 | RIC_NUMMOVL | SMALLINT | N |  |
| 33 | RIC_CODCONF | CHAR(11) | N |  |
| 34 | RIC_MITT | CHAR(8) | N |  |
| 35 | RIC_DTAGZ | CHAR(6) | N |  |
| 36 | RIC_NPROGR | CHAR(2) | N |  |
| 37 | RIC_NUMASS | CHAR(12) | N |  |
| 38 | RIC_NMODPRE | CHAR(11) | N |  |
| 39 | RIC_DTADDE | CHAR(8) | N |  |
| 40 | RIC_ESADD1 | CHAR(1) | N |  |
| 41 | RIC_ESFEL1 | CHAR(1) | N |  |
| 42 | RIC_ESADD2 | CHAR(1) | N |  |
| 43 | RIC_ESFEL2 | CHAR(1) | N |  |
| 44 | RIC_POSMAND | CHAR(1) | N |  |
| 45 | RIC_CODASS | CHAR(1) | N |  |
| 46 | RIC_RESIDENZA | CHAR(1) | N |  |
| 47 | RIC_IMPEURO | DECIMAL(15,2) | N |  |
| 48 | RIC_CODDIV | CHAR(3) | N |  |
| 49 | RIC_SCACONV | DECIMAL(6,5) | N |  |
| 50 | RIC_DTCONEURO | DECIMAL(9,0) | N |  |
| 51 | RIC_TIMER | DECIMAL(13,0) | N |  |
| 52 | RIC_TIMERICH | DECIMAL(13,0) | N |  |
| 53 | RIC_DTPREL | DECIMAL(9,0) | N |  |
| 54 | RIC_UTENTERICH | CHAR(10) | N |  |
| 55 | RIC_CODPROD | CHAR(2) | N |  |
| 56 | RIC_FNAVR | CHAR(1) | N |  |
| 57 | RIC_RETE | CHAR(1) | N |  |
| 58 | RIC_DISINVSPI | CHAR(14) | N |  |
| 59 | RIC_DATAPP | DECIMAL(9,0) | N |  |
| 60 | RIC_ESITOPP | CHAR(1) | N |  |
| 61 | RIC_CONTAPP | DECIMAL(3,0) | N |  |
| 62 | RIC_FILIALE | CHAR(3) | N |  |
| 63 | RIC_CIN | CHAR(1) | N |  |
| 64 | RIC_NAZIOIBAN | CHAR(2) | N |  |
| 65 | RIC_CINIBAN | CHAR(2) | N |  |
| 66 | RIC_CDFIS01 | CHAR(16) | N |  |
| 67 | RIC_CODFID | CHAR(5) | N |  |
| 68 | RIC_DATA_INPUT | DECIMAL(9,0) | N | DATA INPUT |
| 69 | RIC_SUBPROD | CHAR(5) |  |  |

Indici:

- `RICD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RIN1_CD5

*Tabella* – righe: 0
– change data della tabella `RIN1`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | RIN1_CODCONF | CHAR(11) | N |  |
| 6 | RIN1_TIPORICH | CHAR(1) | N |  |

Indici:

- `ASN_RIN1_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RINCAS_CD

*Tabella* – righe: 922.059
– change data della tabella `RINCAS`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RINCAS_CODCONF | CHAR(11) | N |  |
| 5 | RINCAS_CODPROD | CHAR(2) | N |  |
| 6 | RINCAS_DATCONT | DECIMAL(9,0) | N |  |
| 7 | RINCAS_TIPOMOV | CHAR(1) | N |  |
| 8 | RINCAS_PROGINC | SMALLINT | N |  |
| 9 | RINCAS_TIPORIM | CHAR(1) | N |  |
| 10 | RINCAS_TIPOPER | CHAR(2) | N |  |
| 11 | RINCAS_TIPOPES | CHAR(2) | N |  |
| 12 | RINCAS_STATO | CHAR(1) | N |  |
| 13 | RINCAS_INDIRR | CHAR(1) | N |  |
| 14 | RINCAS_NUMINV | CHAR(4) | N |  |
| 15 | RINCAS_PROGINV | CHAR(5) | N |  |
| 16 | RINCAS_IMPORIM | DECIMAL(15,0) | N |  |
| 17 | RINCAS_DVALFND | DECIMAL(9,0) | N |  |
| 18 | RINCAS_DRICEZ | DECIMAL(9,0) | N |  |
| 19 | RINCAS_NUMASS | CHAR(20) | N |  |
| 20 | RINCAS_NUMBON | CHAR(20) | N |  |
| 21 | RINCAS_DISINV | CHAR(11) | N |  |
| 22 | RINCAS_CODDIST | CHAR(15) | N |  |
| 23 | RINCAS_ABI | CHAR(5) | N |  |
| 24 | RINCAS_CAB | CHAR(5) | N |  |
| 25 | RINCAS_CONTO | CHAR(12) | N |  |
| 26 | RINCAS_MANDPAG | CHAR(2) | N |  |
| 27 | RINCAS_DELABOR | DECIMAL(9,0) | N |  |
| 28 | RINCAS_VD | CHAR(1) | N |  |
| 29 | RINCAS_CODDIP | CHAR(2) | N |  |
| 30 | RINCAS_MITT | CHAR(8) | N |  |
| 31 | RINCAS_DTAGZ | CHAR(6) | N |  |
| 32 | RINCAS_NPROGR | CHAR(2) | N |  |
| 33 | RINCAS_DTADDE | CHAR(8) | N |  |
| 34 | RINCAS_ESADD1 | CHAR(1) | N |  |
| 35 | RINCAS_ESFEL1 | CHAR(1) | N |  |
| 36 | RINCAS_ESADD2 | CHAR(1) | N |  |
| 37 | RINCAS_ESFEL2 | CHAR(1) | N |  |
| 38 | RINCAS_OLDCOD | CHAR(11) | N |  |
| 39 | RINCAS_CODASS | CHAR(1) | N |  |
| 40 | RINCAS_RESIDENZA | CHAR(1) | N |  |
| 41 | RINCAS_TITORD | CHAR(1) | N |  |
| 42 | RINCAS_IMPEURO | DECIMAL(15,2) | N |  |
| 43 | RINCAS_CODDIV | CHAR(3) | N |  |
| 44 | RINCAS_TIMER | DECIMAL(13,0) | N |  |
| 45 | RINCAS_TIMERICH | DECIMAL(13,0) | N |  |
| 46 | RINCAS_SCACONV | DECIMAL(6,5) | N |  |
| 47 | RINCAS_DTCONEURO | DECIMAL(9,0) | N |  |
| 48 | RINCAS_DTAUTOG | DECIMAL(9,0) | N |  |
| 49 | RINCAS_DTPREL | DECIMAL(9,0) | N |  |
| 50 | RINCAS_PAGABILE | DECIMAL(15,2) | N |  |
| 51 | RINCAS_UTENTERICH | CHAR(10) | N |  |
| 52 | RINCAS_FNAVR | CHAR(1) | N |  |
| 53 | RINCAS_STPARAL | CHAR(2) | N |  |
| 54 | RINCAS_MULTI | CHAR(1) | N |  |
| 55 | RINCAS_RETE | CHAR(1) | N |  |
| 56 | RINCAS_DISINVSPI | CHAR(14) | N |  |
| 57 | RINCAS_DATAPP | DECIMAL(9,0) | N |  |
| 58 | RINCAS_ESITOPP | CHAR(1) | N |  |
| 59 | RINCAS_CONTAPP | DECIMAL(3,0) | N |  |
| 60 | RINCAS_FILIALE | CHAR(3) | N |  |
| 61 | RINCAS_CIN | CHAR(1) | N |  |
| 62 | RINCAS_NAZIOIBAN | CHAR(2) | N |  |
| 63 | RINCAS_CINIBAN | CHAR(2) | N |  |
| 64 | RINCAS_DATA_INPUT | DECIMAL(9,0) | N | DATA INPUT |
| 65 | RINCAS_SUBPROD | CHAR(5) |  |  |

Indici:

- `RINCASD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_RNREG_CD

*Tabella* – righe: 0
– change data della tabella `RNREG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | RNREG_PROC | CHAR(8) | N |  |
| 5 | RNREG_CODPROD | CHAR(2) | N |  |
| 6 | RNREG_SUBPROD | CHAR(5) | N |  |
| 7 | RNREG_TIPOPER | CHAR(2) | N |  |
| 8 | RNREG_TIPOPES | CHAR(2) | N |  |
| 9 | RNREG_CODDAT | CHAR(4) | N |  |
| 10 | RNREG_FCONT | CHAR(1) | N |  |

Indici:

- `RNREGD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_SLIV1A_CD

*Tabella* – righe: 20.378.877
– change data della tabella `SLIV1A`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | SLIV1A_CODCONF | CHAR(11) | N |  |
| 5 | SLIV1A_CODPROD | CHAR(2) | N |  |
| 6 | SLIV1A_COD_LIV3 | CHAR(5) | N |  |
| 7 | SLIV1A_COD_LIV2 | CHAR(5) | N |  |
| 8 | SLIV1A_SUBPROD | CHAR(5) | N |  |
| 9 | SLIV1A_COD_STATO | CHAR(1) | N |  |
| 10 | SLIV1A_COD_RETE | CHAR(1) | N |  |
| 11 | SLIV1A_IMP_INVEST | DECIMAL(15,2) | N |  |
| 12 | SLIV1A_IMP_LIQUID | DECIMAL(15,2) | N |  |
| 13 | SLIV1A_DT_VALNAV | DECIMAL(9,0) | N |  |
| 14 | SLIV1A_DT_NAVAL | DECIMAL(9,0) | N |  |
| 15 | SLIV1A_QUOTE_ACQS | DECIMAL(15,7) | N |  |
| 16 | SLIV1A_QUOTE_TRASF | DECIMAL(15,7) | N |  |
| 17 | SLIV1A_QUOTE_LIQD | DECIMAL(15,7) | N |  |
| 18 | SLIV1A_QUOTE_RIFS | DECIMAL(15,7) | N |  |
| 19 | SLIV1A_VALNAV | DECIMAL(13,5) | N |  |
| 20 | SLIV1A_IMP_CTV_QUOTE | DECIMAL(15,2) | N |  |
| 21 | SLIV1A_QUOTE_BONUS | DECIMAL(15,7) | N |  |
| 22 | SLIV1A_IMP_CTV_BONUS | DECIMAL(15,2) | N |  |
| 23 | SLIV1A_VALNAV_PROT | DECIMAL(13,5) | N |  |
| 24 | SLIV1A_IMP_CTV_PROT | DECIMAL(15,2) | N |  |
| 25 | SLIV1A_IMP_CARICAM | DECIMAL(15,2) | N |  |
| 26 | SLIV1A_IMP_TASSE | DECIMAL(15,2) | N |  |
| 27 | SLIV1A_IMP_SPSLIQ | DECIMAL(15,2) | N |  |
| 28 | SLIV1A_IMP_SPSAMMI | DECIMAL(15,2) | N |  |
| 29 | SLIV1A_IMP_CGEST | DECIMAL(15,2) | N |  |
| 30 | SLIV1A_IMP_CMORTE | DECIMAL(15,2) | N |  |
| 31 | SLIV1A_IMP_PENALI | DECIMAL(15,2) | N |  |
| 32 | SLIV1A_IMP_NETTO | DECIMAL(15,2) | N |  |
| 33 | SLIV1A_IMP_PURO | DECIMAL(15,2) | N |  |
| 34 | SLIV1A_IMP_INVBONUS | DECIMAL(15,2) | N |  |
| 35 | SLIV1A_IMP_LIQBONUS | DECIMAL(15,2) | N |  |

Indici:

- `SLIV1AD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_SLIV2A_CD

*Tabella* – righe: 10.080.006
– change data della tabella `SLIV2A`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | SLIV2A_CODCONF | CHAR(11) | N |  |
| 5 | XSLIV2A_CODCONF | CHAR(11) |  |  |
| 6 | SLIV2A_CODPROD | CHAR(2) | N |  |
| 7 | XSLIV2A_CODPROD | CHAR(2) |  |  |
| 8 | SLIV2A_COD_LIV3 | CHAR(5) | N |  |
| 9 | SLIV2A_COD_LIV2 | CHAR(5) | N |  |
| 10 | XSLIV2A_COD_LIV2 | CHAR(5) |  |  |
| 11 | SLIV2A_COD_STATO | CHAR(1) | N |  |
| 12 | SLIV2A_COD_PORTMOD | CHAR(5) | N |  |
| 13 | SLIV2A_PRC_CORE | DECIMAL(7,3) | N |  |
| 14 | SLIV2A_IMP_CTV_TOT | DECIMAL(15,2) | N |  |
| 15 | SLIV2A_IMP_FLOOR | DECIMAL(15,2) | N |  |
| 16 | SLIV2A_IMP_INVEST | DECIMAL(15,2) | N |  |
| 17 | SLIV2A_IMP_LIQUID | DECIMAL(15,2) | N |  |
| 18 | SLIV2A_IMP_CARICAM | DECIMAL(15,2) | N |  |
| 19 | SLIV2A_IMP_TASSE | DECIMAL(15,2) | N |  |
| 20 | SLIV2A_IMP_SPSLIQ | DECIMAL(15,2) | N |  |
| 21 | SLIV2A_IMP_SPSAMMI | DECIMAL(15,2) | N |  |
| 22 | SLIV2A_IMP_CGEST | DECIMAL(15,2) | N |  |
| 23 | SLIV2A_IMP_CMORTE | DECIMAL(15,2) | N |  |
| 24 | SLIV2A_IMP_PENALI | DECIMAL(15,2) | N |  |
| 25 | SLIV2A_IMP_NETTO | DECIMAL(15,2) | N |  |
| 26 | SLIV2A_IMP_PURO | DECIMAL(15,2) | N |  |
| 27 | SLIV2A_IMP_AVALUE | DECIMAL(15,2) |  |  |
| 28 | SLIV2A_PRC_PROTEZ | DECIMAL(7,3) |  |  |
| 29 | SLIV2A_IMP_CTV_MONET | DECIMAL(15,2) |  |  |

Indici:

- `SLIV2AD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_SPLI_CD

*Tabella* – righe: 0
– change data della tabella `SPLI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | SPLI_CODPROD | CHAR(2) | N |  |
| 5 | SPLI_SUBPROD | CHAR(5) | N |  |
| 6 | SPLI_DVALINI | DECIMAL(9,0) | N |  |
| 7 | SPLI_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | SPLI_GIORMIN | DECIMAL(5,0) | N |  |
| 9 | SPLI_GIORMAX | DECIMAL(5,0) | N |  |
| 10 | SPLI_PRCLIQ | DECIMAL(5,2) | N |  |

Indici:

- `SPLID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_SPOL_CD5

*Tabella* – righe: 0
– change data della tabella `SPOL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | SPOL_LVC1 | CHAR(2) | N |  |
| 6 | SPOL_LVC2 | CHAR(2) | N |  |
| 7 | SPOL_CDSTATI | CHAR(2) | N |  |
| 8 | SPOL_FUNZ | CHAR(6) | N |  |

Indici:

- `ASN_SPOL_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_SSIGE_CD5

*Tabella* – righe: 0
– change data della tabella `SSIGE`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | SSIGE_DVALORIZ | DECIMAL(9,0) | N |  |
| 6 | SSIGE_CODCONF | CHAR(11) | N |  |
| 7 | SSIGE_CTRVLIQ | DECIMAL(15,0) | N |  |
| 8 | SSIGE_CTRVRF | DECIMAL(15,0) | N |  |
| 9 | SSIGE_CTRVAZ | DECIMAL(15,0) | N |  |
| 10 | SSIGE_PATRN | DECIMAL(15,0) | N |  |
| 11 | SSIGE_RENDIMENTO | DECIMAL(9,4) | N |  |
| 12 | SSIGE_TIPO_VALORIZ | CHAR(1) | N |  |
| 13 | SSIGE_IMPIFU | DECIMAL(15,0) | N |  |
| 14 | SSIGE_IMPBOT | DECIMAL(15,0) | N |  |
| 15 | SSIGE_IMPBTP | DECIMAL(15,0) | N |  |
| 16 | SSIGE_IMPCCT | DECIMAL(15,0) | N |  |
| 17 | SSIGE_ECTRVLIQ | DECIMAL(15,2) | N |  |
| 18 | SSIGE_ECTRVAZ | DECIMAL(15,2) | N |  |
| 19 | SSIGE_EPATRN | DECIMAL(15,2) | N |  |
| 20 | SSIGE_EIMPIFU | DECIMAL(15,2) | N |  |
| 21 | SSIGE_RETE | CHAR(1) | N | INDICATORE RETE VENDITA |
| 22 | SSIGE_EIMPFDT | DECIMAL(15,2) | N | CONTROVALORE DEL SOTTOSTANTE FT |
| 23 | SSIGE_EIMPTIT | DECIMAL(15,2) | N | CONTROVALORE DEL SOTTOSTANTE TITOLI |
| 24 | SSIGE_EIMPFOI | DECIMAL(15,2) | N | CONTROVALORE DEL SOTTOSTANTE FOI |
| 25 | SSIGE_DRIFSALDO | DECIMAL(9,0) | N | DATA RIFERIMENTO SALDO PER 57 |
| 26 | SSIGE_SUBPROD | CHAR(5) | N | CODICE SOTTOPRODOTTO |
| 27 | SSIGE_PLUSVALENZE | DECIMAL(15,2) | N | PLUSVALENZE |
| 28 | SSIGE_PROVENTI | DECIMAL(15,2) | N | PROVENTI |
| 29 | SSIGE_ONERI | DECIMAL(15,2) | N | ONERI |
| 30 | SSIGE_CTRFONDI_NON | DECIMAL(15,0) |  |  |
| 31 | SSIGE_CTRFONDI_IMI | DECIMAL(15,0) |  |  |
| 32 | SSIGE_CODDIV | CHAR(3) |  |  |
| 33 | SSIGE_ECVN | DECIMAL(15,2) |  |  |
| 34 | SSIGE_CPP | CHAR(1) |  |  |
| 35 | SSIGE_CODPROD | CHAR(2) |  |  |
| 36 | SSIGE_MARGINI | DECIMAL(15,2) |  |  |
| 37 | SSIGE_IVA | DECIMAL(15,2) | N | IVA |

Indici:

- `ASN_SSIGE_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_STAPOL_CD

*Tabella* – righe: 0
– change data della tabella `STAPOL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | STAPOL_STATOPOL | CHAR(2) | N |  |
| 5 | STAPOL_STAPOLDET | CHAR(2) | N |  |
| 6 | STAPOL_DESCR | CHAR(50) | N |  |
| 7 | STAPOL_STATOCON | CHAR(1) | N |  |

Indici:

- `STAPOLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_STORFA_CD

*Tabella* – righe: 4.704
– change data della tabella `STORFA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | STORFA_CODAGE | CHAR(6) | N |  |
| 5 | STORFA_DATA | DECIMAL(9,0) | N |  |
| 6 | STORFA_COMP | CHAR(3) | N |  |
| 7 | STORFA_IMPORTO | DECIMAL(15,2) | N |  |

Indici:

- `STORFAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_STPROVCG_CD

*Tabella* – righe: 0
– change data della tabella `STPROVCG`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | STPROVCG_CODAGVEN | CHAR(6) | N |  |
| 5 | STPROVCG_CODANA | CHAR(12) | N |  |
| 6 | STPROVCG_CODCONF | CHAR(11) | N |  |
| 7 | STPROVCG_PROGMOV | SMALLINT | N |  |
| 8 | STPROVCG_TIPOPER | CHAR(2) | N |  |
| 9 | STPROVCG_TIPOPES | CHAR(2) | N |  |
| 10 | STPROVCG_CODPROD | CHAR(2) | N |  |
| 11 | STPROVCG_SUBPROD | CHAR(5) | N |  |
| 12 | STPROVCG_TITOLO | CHAR(5) | N |  |
| 13 | STPROVCG_ISIN | CHAR(12) | N |  |
| 14 | STPROVCG_DELABCOM | DECIMAL(9,0) | N |  |
| 15 | STPROVCG_VOCE | CHAR(3) | N |  |
| 16 | STPROVCG_TIPOCOMM | CHAR(2) | N |  |
| 17 | STPROVCG_PAYIN | DECIMAL(15,2) | N |  |
| 18 | STPROVCG_TIPO_DISTR | CHAR(2) | N |  |
| 19 | STPROVCG_CODAGE | CHAR(6) | N |  |
| 20 | STPROVCG_PAYOUT | DECIMAL(15,2) | N |  |
| 21 | STPROVCG_TIPO_PAYOUT | CHAR(3) | N |  |
| 22 | STPROVCG_RETE | CHAR(1) | N |  |
| 23 | STPROVCG_FASE | CHAR(3) | N |  |
| 24 | STPROVCG_PROVENIENZA | CHAR(5) | N |  |
| 25 | STPROVCG_TIPO_PREMIO | CHAR(1) | N |  |
| 26 | STPROVCG_TIPO_ANN | CHAR(1) | N |  |
| 27 | STPROVCG_KEYNUMBER | DECIMAL(15,0) | N |  |
| 28 | STPROVCG_DT_INVIO | DECIMAL(9,0) | N |  |
| 29 | STPROVCG_DCOMPBIL | DECIMAL(9,0) | N |  |
| 30 | STPROVCG_PAYIN_DISTR | DECIMAL(15,2) | N |  |
| 31 | STPROVCG_PAYIN_IVA | DECIMAL(15,2) | N |  |

Indici:

- `STPROVCGD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_STPR_CD5

*Tabella* – righe: 0
– change data della tabella `STPR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | STPR_PROC | CHAR(8) | N |  |
| 6 | STPR_DTRIFE | DECIMAL(9,0) | N |  |
| 7 | STPR_CODENT | CHAR(5) | N |  |

Indici:

- `ASN_STPR_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_STPUL_CD

*Tabella* – righe: 1
– change data della tabella `STPUL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | STPUL_SUBPROD | CHAR(5) | N |  |
| 5 | STPUL_ANNO | DECIMAL(5,0) | N |  |
| 6 | STPUL_DURATA | DECIMAL(3,0) | N |  |
| 7 | STPUL_DVALINI | DECIMAL(9,0) | N |  |
| 8 | STPUL_DVALFIN | DECIMAL(9,0) | N |  |
| 9 | STPUL_CODPROD | CHAR(2) | N |  |
| 10 | STPUL_DVINIASS | DECIMAL(9,0) | N |  |
| 11 | STPUL_DVFINASS | DECIMAL(9,0) | N |  |
| 12 | STPUL_DESCR | CHAR(24) | N |  |
| 13 | STPUL_COMGS | DECIMAL(4,0) | N |  |
| 14 | STPUL_DESCRIZIONE | CHAR(100) | N |  |

Indici:

- `STPULD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TFCLIENT_CD

*Tabella* – righe: 0
– change data della tabella `TFCLIENT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TFCLIENT_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTFCLIENT_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TFCLIENT_ID_CLIENTE | DECIMAL(15,0) | N |  |
| 7 | XTFCLIENT_ID_CLIENTE | DECIMAL(15,0) |  |  |
| 8 | TFCLIENT_DVALINI | DECIMAL(9,0) | N |  |
| 9 | TFCLIENT_DVALFIN | DECIMAL(9,0) | N |  |
| 10 | XTFCLIENT_DVALFIN | DECIMAL(9,0) |  |  |
| 11 | TFCLIENT_CDFIS | CHAR(16) | N |  |
| 12 | XTFCLIENT_CDFIS | CHAR(16) |  |  |
| 13 | TFCLIENT_CODANA | CHAR(12) | N |  |
| 14 | TFCLIENT_NOME | CHAR(25) | N |  |
| 15 | TFCLIENT_COGNOME | CHAR(25) | N |  |
| 16 | TFCLIENT_DTDECOR | DECIMAL(9,0) | N |  |
| 17 | TFCLIENT_STATO | CHAR(2) | N |  |
| 18 | TFCLIENT_ID_VALID | DECIMAL(15,0) | N |  |
| 19 | TFCLIENT_RETE | CHAR(1) | N |  |
| 20 | TFCLIENT_DCHIUSURA | DECIMAL(9,0) | N |  |
| 21 | TFCLIENT_NOTE | CHAR(150) | N |  |
| 22 | TFCLIENT_DURATA_EFF | DECIMAL(5,0) | N |  |
| 23 | TFCLIENT_NO_TF | CHAR(2) | N |  |

Indici:

- `TFCLIENTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TFTEAM_CD

*Tabella* – righe: 0
– change data della tabella `TFTEAM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TFTEAM_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTFTEAM_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TFTEAM_DVALINI | DECIMAL(9,0) | N |  |
| 7 | TFTEAM_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | XTFTEAM_DVALFIN | DECIMAL(9,0) |  |  |
| 9 | TFTEAM_PB1 | CHAR(6) | N |  |
| 10 | TFTEAM_PB2 | CHAR(6) | N |  |
| 11 | TFTEAM_DSOTTOS | DECIMAL(9,0) | N |  |
| 12 | TFTEAM_CODICE | CHAR(20) | N |  |
| 13 | TFTEAM_DURATA | DECIMAL(5,0) | N |  |
| 14 | TFTEAM_PRV_PB1 | DECIMAL(5,2) | N |  |
| 15 | TFTEAM_PRV_PB2 | DECIMAL(5,2) | N |  |
| 16 | TFTEAM_RNT_PB1 | DECIMAL(5,2) | N |  |
| 17 | TFTEAM_RNT_PB2 | DECIMAL(5,2) | N |  |
| 18 | TFTEAM_DT_DECOR | DECIMAL(9,0) | N |  |
| 19 | TFTEAM_MESI_PROROGA | DECIMAL(5,0) | N |  |
| 20 | TFTEAM_DTPROROGA | DECIMAL(9,0) | N |  |
| 21 | TFTEAM_DSCADENZA | DECIMAL(9,0) | N |  |
| 22 | TFTEAM_STATO | CHAR(2) | N |  |
| 23 | TFTEAM_CAUSALE | CHAR(2) | N |  |
| 24 | TFTEAM_RIASS | CHAR(1) | N |  |
| 25 | TFTEAM_USERCREAT | CHAR(7) | N |  |
| 26 | TFTEAM_GRADOCREAT | CHAR(4) | N |  |
| 27 | TFTEAM_DT_RICEZ | DECIMAL(9,0) | N |  |
| 28 | TFTEAM_RETE | CHAR(1) | N |  |
| 29 | TFTEAM_DCHIUSURA | DECIMAL(9,0) | N |  |
| 30 | TFTEAM_DURATA_EFF | DECIMAL(5,0) | N |  |

Indici:

- `TFTEAMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TIPOLEG_CD

*Tabella* – righe: 7
– change data della tabella `TIPOLEG` (FJBM: TABELLA TIPO LEGAMI)

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TIPOLEG_CFIS_INT | CHAR(16) | N |  |
| 5 | TIPOLEG_CFIS_ESE | CHAR(16) | N |  |
| 6 | TIPOLEG_TIPO_LEGAME | CHAR(2) | N |  |
| 7 | TIPOLEG_DESCR_LEGAME | CHAR(50) | N |  |
| 8 | TIPOLEG_TIPOLOGIA | CHAR(10) | N |  |
| 9 | TIPOLEG_TIPO_DELEGA | CHAR(10) | N |  |
| 10 | TIPOLEG_DATA_CHIUSURA | DECIMAL(8,0) | N |  |
| 11 | TIPOLEG_ORDINE | SMALLINT | N |  |

Indici:

- `TIPOLEGD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TMCLIENT_CD

*Tabella* – righe: 10.904
– change data della tabella `TMCLIENT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TMCLIENT_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTMCLIENT_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TMCLIENT_ID_CLIENTE | DECIMAL(15,0) | N |  |
| 7 | XTMCLIENT_ID_CLIENTE | DECIMAL(15,0) |  |  |
| 8 | TMCLIENT_DVALINI | DECIMAL(9,0) | N |  |
| 9 | TMCLIENT_DVALFIN | DECIMAL(9,0) | N |  |
| 10 | XTMCLIENT_DVALFIN | DECIMAL(9,0) |  |  |
| 11 | TMCLIENT_TIPOCLI | CHAR(2) | N |  |
| 12 | TMCLIENT_TIPO_ESTR | CHAR(2) | N |  |
| 13 | TMCLIENT_CDFIS | CHAR(16) | N |  |
| 14 | XTMCLIENT_CDFIS | CHAR(16) |  |  |
| 15 | TMCLIENT_CODANA | CHAR(12) | N |  |
| 16 | TMCLIENT_NOME | CHAR(25) | N |  |
| 17 | TMCLIENT_COGNOME | CHAR(25) | N |  |
| 18 | TMCLIENT_MANDATO | CHAR(25) | N |  |
| 19 | XTMCLIENT_MANDATO | CHAR(25) |  |  |
| 20 | TMCLIENT_CODCONF | CHAR(11) | N |  |
| 21 | XTMCLIENT_CODCONF | CHAR(11) |  |  |
| 22 | TMCLIENT_DTDECOR | DECIMAL(9,0) | N |  |
| 23 | TMCLIENT_STATO | CHAR(2) | N |  |
| 24 | TMCLIENT_ID_VALID | DECIMAL(15,0) | N |  |
| 25 | TMCLIENT_F_STATO | CHAR(2) | N |  |
| 26 | TMCLIENT_BYPASS | CHAR(2) | N |  |
| 27 | TMCLIENT_DCHIUSURA | DECIMAL(9,0) | N |  |
| 28 | TMCLIENT_DURATA_EFF | DECIMAL(5,0) | N |  |
| 29 | TMCLIENT_NO_TF | CHAR(2) | N |  |
| 30 | TMCLIENT_PB_RIASS | CHAR(6) | N |  |
| 31 | TMCLIENT_PB_PREL | CHAR(6) | N |  |
| 32 | TMCLIENT_DT_RIN | DECIMAL(9,0) | N |  |
| 33 | TMCLIENT_RETE | CHAR(1) | N |  |
| 34 | TMCLIENT_WARNING | CHAR(150) | N |  |
| 35 | TMCLIENT_NOTE | CHAR(150) | N |  |

Indici:

- `TMCLIENTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TMPB_CD

*Tabella* – righe: 387
– change data della tabella `TMPB`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TMPB_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTMPB_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TMPB_CODAGE | CHAR(6) | N |  |
| 7 | XTMPB_CODAGE | CHAR(6) |  |  |
| 8 | TMPB_DVALINI | DECIMAL(9,0) | N |  |
| 9 | TMPB_DVALFIN | DECIMAL(9,0) | N |  |
| 10 | XTMPB_DVALFIN | DECIMAL(9,0) |  |  |
| 11 | TMPB_RUOLO | CHAR(2) | N |  |
| 12 | TMPB_GERARCHIA | DECIMAL(3,0) | N |  |
| 13 | TMPB_IDP_PLUS | DECIMAL(7,2) | N |  |
| 14 | TMPB_DT_DECOR | DECIMAL(9,0) | N |  |
| 15 | TMPB_PRV_SOTT | DECIMAL(5,2) | N |  |
| 16 | TMPB_PRV_GEST | DECIMAL(5,2) | N |  |
| 17 | TMPB_RNT | DECIMAL(5,2) | N |  |
| 18 | TMPB_DCHIUSURA | DECIMAL(9,0) | N |  |
| 19 | TMPB_DT_RIN | DECIMAL(9,0) | N |  |
| 20 | TMPB_STATO | CHAR(2) | N |  |
| 21 | TMPB_CAUSALE | CHAR(2) | N |  |
| 22 | TMPB_RETE | CHAR(1) | N |  |
| 23 | TMPB_NOTE | CHAR(150) | N |  |

Indici:

- `TMPBD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TMPERC_CD

*Tabella* – righe: 20.941
– change data della tabella `TMPERC`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TMPERC_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTMPERC_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TMPERC_CDFIS | CHAR(16) | N |  |
| 7 | XTMPERC_CDFIS | CHAR(16) |  |  |
| 8 | TMPERC_CODANA | CHAR(12) | N |  |
| 9 | TMPERC_NOME | CHAR(25) | N |  |
| 10 | TMPERC_COGNOME | CHAR(25) | N |  |
| 11 | TMPERC_CODAGE | CHAR(6) | N |  |
| 12 | XTMPERC_CODAGE | CHAR(6) |  |  |
| 13 | TMPERC_MANDATO | CHAR(25) | N |  |
| 14 | XTMPERC_MANDATO | CHAR(25) |  |  |
| 15 | TMPERC_CODCONF | CHAR(11) | N |  |
| 16 | XTMPERC_CODCONF | CHAR(11) |  |  |
| 17 | TMPERC_DVALINI | DECIMAL(9,0) | N |  |
| 18 | TMPERC_DVALFIN | DECIMAL(9,0) | N |  |
| 19 | XTMPERC_DVALFIN | DECIMAL(9,0) |  |  |
| 20 | TMPERC_PRV_SOTT | DECIMAL(5,2) | N |  |
| 21 | TMPERC_PRV_GEST | DECIMAL(5,2) | N |  |
| 22 | TMPERC_RNT | DECIMAL(5,2) | N |  |
| 23 | TMPERC_STATO | CHAR(2) | N |  |
| 24 | TMPERC_CAUSALE | CHAR(2) | N |  |
| 25 | TMPERC_RETE | CHAR(1) | N |  |
| 26 | TMPERC_NOTE | CHAR(150) | N |  |

Indici:

- `TMPERCD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TMTEAM_CD

*Tabella* – righe: 749
– change data della tabella `TMTEAM`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TMTEAM_ID_ACCORDO | DECIMAL(15,0) | N |  |
| 5 | XTMTEAM_ID_ACCORDO | DECIMAL(15,0) |  |  |
| 6 | TMTEAM_DVALINI | DECIMAL(9,0) | N |  |
| 7 | TMTEAM_DVALFIN | DECIMAL(9,0) | N |  |
| 8 | XTMTEAM_DVALFIN | DECIMAL(9,0) |  |  |
| 9 | TMTEAM_DSOTTOS | DECIMAL(9,0) | N |  |
| 10 | TMTEAM_CODICE | CHAR(20) | N |  |
| 11 | TMTEAM_DURATA | DECIMAL(5,0) | N |  |
| 12 | TMTEAM_DT_DECOR | DECIMAL(9,0) | N |  |
| 13 | TMTEAM_MESI_PROROGA | DECIMAL(5,0) | N |  |
| 14 | TMTEAM_DTPROROGA | DECIMAL(9,0) | N |  |
| 15 | TMTEAM_DSCADENZA | DECIMAL(9,0) | N |  |
| 16 | TMTEAM_STATO | CHAR(2) | N |  |
| 17 | TMTEAM_CAUSALE | CHAR(2) | N |  |
| 18 | TMTEAM_USERCREAT | CHAR(7) | N |  |
| 19 | TMTEAM_GRADOCREAT | CHAR(4) | N |  |
| 20 | TMTEAM_DT_RICEZ | DECIMAL(9,0) | N |  |
| 21 | TMTEAM_RETE | CHAR(1) | N |  |
| 22 | TMTEAM_DCHIUSURA | DECIMAL(9,0) | N |  |
| 23 | TMTEAM_DURATA_EFF | DECIMAL(5,0) | N |  |

Indici:

- `TMTEAMD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TPREMI_CD

*Tabella* – righe: 8
– change data della tabella `TPREMI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TPREMI_CODCONF | CHAR(11) | N |  |
| 5 | TPREMI_CODPROD | CHAR(2) | N |  |
| 6 | TPREMI_SUBPROD | CHAR(5) | N |  |
| 7 | TPREMI_TIPOPREM | CHAR(5) | N |  |
| 8 | TPREMI_DTVALINI | DECIMAL(9,0) | N |  |
| 9 | TPREMI_DTVALFIN | DECIMAL(9,0) | N |  |
| 10 | TPREMI_NUMPREV | SMALLINT | N |  |
| 11 | TPREMI_IMPANNUO | DECIMAL(12,2) | N |  |
| 12 | TPREMI_IMPFRAZ | DECIMAL(12,2) | N |  |
| 13 | TPREMI_RETE | CHAR(1) | N |  |

Indici:

- `TPREMID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TRARASPI_CD

*Tabella* – righe: 0
– change data della tabella `TRARASPI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TRARASPI_TIPTRA | CHAR(2) | N |  |
| 5 | TRARASPI_AGECED | CHAR(6) | N |  |
| 6 | TRARASPI_AGESUB | CHAR(6) | N |  |
| 7 | TRARASPI_DTRIASS | DECIMAL(9,0) | N |  |
| 8 | TRARASPI_DTINIZIO | DECIMAL(9,0) | N |  |
| 9 | TRARASPI_DTFINE | DECIMAL(9,0) | N |  |
| 10 | TRARASPI_CODCONF | CHAR(11) | N |  |
| 11 | TRARASPI_DTSTRALCI | DECIMAL(9,0) | N |  |

Indici:

- `TRARASPID01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TRARA_CD

*Tabella* – righe: 0
– change data della tabella `TRARA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TRARA_TIPTRA | CHAR(2) | N |  |
| 5 | TRARA_AGECED | CHAR(6) | N |  |
| 6 | TRARA_AGESUB | CHAR(6) | N |  |
| 7 | TRARA_DTRIASS | DECIMAL(9,0) | N |  |
| 8 | TRARA_DTINIZIO | DECIMAL(9,0) | N |  |
| 9 | TRARA_DTFINE | DECIMAL(9,0) | N |  |
| 10 | TRARA_CODCONF | CHAR(11) | N |  |
| 11 | TRARA_DTSTRALCIO | DECIMAL(9,0) | N |  |

Indici:

- `TRARAD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TRASF_CD

*Tabella* – righe: 0
– change data della tabella `TRASF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | TRASF_CODCONF_CEDENTE | CHAR(11) | N |  |
| 5 | TRASF_CODCONF_RICEVENTE | CHAR(11) | N |  |
| 6 | TRASF_DT_VALOR_DISINV | DECIMAL(9,0) | N |  |
| 7 | TRASF_DT_VALOR_INV | DECIMAL(9,0) | N |  |
| 8 | TRASF_ESEGUITO | CHAR(1) | N |  |
| 9 | TRASF_NLV_DISINV | DECIMAL(15,0) | N |  |
| 10 | TRASF_NLV_INV | DECIMAL(15,0) | N |  |
| 11 | TRASF_PROGMOV_DISINV | DECIMAL(15,0) | N |  |
| 12 | TRASF_PROGMOV_INV | DECIMAL(15,0) | N |  |
| 13 | TRASF_SCHEDA | DECIMAL(15,0) | N |  |
| 14 | TRASF_IMP_STIM | DECIMAL(15,2) | N |  |

Indici:

- `TRASFD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_TRF_CD5

*Tabella* – righe: 0
– change data della tabella `TRF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | TRF_CODTRF | CHAR(3) | N |  |
| 6 | TRF_CDDURTRF | CHAR(1) | N |  |
| 7 | TRF_CDPREST | CHAR(1) | N |  |
| 8 | TRF_CDPREMIO | CHAR(1) | N |  |
| 9 | TRF_DESTRF | VARCHAR(50) | N |  |
| 10 | TRF_CDFND | CHAR(5) |  |  |
| 11 | TRF_CODVAL | CHAR(3) | N |  |
| 12 | TRF_ITIPRIS | CHAR(1) | N |  |
| 13 | TRF_TASTEC | DECIMAL(5,2) |  |  |

Indici:

- `ASN_TRF_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VARPOL_CD

*Tabella* – righe: 0
– change data della tabella `VARPOL`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | VARPOL_CODCONF | CHAR(11) | N |  |
| 5 | VARPOL_CODPROD | CHAR(2) | N |  |
| 6 | VARPOL_VARIABILE | CHAR(5) | N |  |
| 7 | VARPOL_VALORE | CHAR(20) | N |  |

Indici:

- `VARPOLD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VAR_CD5

*Tabella* – righe: 0
– change data della tabella `VAR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | VAR_CODCONF | CHAR(11) | N |  |
| 6 | VAR_CODPROD | CHAR(2) | N |  |
| 7 | VAR_TIPOPER | CHAR(2) | N |  |
| 8 | VAR_NOTE | VARCHAR(70) | N |  |
| 9 | VAR_CONTO | DECIMAL(9,0) | N |  |
| 10 | VAR_IMP | DECIMAL(13,0) | N |  |
| 11 | VAR_PROGPAG | SMALLINT | N |  |
| 12 | VAR_SUBPROD | CHAR(5) | N |  |
| 13 | VAR_DACQUIS | DECIMAL(9,0) | N |  |
| 14 | VAR_IMPOPAG | DECIMAL(15,2) | N |  |
| 15 | VAR_IMPEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_VAR_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VDISTR_CD5

*Tabella* – righe: 0
– change data della tabella `VDISTR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | VDISTR_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | VDISTR_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | VDISTR_CODCONF | CHAR(11) | N |  |
| 8 | VDISTR_CODPROD | CHAR(2) | N |  |
| 9 | VDISTR_SUBPROD | CHAR(5) | N |  |
| 10 | VDISTR_PERCCMP | DECIMAL(9,5) | N |  |
| 11 | VDISTR_PERCTIPO | CHAR(1) | N |  |
| 12 | VDISTR_COD_LIV3 | CHAR(5) |  |  |
| 13 | VDISTR_COD_LIV2 | CHAR(5) |  |  |
| 14 | VDISTR_PRC_LIV2 | DECIMAL(7,3) |  |  |
| 15 | VDISTR_IND_TENDENZA | CHAR(1) |  |  |

Indici:

- `ASN_VDISTR_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VFFOI_CD5

*Tabella* – righe: 0
– change data della tabella `VFFOI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | VFFOI_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | VFFOI_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | VFFOI_CODCONF | CHAR(11) | N |  |
| 8 | VFFOI_CODPROD | CHAR(2) | N |  |
| 9 | VFFOI_CONTRTIPO | CHAR(1) | N |  |
| 10 | VFFOI_IMPDIFF | DECIMAL(13,0) | N |  |
| 11 | VFFOI_IMPDIFFEURO | DECIMAL(15,2) | N |  |

Indici:

- `ASN_VFFOI_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VTFOIF_CD5

*Tabella* – righe: 0
– change data della tabella `VTFOIF`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | VTFOIF_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | VTFOIF_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | VTFOIF_CODCONF | CHAR(11) | N |  |
| 8 | VTFOIF_CODPROD | CHAR(2) | N |  |
| 9 | VTFOIF_TARSPS | CHAR(4) | N |  |
| 10 | VTFOIF_CODAGE | CHAR(6) | N |  |
| 11 | VTFOIF_CODAGES | CHAR(6) | N |  |
| 12 | VTFOIF_PRCAGE | SMALLINT | N |  |
| 13 | VTFOIF_TIPOVAR | CHAR(1) | N |  |

Indici:

- `ASN_VTFOIF_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_VTFOI_CD5

*Tabella* – righe: 0
– change data della tabella `VTFOI`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | VTFOI_DATAINIZ | DECIMAL(9,0) | N |  |
| 6 | VTFOI_DATAFINE | DECIMAL(9,0) | N |  |
| 7 | VTFOI_CODCONF | CHAR(11) | N |  |
| 8 | VTFOI_CODPROD | CHAR(2) | N |  |
| 9 | VTFOI_TARSPS | CHAR(4) | N |  |

Indici:

- `ASN_VTFOI_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_W6SCCO_CD

*Tabella* – righe: 0
– change data della tabella `W6SCCO`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CODFIS | CHAR(16) | N |  |
| 5 | CODMAN | CHAR(6) | N |  |
| 6 | RETE | CHAR(1) | N |  |
| 7 | CODAGE | CHAR(6) | N |  |
| 8 | COGNOME | CHAR(25) | N |  |
| 9 | NOME | CHAR(25) | N |  |
| 10 | CODANA | CHAR(12) | N |  |
| 11 | CODCO | CHAR(11) | N |  |
| 12 | SUBPRCO | CHAR(5) | N |  |
| 13 | DTLETBENV | DECIMAL(9,0) | N |  |
| 14 | CODCOPRE | CHAR(11) | N |  |
| 15 | DTLETPRE | DECIMAL(9,0) | N |  |
| 16 | CODCONF | CHAR(11) | N |  |
| 17 | SUBPROD | CHAR(11) | N |  |
| 18 | CONTO | CHAR(12) | N |  |
| 19 | CODABI | CHAR(8) | N |  |
| 20 | TIPOPER | CHAR(5) | N |  |
| 21 | TIPOPES | CHAR(2) | N |  |
| 22 | MANLEVA | CHAR(1) | N |  |
| 23 | DTMANLEVA | DECIMAL(9,0) | N |  |
| 24 | AGEVCO | CHAR(1) | N |  |
| 25 | DTRUN | DECIMAL(9,0) | N |  |
| 26 | DTPERDA | DECIMAL(9,0) | N |  |
| 27 | DTPERA | DECIMAL(9,0) | N |  |
| 28 | DTULTMOV | DECIMAL(9,0) | N |  |
| 29 | DTSOSP | DECIMAL(9,0) | N |  |
| 30 | DTRIATT | DECIMAL(9,0) | N |  |
| 31 | ALERT | DECIMAL(2,0) | N |  |
| 32 | SOSPAG | CHAR(1) | N |  |
| 33 | BLOCCO | CHAR(1) | N |  |

Indici:

- `W6SCCOD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_W6SCST_CD

*Tabella* – righe: 0
– change data della tabella `W6SCST`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CODFIS | CHAR(16) | N |  |
| 5 | CODMAN | CHAR(6) | N |  |
| 6 | RETE | CHAR(1) | N |  |
| 7 | CODAGE | CHAR(6) | N |  |
| 8 | CODCO | CHAR(11) | N |  |
| 9 | SUBPRCO | CHAR(5) | N |  |
| 10 | DTLETBENV | DECIMAL(9,0) | N |  |
| 11 | DTRUN | DECIMAL(9,0) | N |  |
| 12 | DTPERDA | DECIMAL(9,0) | N |  |
| 13 | DTPERA | DECIMAL(9,0) | N |  |
| 14 | DTULTMOV | DECIMAL(9,0) | N |  |
| 15 | DTMANLEV | DECIMAL(9,0) | N |  |
| 16 | DTSOSP | DECIMAL(9,0) | N |  |
| 17 | DTRIATT | DECIMAL(9,0) | N |  |
| 18 | ALERT | DECIMAL(2,0) | N |  |
| 19 | SOSPAG | CHAR(1) | N |  |
| 20 | FLAGMAN | CHAR(1) | N |  |

Indici:

- `W6SCSTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WCARAD_CD

*Tabella* – righe: 0
– change data della tabella `WCARAD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | STATO | CHAR(1) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(40) | N |  |
| 8 | DESRID | CHAR(15) | N |  |

Indici:

- `WCARADD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WCTRAD_CD

*Tabella* – righe: 0
– change data della tabella `WCTRAD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CAUSALE | DECIMAL(5,0) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(80) | N |  |

Indici:

- `WCTRADD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WDCBEN_CD

*Tabella* – righe: 0
– change data della tabella `WDCBEN`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | CHAR(10) | N |  |
| 2 | IBMSNAP_INTENTSEQ | CHAR(10) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODBENOLD | CHAR(10) | N |  |
| 6 | DTFINE | DECIMAL(9,0) | N |  |
| 7 | DTINIZ | DECIMAL(9,0) | N |  |
| 8 | CODDEC | CHAR(20) | N |  |

Indici:

- `WDCBEND01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WESTCD_CD

*Tabella* – righe: 0
– change data della tabella `WESTCD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODFREQ | CHAR(1) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(20) | N |  |

Indici:

- `WESTCDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WIBSTRT_CD

*Tabella* – righe: 0
– change data della tabella `WIBSTRT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 4 | CODAGE | CHAR(6) | N |  |
| 5 | STATUS | CHAR(1) | N |  |
| 6 | DTTERM | DECIMAL(9,0) | N |  |
| 7 | GRADO | CHAR(3) | N |  |
| 8 | NOMIN | CHAR(65) | N |  |
| 9 | CODAGESPV | CHAR(6) | N |  |
| 10 | NOMINSPV | CHAR(65) | N |  |
| 11 | CODAGERM | CHAR(6) | N |  |
| 12 | NOMINRM | CHAR(65) | N |  |
| 13 | CODAGEDM | CHAR(6) | N |  |
| 14 | NOMINDM | CHAR(65) | N |  |
| 15 | CODAGEAM | CHAR(6) | N |  |
| 16 | NOMINAM | CHAR(65) | N |  |
| 17 | RETE | CHAR(1) | N |  |

Indici:

- `IXCDWIBSTRT` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WPRDD_CD

*Tabella* – righe: 0
– change data della tabella `WPRDD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODPROD | CHAR(2) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(30) | N |  |
| 8 | RETE | CHAR(1) | N |  |
| 9 | DESRID | CHAR(8) | N |  |

Indici:

- `WPRDDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WPRDSD_CD

*Tabella* – righe: 0
– change data della tabella `WPRDSD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODPROD | CHAR(2) | N |  |
| 6 | SUBPROD | CHAR(5) | N |  |
| 7 | LINGUA | CHAR(2) | N |  |
| 8 | DES | CHAR(30) | N |  |
| 9 | DESTPPROD | CHAR(10) | N |  |
| 10 | DESTRF | CHAR(50) | N |  |
| 11 | DESRID | CHAR(15) | N |  |
| 12 | DESPERF | CHAR(52) | N |  |
| 13 | RETE | CHAR(1) | N |  |

Indici:

- `WPRDSDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WPRPOD_CD

*Tabella* – righe: 0
– change data della tabella `WPRPOD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODPERIOD | CHAR(2) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(30) | N |  |

Indici:

- `WPRPODD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WREPRD_CD

*Tabella* – righe: 0
– change data della tabella `WREPRD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODREPR | CHAR(1) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(25) | N |  |

Indici:

- `ASN_WREPRD_IX` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WSPOLD_CD

*Tabella* – righe: 0
– change data della tabella `WSPOLD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | INDSTA1 | CHAR(2) | N |  |
| 6 | INDSTA2 | CHAR(2) | N |  |
| 7 | LINGUA | CHAR(2) | N |  |
| 8 | DES | CHAR(50) | N |  |

Indici:

- `WSPOLDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WSTCND_CD

*Tabella* – righe: 0
– change data della tabella `WSTCND`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | BLOCCO | CHAR(2) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(25) | N |  |
| 8 | DESBREVE | CHAR(15) | N |  |

Indici:

- `WSTCNDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WSTRT_CD

*Tabella* – righe: 0
– change data della tabella `WSTRT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODAGE | CHAR(6) | N |  |
| 6 | STATUS | CHAR(1) | N |  |
| 7 | DTTERM | DECIMAL(9,0) | N |  |
| 8 | GRADO | CHAR(3) | N |  |
| 9 | NOMIN | CHAR(65) | N |  |
| 10 | CODAGESPV | CHAR(6) | N |  |
| 11 | NOMINSPV | CHAR(65) | N |  |
| 12 | CODAGERM | CHAR(6) | N |  |
| 13 | NOMINRM | CHAR(65) | N |  |
| 14 | CODAGEDM | CHAR(6) | N |  |
| 15 | NOMINDM | CHAR(65) | N |  |
| 16 | CODAGEAM | CHAR(6) | N |  |
| 17 | NOMINAM | CHAR(65) | N |  |
| 18 | RETE | CHAR(1) | N |  |

Indici:

- `WSTRTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WTPGED_CD

*Tabella* – righe: 0
– change data della tabella `WTPGED`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | TPGEST | CHAR(1) | N |  |
| 6 | CODPROD | CHAR(2) | N |  |
| 7 | LINGUA | CHAR(2) | N |  |
| 8 | DES | CHAR(50) | N |  |

Indici:

- `WTPGEDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WTRFD_CD

*Tabella* – righe: 0
– change data della tabella `WTRFD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODTRF | CHAR(3) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(50) | N |  |
| 8 | DESPREST | CHAR(10) | N |  |
| 9 | DESPREMIO | CHAR(10) | N |  |

Indici:

- `WTRFDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WTVOCD_CD

*Tabella* – righe: 0
– change data della tabella `WTVOCD`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODTPVOCE | CHAR(3) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | CODFAMRIC | CHAR(2) | N |  |
| 8 | DES | CHAR(50) | N |  |

Indici:

- `WTVOCDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WVOCID_CD

*Tabella* – righe: 0
– change data della tabella `WVOCID`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODVOCE | CHAR(3) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(50) | N |  |

Indici:

- `WVOCIDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_WZOPED_CD

*Tabella* – righe: 0
– change data della tabella `WZOPED`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | TIPOPER | CHAR(2) | N |  |
| 6 | LINGUA | CHAR(2) | N |  |
| 7 | DES | CHAR(20) | N |  |

Indici:

- `WZOPEDD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_YSTRT_CD

*Tabella* – righe: 0
– change data della tabella `YSTRT`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP | N |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | CODAGE | CHAR(6) | N |  |
| 6 | STATUS | CHAR(1) | N |  |
| 7 | DTTERM | DECIMAL(9,0) | N |  |
| 8 | GRADO | CHAR(3) | N |  |
| 9 | NOMIN | CHAR(65) | N |  |
| 10 | CODAGESPV | CHAR(6) | N |  |
| 11 | NOMINSPV | CHAR(65) | N |  |
| 12 | CODAGERM | CHAR(6) | N |  |
| 13 | NOMINRM | CHAR(65) | N |  |
| 14 | CODAGEDM | CHAR(6) | N |  |
| 15 | NOMINDM | CHAR(65) | N |  |
| 16 | CODAGEAM | CHAR(6) | N |  |
| 17 | NOMINAM | CHAR(65) | N |  |
| 18 | RETE | CHAR(1) | N |  |

Indici:

- `YSTRTD01` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ZOPR_CD5

*Tabella* – righe: 0
– change data della tabella `ZOPR`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | XZOPR_TIPOPER | CHAR(2) |  |  |
| 6 | XZOPR_TIPOPES | CHAR(2) |  |  |
| 7 | ZOPR_TIPOPER | CHAR(2) | N |  |
| 8 | ZOPR_TIPOPES | CHAR(2) | N |  |
| 9 | ZOPR_TDESRID | CHAR(15) | N |  |
| 10 | ZOPR_TDESOPR | CHAR(30) | N |  |
| 11 | ZOPR_CODGROP | CHAR(2) |  |  |
| 12 | ZOPR_CODSOC | CHAR(2) |  |  |
| 13 | ZOPR_FONLIN | CHAR(1) |  |  |
| 14 | ZOPR_FIMIINQ | CHAR(1) |  |  |
| 15 | ZOPR_FINVEST | CHAR(1) |  |  |
| 16 | ZOPR_FMODPAG | CHAR(1) |  |  |
| 17 | ZOPR_FMODVAL | CHAR(1) |  |  |
| 18 | ZOPR_NPRGELA | DECIMAL(3,0) |  |  |
| 19 | ZOPR_FSPSAMMI | CHAR(1) |  |  |
| 20 | ZOPR_TIPOL | CHAR(1) |  |  |
| 21 | ZOPR_BLOCCO | CHAR(1) |  |  |
| 22 | ZOPR_PRTCFX | CHAR(4) |  |  |
| 23 | ZOPR_PRTY | DECIMAL(3,0) |  |  |
| 24 | ZOPR_OPECAUS | CHAR(2) |  |  |
| 25 | ZOPR_FLAGTOP | CHAR(1) |  |  |
| 26 | ZOPR_CTEVFIN | DECIMAL(3,0) |  |  |
| 27 | ZOPR_SWSTORNO | CHAR(1) |  |  |
| 28 | ZOPR_FLAGBI | CHAR(2) |  |  |
| 29 | ZOPR_AUI | CHAR(1) |  |  |
| 30 | ZOPR_CAUSDEP | CHAR(4) |  |  |
| 31 | ZOPR_SPEGROP | CHAR(2) |  |  |
| 32 | ZOPR_INDQUA | CHAR(2) |  |  |

Indici:

- `ASN_ZOPR_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## ASN_ZTRA_CD5

*Tabella* – righe: 0
– change data della tabella `ZTRA`

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | IBMSNAP_COMMITSEQ | VARCHAR(16) | N |  |
| 2 | IBMSNAP_INTENTSEQ | VARCHAR(16) | N |  |
| 3 | IBMSNAP_LOGMARKER | TIMESTMP |  |  |
| 4 | IBMSNAP_OPERATION | CHAR(1) | N |  |
| 5 | ZTRA_CODCONFC | CHAR(11) | N |  |
| 6 | ZTRA_PROGMOVC | SMALLINT | N |  |
| 7 | ZTRA_CODCONFR | CHAR(11) | N |  |
| 8 | ZTRA_PROGMOVR | SMALLINT | N |  |
| 9 | ZTRA_CAUSALE | DECIMAL(5,0) | N |  |
| 10 | ZTRA_CODPRODC | CHAR(2) | N |  |
| 11 | ZTRA_CODPRODR | CHAR(2) | N |  |
| 12 | ZTRA_DACQUIS | DECIMAL(8,0) | N |  |
| 13 | ZTRA_DTLET_CLI | DECIMAL(9,0) | N |  |

Indici:

- `ASN_ZTRA_IX5` (UNIQUE): IBMSNAP_COMMITSEQ, IBMSNAP_INTENTSEQ

## BJSYSPACKAGEV2

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | SYSTEM | CHAR(4) | N |  |
| 2 | COLLID | VARCHAR(128) | N |  |
| 3 | NAME | VARCHAR(128) | N |  |
| 4 | VERSION | VARCHAR(122) | N |  |
| 5 | CREATOR | VARCHAR(128) | N |  |
| 6 | QUALIFIER | VARCHAR(128) | N |  |
| 7 | OWNER | VARCHAR(128) | N |  |

## BJSYSPACKAGEV3

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | SYSTEM | CHAR(4) | N |  |
| 2 | COLLID | CHAR(18) | N |  |
| 3 | NAME | VARCHAR(24) | N |  |
| 4 | VERSION | VARCHAR(64) | N |  |
| 5 | CREATOR | VARCHAR(128) | N |  |
| 6 | QUALIFIER | VARCHAR(128) | N |  |
| 7 | OWNER | VARCHAR(128) | N |  |

## BJSYSPLANV1

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | SYSTEM | CHAR(4) | N |  |
| 2 | PLNAME | VARCHAR(24) | N |  |
| 3 | COLLID | CHAR(18) | N |  |
| 4 | PLCREATOR | VARCHAR(128) | N |  |
| 5 | QUALIFIER | VARCHAR(128) | N |  |

## BJSYSPLANV2

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | SYSTEM | CHAR(4) | N |  |
| 2 | PLNAME | VARCHAR(24) | N |  |
| 3 | COLLID | VARCHAR(128) | N |  |
| 4 | PLCREATOR | VARCHAR(128) | N |  |
| 5 | QUALIFIER | VARCHAR(128) | N |  |

## BJSYSTABLESV1

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## BJSYSTABLESV2

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## BJSYSTABLESV3

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## BJSYSTABLESV4

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## BJSYSTABLESV5

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## BJSYSTABLESV6

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DBNAME | VARCHAR(24) | N |  |
| 2 | TSNAME | VARCHAR(24) | N |  |
| 3 | CREATOR | VARCHAR(128) | N |  |
| 4 | NAME | CHAR(18) | N |  |
| 5 | TYPE | VARCHAR(1) | N |  |
| 6 | TBCREATOR | VARCHAR(128) | N |  |
| 7 | TBNAME | CHAR(18) | N |  |
| 8 | SYSTEM | VARCHAR(4) | N |  |
| 9 | PQTY | INTEGER |  |  |
| 10 | SQTY | INTEGER |  |  |

## DSN_COLDIST_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | APPLNAME | VARCHAR(128) | N |  |
| 3 | PROGNAME | VARCHAR(128) | N |  |
| 4 | COLLID | VARCHAR(128) | N |  |
| 5 | GROUP_MEMBER | VARCHAR(128) | N |  |
| 6 | SECTNOI | INTEGER | N |  |
| 7 | VERSION | VARCHAR(122) | N |  |
| 8 | EXPLAIN_TIME | TIMESTMP | N |  |
| 9 | SCHEMA | VARCHAR(128) | N |  |
| 10 | TBNAME | VARCHAR(128) | N |  |
| 11 | NAME | VARCHAR(128) | N |  |
| 12 | COLVALUE | VARCHAR(2000) | N |  |
| 13 | TYPE | CHAR(1) | N |  |
| 14 | CARDF | FLOAT | N |  |
| 15 | COLGROUPCOLNO | VARCHAR(254) | N |  |
| 16 | NUMCOLUMNS | SMALLINT | N |  |
| 17 | FREQUENCYF | FLOAT | N |  |
| 18 | QUANTILENO | SMALLINT | N |  |
| 19 | LOWVALUE | VARCHAR(2000) | N |  |
| 20 | HIGHVALUE | VARCHAR(2000) | N |  |
| 21 | EXPANSION_REASON | CHAR(2) | N |  |
| 22 | PER_STMT_ID | BIGINT | N |  |
| 23 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX49` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_COLDIST_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_DETCOST_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | PLANNO | SMALLINT | N |  |
| 6 | OPENIO | FLOAT | N |  |
| 7 | OPENCPU | FLOAT | N |  |
| 8 | OPENCOST | FLOAT | N |  |
| 9 | DMIO | FLOAT | N |  |
| 10 | DMCPU | FLOAT | N |  |
| 11 | DMTOT | FLOAT | N |  |
| 12 | SUBQIO | FLOAT | N |  |
| 13 | SUBQCPU | FLOAT | N |  |
| 14 | SUBQCOST | FLOAT | N |  |
| 15 | BASEIO | FLOAT | N |  |
| 16 | BASECPU | FLOAT | N |  |
| 17 | BASETOT | FLOAT | N |  |
| 18 | ONECOMPROWS | FLOAT | N |  |
| 19 | IMLEAF | FLOAT | N |  |
| 20 | IMIO | FLOAT | N |  |
| 21 | IMPREFH | CHAR(2) | N |  |
| 22 | IMMPRED | INTEGER | N |  |
| 23 | IMFF | FLOAT | N |  |
| 24 | IMSRPRED | INTEGER | N |  |
| 25 | IMFFADJ | FLOAT | N |  |
| 26 | IMSCANCST | FLOAT | N |  |
| 27 | IMROWCST | FLOAT | N |  |
| 28 | IMPAGECST | FLOAT | N |  |
| 29 | IMRIDSORT | FLOAT | N |  |
| 30 | IMMERGCST | FLOAT | N |  |
| 31 | IMCPU | FLOAT | N |  |
| 32 | IMTOT | FLOAT | N |  |
| 33 | IMSEQNO | SMALLINT | N |  |
| 34 | DMPREFH | CHAR(2) | N |  |
| 35 | DMCLUDIO | FLOAT | N |  |
| 36 | DMNCLUDIO | FLOAT | N |  |
| 37 | DMPREDS | INTEGER | N |  |
| 38 | DMSROWS | FLOAT | N |  |
| 39 | DMSCANCST | FLOAT | N |  |
| 40 | DMCOLS | SMALLINT | N |  |
| 41 | DMROWS | FLOAT | N |  |
| 42 | RDSROWCST | FLOAT | N |  |
| 43 | DMPAGECST | FLOAT | N |  |
| 44 | DMDATAIO | FLOAT | N |  |
| 45 | DMDATACPU | FLOAT | N |  |
| 46 | DMDATATOT | FLOAT | N |  |
| 47 | RDSROW | FLOAT | N |  |
| 48 | SNCOLS | SMALLINT | N |  |
| 49 | SNROWS | FLOAT | N |  |
| 50 | SNRECSZ | INTEGER | N |  |
| 51 | SNPAGES | FLOAT | N |  |
| 52 | SNRUNS | FLOAT | N |  |
| 53 | SNMERGES | FLOAT | N |  |
| 54 | SNIOCOST | FLOAT | N |  |
| 55 | SNCPUCOST | FLOAT | N |  |
| 56 | SNCOST | FLOAT | N |  |
| 57 | SNSCANIO | FLOAT | N |  |
| 58 | SNSCANCPU | FLOAT | N |  |
| 59 | SNSCANCOST | FLOAT | N |  |
| 60 | SCCOLS | SMALLINT | N |  |
| 61 | SCROWS | FLOAT | N |  |
| 62 | SCRECSZ | INTEGER | N |  |
| 63 | SCPAGES | FLOAT | N |  |
| 64 | SCRUNS | FLOAT | N |  |
| 65 | SCMERGES | FLOAT | N |  |
| 66 | SCIOCOST | FLOAT | N |  |
| 67 | SCCPUCOST | FLOAT | N |  |
| 68 | SCCOST | FLOAT | N |  |
| 69 | SCSCANIO | FLOAT | N |  |
| 70 | SCSCANCPU | FLOAT | N |  |
| 71 | SCSCANCOST | FLOAT | N |  |
| 72 | COMPCARD | FLOAT | N |  |
| 73 | COMPIOCOST | FLOAT | N |  |
| 74 | COMPCPUCOST | FLOAT | N |  |
| 75 | COMPCOST | FLOAT | N |  |
| 76 | JOINCOLS | SMALLINT | N |  |
| 77 | EXPLAIN_TIME | TIMESTMP | N |  |
| 78 | COSTBLK | INTEGER | N |  |
| 79 | COSTSTOR | INTEGER | N |  |
| 80 | MPBLK | INTEGER | N |  |
| 81 | MPSTOR | INTEGER | N |  |
| 82 | COMPOSITES | INTEGER | N |  |
| 83 | CLIPPED | INTEGER | N |  |
| 84 | PARTITION | INTEGER | N |  |
| 85 | TABREF | VARCHAR(64) | N |  |
| 86 | MAX_COMPOSITES | INTEGER | N |  |
| 87 | MAX_STOR | INTEGER | N |  |
| 88 | MAX_CPU | INTEGER | N |  |
| 89 | MAX_ELAP | INTEGER | N |  |
| 90 | TBL_JOINED_THRESH | INTEGER | N |  |
| 91 | STOR_USED | INTEGER | N |  |
| 92 | CPU_USED | INTEGER | N |  |
| 93 | ELAPSED | INTEGER | N |  |
| 94 | MIN_CARD_KEEP | FLOAT | N |  |
| 95 | MAX_CARD_KEEP | FLOAT | N |  |
| 96 | MIN_COST_KEEP | FLOAT | N |  |
| 97 | MAX_COST_KEEP | FLOAT | N |  |
| 98 | MIN_VALUE_KEEP | FLOAT | N |  |
| 99 | MIN_VALUE_CARD_KEEP | FLOAT | N |  |
| 100 | MIN_VALUE_COST_KEEP | FLOAT | N |  |
| 101 | MAX_VALUE_KEEP | FLOAT | N |  |
| 102 | MAX_VALUE_CARD_KEEP | FLOAT | N |  |
| 103 | MAX_VALUE_COST_KEEP | FLOAT | N |  |
| 104 | MIN_CARD_CLIP | FLOAT | N |  |
| 105 | MAX_CARD_CLIP | FLOAT | N |  |
| 106 | MIN_COST_CLIP | FLOAT | N |  |
| 107 | MAX_COST_CLIP | FLOAT | N |  |
| 108 | MIN_VALUE_CLIP | FLOAT | N |  |
| 109 | MIN_VALUE_CARD_CLIP | FLOAT | N |  |
| 110 | MIN_VALUE_COST_CLIP | FLOAT | N |  |
| 111 | MAX_VALUE_CLIP | FLOAT | N |  |
| 112 | MAX_VALUE_CARD_CLIP | FLOAT | N |  |
| 113 | MAX_VALUE_COST_CLIP | FLOAT | N |  |
| 114 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 115 | PSEQIOCOST | FLOAT | N |  |
| 116 | PSEQCPUCOST | FLOAT | N |  |
| 117 | PSEQCOST | FLOAT | N |  |
| 118 | PADJIOCOST | FLOAT | N |  |
| 119 | PADJCPUCOST | FLOAT | N |  |
| 120 | PADJCOST | FLOAT | N |  |
| 121 | UNCERTAINTY | FLOAT | N |  |
| 122 | UNCERTAINTY_1T | FLOAT | N |  |
| 123 | SECTNOI | INTEGER | N |  |
| 124 | COLLID | VARCHAR(128) | N |  |
| 125 | VERSION | VARCHAR(122) | N |  |
| 126 | IMNP | FLOAT | N |  |
| 127 | DMNP | FLOAT | N |  |
| 128 | IMJC | FLOAT | N |  |
| 129 | IMFC | FLOAT | N |  |
| 130 | IMJBC | FLOAT | N |  |
| 131 | IMJFC | FLOAT | N |  |
| 132 | CRED | INTEGER | N |  |
| 133 | IXSCAN_SKIP_DUPS | CHAR(1) | N |  |
| 134 | IXSCAN_SKIP_SCREEN | CHAR(1) | N |  |
| 135 | EARLY_OUT | CHAR(1) | N |  |
| 136 | EXPANSION_REASON | CHAR(2) | N |  |
| 137 | BLOCK_FETCH | CHAR(1) | N |  |
| 138 | PER_STMT_ID | BIGINT | N |  |
| 139 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX04` (non unico): EXPLAIN_TIME, QUERYNO, QBLOCKNO
- `DSNU_PLTBIX08` (non unico): QUERYNO, EXPLAIN_TIME
- `DSN_DETCOST_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_FILTER_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | PLANNO | SMALLINT | N |  |
| 4 | APPLNAME | VARCHAR(24) | N |  |
| 5 | PROGNAME | VARCHAR(128) | N |  |
| 6 | COLLID | VARCHAR(128) | N |  |
| 7 | ORDERNO | INTEGER | N |  |
| 8 | PREDNO | INTEGER | N |  |
| 9 | STAGE | CHAR(9) | N |  |
| 10 | ORDERCLASS | INTEGER | N |  |
| 11 | EXPLAIN_TIME | TIMESTMP | N |  |
| 12 | MIXOPSEQNO | SMALLINT | N |  |
| 13 | REEVAL | CHAR(1) | N |  |
| 14 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 15 | SECTNOI | INTEGER | N |  |
| 16 | VERSION | VARCHAR(122) | N |  |
| 17 | PUSHDOWN | CHAR(1) | N |  |
| 18 | EXPANSION_REASON | CHAR(2) | N |  |
| 19 | PER_STMT_ID | BIGINT | N |  |
| 20 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX21` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX41` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_FILTER_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_FUNCTION_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | INTEGER | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | COLLID | VARCHAR(128) | N |  |
| 6 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 7 | EXPLAIN_TIME | TIMESTMP | N |  |
| 8 | SCHEMA_NAME | VARCHAR(128) | N |  |
| 9 | FUNCTION_NAME | VARCHAR(128) | N |  |
| 10 | SPEC_FUNC_NAME | VARCHAR(128) | N |  |
| 11 | FUNCTION_TYPE | CHAR(2) | N |  |
| 12 | VIEW_CREATOR | VARCHAR(128) | N |  |
| 13 | VIEW_NAME | VARCHAR(128) | N |  |
| 14 | PATH | VARCHAR(2048) | N |  |
| 15 | FUNCTION_TEXT | VARCHAR(1500) | N |  |
| 16 | FUNC_VERSION | VARCHAR(122) | N |  |
| 17 | SECURE | CHAR(1) | N |  |
| 18 | SECTNOI | INTEGER | N |  |
| 19 | VERSION | VARCHAR(122) | N |  |
| 20 | EXPANSION_REASON | CHAR(2) | N |  |
| 21 | PER_STMT_ID | BIGINT | N |  |
| 22 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX02` (non unico): APPLNAME, PROGNAME, EXPLAIN_TIME, QUERYNO, QBLOCKNO
- `DSNU_PLTBIX19` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX40` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_FUNCTION_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_KEYTGTDIST_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | APPLNAME | VARCHAR(128) | N |  |
| 3 | PROGNAME | VARCHAR(128) | N |  |
| 4 | COLLID | VARCHAR(128) | N |  |
| 5 | GROUP_MEMBER | VARCHAR(128) | N |  |
| 6 | SECTNOI | INTEGER | N |  |
| 7 | VERSION | VARCHAR(122) | N |  |
| 8 | EXPLAIN_TIME | TIMESTMP | N |  |
| 9 | IXSCHEMA | VARCHAR(128) | N |  |
| 10 | IXNAME | VARCHAR(128) | N |  |
| 11 | KEYSEQ | VARCHAR(128) | N |  |
| 12 | KEYVALUE | VARCHAR(2000) | N |  |
| 13 | TYPE | CHAR(1) | N |  |
| 14 | CARDF | FLOAT | N |  |
| 15 | KEYGROUPKEYNO | VARCHAR(254) | N |  |
| 16 | NUMKEYS | SMALLINT | N |  |
| 17 | FREQUENCYF | FLOAT | N |  |
| 18 | QUANTILENO | SMALLINT | N |  |
| 19 | LOWVALUE | VARCHAR(2000) | N |  |
| 20 | HIGHVALUE | VARCHAR(2000) | N |  |
| 21 | EXPANSION_REASON | CHAR(2) | N |  |
| 22 | PER_STMT_ID | BIGINT | N |  |
| 23 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX50` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_KEYTGTDIST_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_PGRANGE_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | TABNO | SMALLINT | N |  |
| 4 | RANGE | SMALLINT | N |  |
| 5 | FIRSTPART | SMALLINT | N |  |
| 6 | LASTPART | SMALLINT | N |  |
| 7 | NUMPARTS | SMALLINT | N |  |
| 8 | EXPLAIN_TIME | TIMESTMP | N |  |
| 9 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 10 | SECTNOI | INTEGER | N |  |
| 11 | APPLNAME | VARCHAR(24) | N |  |
| 12 | PROGNAME | VARCHAR(128) | N |  |
| 13 | COLLID | VARCHAR(128) | N |  |
| 14 | VERSION | VARCHAR(122) | N |  |
| 15 | EXPANSION_REASON | CHAR(2) | N |  |
| 16 | PER_STMT_ID | BIGINT | N |  |
| 17 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX22` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX42` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_PGRANGE_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_PGROUP_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | PLANNAME | VARCHAR(24) | N |  |
| 4 | COLLID | VARCHAR(128) | N |  |
| 5 | PROGNAME | VARCHAR(128) | N |  |
| 6 | EXPLAIN_TIME | TIMESTMP | N |  |
| 7 | VERSION | VARCHAR(122) | N |  |
| 8 | GROUPID | SMALLINT | N |  |
| 9 | FIRSTPLAN | SMALLINT | N |  |
| 10 | LASTPLAN | SMALLINT | N |  |
| 11 | CPUCOST | FLOAT | N |  |
| 12 | IOCOST | FLOAT | N |  |
| 13 | BESTTIME | FLOAT | N |  |
| 14 | DEGREE | SMALLINT | N |  |
| 15 | MODE | CHAR(1) | N |  |
| 16 | REASON | SMALLINT | N |  |
| 17 | LOCALCPU | SMALLINT | N |  |
| 18 | TOTALCPU | SMALLINT | N |  |
| 19 | FIRSTBASE | SMALLINT |  |  |
| 20 | LARGETS | CHAR(1) |  |  |
| 21 | PARTKIND | CHAR(1) |  |  |
| 22 | GROUPTYPE | CHAR(3) |  |  |
| 23 | ORDER | CHAR(1) |  |  |
| 24 | STYLE | CHAR(4) |  |  |
| 25 | RANGEKIND | CHAR(1) |  |  |
| 26 | NKEYCOLS | SMALLINT |  |  |
| 27 | LOWBOUND | VARCHAR(40) |  |  |
| 28 | HIGHBOUND | VARCHAR(40) |  |  |
| 29 | LOWKEY | VARCHAR(40) |  |  |
| 30 | HIGHKEY | VARCHAR(40) |  |  |
| 31 | FIRSTPAGE | CHAR(4) |  |  |
| 32 | LASTPAGE | CHAR(4) |  |  |
| 33 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 34 | HOST_REASON | SMALLINT |  |  |
| 35 | PARA_TYPE | CHAR(4) |  |  |
| 36 | PART_INNER | CHAR(1) |  |  |
| 37 | GRNU_KEYRNG | CHAR(1) |  |  |
| 38 | OPEN_KEYRNG | CHAR(1) |  |  |
| 39 | APPLNAME | VARCHAR(24) | N |  |
| 40 | SECTNOI | INTEGER | N |  |
| 41 | STRAW_MODEL | CHAR(1) | N |  |
| 42 | EXPANSION_REASON | CHAR(2) | N |  |
| 43 | PER_STMT_ID | BIGINT | N |  |
| 44 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX23` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX43` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_PGROUP_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_PREDICATE_SELECTIVITY

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | SECTNOI | INTEGER | N |  |
| 6 | COLLID | VARCHAR(128) | N |  |
| 7 | VERSION | VARCHAR(122) | N |  |
| 8 | PREDNO | INTEGER | N |  |
| 9 | INSTANCE | SMALLINT | N |  |
| 10 | SELECTIVITY | FLOAT | N |  |
| 11 | WEIGHT | FLOAT | N |  |
| 12 | ASSUMPTION | VARCHAR(128) | N |  |
| 13 | INSERT_TIME | TIMESTMP | N |  |
| 14 | EXPLAIN_TIME | TIMESTMP |  |  |
| 15 | REMARKS | VARCHAR(762) |  |  |
| 16 | EXPANSION_REASON | CHAR(2) | N |  |
| 17 | PER_STMT_ID | BIGINT | N |  |

Indici:

- `DSNU_PLTBIX38` (non unico): QUERYNO
- `DSNU_PLTBIX52` (non unico): EXPLAIN_TIME, QUERYNO

## DSN_PREDICAT_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | PREDNO | INTEGER | N |  |
| 6 | TYPE | CHAR(8) | N |  |
| 7 | LEFT_HAND_SIDE | VARCHAR(128) | N |  |
| 8 | LEFT_HAND_PNO | INTEGER | N |  |
| 9 | LHS_TABNO | SMALLINT | N |  |
| 10 | LHS_QBNO | SMALLINT | N |  |
| 11 | RIGHT_HAND_SIDE | VARCHAR(128) | N |  |
| 12 | RIGHT_HAND_PNO | INTEGER | N |  |
| 13 | RHS_TABNO | SMALLINT | N |  |
| 14 | RHS_QBNO | SMALLINT | N |  |
| 15 | FILTER_FACTOR | FLOAT | N |  |
| 16 | BOOLEAN_TERM | CHAR(1) | N |  |
| 17 | SEARCHARG | CHAR(1) | N |  |
| 18 | JOIN | CHAR(1) | N |  |
| 19 | AFTER_JOIN | CHAR(1) | N |  |
| 20 | ADDED_PRED | CHAR(1) | N |  |
| 21 | REDUNDANT_PRED | CHAR(1) | N |  |
| 22 | DIRECT_ACCESS | CHAR(1) | N |  |
| 23 | KEYFIELD | CHAR(1) | N |  |
| 24 | EXPLAIN_TIME | TIMESTMP | N |  |
| 25 | CATEGORY | SMALLINT | N |  |
| 26 | CATEGORY_B | SMALLINT | N |  |
| 27 | TEXT | VARCHAR(2000) | N |  |
| 28 | PRED_ENCODE | CHAR(1) | N |  |
| 29 | PRED_CCSID | SMALLINT | N |  |
| 30 | PRED_MCCSID | SMALLINT | N |  |
| 31 | MARKER | CHAR(1) | N |  |
| 32 | PARENT_PNO | INTEGER | N |  |
| 33 | NEGATION | CHAR(1) | N |  |
| 34 | LITERALS | VARCHAR(128) | N |  |
| 35 | CLAUSE | CHAR(8) | N |  |
| 36 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 37 | ORIGIN | CHAR(1) | N |  |
| 38 | UNCERTAINTY | FLOAT | N |  |
| 39 | SECTNOI | INTEGER | N |  |
| 40 | COLLID | VARCHAR(128) | N |  |
| 41 | VERSION | VARCHAR(122) | N |  |
| 42 | EXPANSION_REASON | CHAR(2) | N |  |
| 43 | PER_STMT_ID | BIGINT | N |  |
| 44 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX05` (non unico): EXPLAIN_TIME, PREDNO
- `DSNU_PLTBIX10` (non unico): QUERYNO, PREDNO
- `DSNU_PLTBIX20` (non unico): QUERYNO, EXPLAIN_TIME
- `DSN_PREDICAT_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_PTASK_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | PGDNO | SMALLINT | N |  |
| 4 | APPLNAME | VARCHAR(24) | N |  |
| 5 | PROGNAME | VARCHAR(128) | N |  |
| 6 | LPTNO | SMALLINT | N |  |
| 7 | KEYCOLID | SMALLINT |  |  |
| 8 | DPSI | CHAR(1) | N |  |
| 9 | LPTLOKEY | VARCHAR(40) |  |  |
| 10 | LPTHIKEY | VARCHAR(40) |  |  |
| 11 | LPTLOPAG | CHAR(4) |  |  |
| 12 | LPTHIPAG | CHAR(4) |  |  |
| 13 | LPTLOPG | CHAR(4) |  |  |
| 14 | LPTHIPG | CHAR(4) |  |  |
| 15 | LPTLOPT | SMALLINT |  |  |
| 16 | LPTHIPT | SMALLINT |  |  |
| 17 | KEYCOLDT | SMALLINT |  |  |
| 18 | KEYCOLPREC | SMALLINT |  |  |
| 19 | KEYCOLSCAL | SMALLINT |  |  |
| 20 | EXPLAIN_TIME | TIMESTMP | N |  |
| 21 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 22 | SECTNOI | INTEGER | N |  |
| 23 | COLLID | VARCHAR(128) | N |  |
| 24 | VERSION | VARCHAR(122) | N |  |
| 25 | EXPANSION_REASON | CHAR(2) | N |  |
| 26 | PER_STMT_ID | BIGINT | N |  |
| 27 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX24` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX44` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_PTASK_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_QUERYINFO_AUX

*Tabella ausiliaria LOB* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | AUXID | VARCHAR(17) | N |  |
| 2 | AUXVER | SMALLINT | N |  |
| 3 | AUXVALUE | CLOB | N |  |

Indici:

- `DSNU_PLTBIX36` (UNIQUE): AUXID, AUXVER

## DSN_QUERYINFO_AUX2

*Tabella ausiliaria LOB* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | AUXID | VARCHAR(17) | N |  |
| 2 | AUXVER | SMALLINT | N |  |
| 3 | AUXVALUE | BLOB | N |  |

Indici:

- `DSNU_PLTBIX37` (UNIQUE): AUXID, AUXVER

## DSN_QUERYINFO_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | QINAME1 | VARCHAR(128) | N |  |
| 4 | QINAME2 | VARCHAR(128) | N |  |
| 5 | APPLNAME | VARCHAR(24) | N |  |
| 6 | PROGNAME | VARCHAR(128) | N |  |
| 7 | VERSION | VARCHAR(122) | N |  |
| 8 | COLLID | VARCHAR(128) | N |  |
| 9 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 10 | SECTNOI | INTEGER | N |  |
| 11 | SEQNO | INTEGER | N |  |
| 12 | EXPLAIN_TIME | TIMESTMP | N |  |
| 13 | TYPE | CHAR(8) | N |  |
| 14 | REASON_CODE | SMALLINT | N |  |
| 15 | QI_DATA | CLOB | N |  |
| 16 | SERVICE_INFO | BLOB | N |  |
| 17 | QB_INFO_ROWID | ROWID | N |  |
| 18 | EXPANSION_REASON | CHAR(2) | N |  |
| 19 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX51` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_QUERYINFO_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_QUERY_AUX

*Tabella ausiliaria LOB* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | AUXID | VARCHAR(17) | N |  |
| 2 | AUXVER | SMALLINT | N |  |
| 3 | AUXVALUE | CLOB | N |  |

Indici:

- `DSNU_PLTBIX28` (UNIQUE): AUXID, AUXVER

## DSN_QUERY_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | TYPE | CHAR(8) | N |  |
| 3 | QUERY_STAGE | CHAR(8) | N |  |
| 4 | SEQNO | INTEGER | N |  |
| 5 | NODE_DATA | CLOB | N |  |
| 6 | EXPLAIN_TIME | TIMESTMP | N |  |
| 7 | QUERY_ROWID | ROWID | N |  |
| 8 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 9 | HASHKEY | INTEGER | N |  |
| 10 | HAS_PRED | CHAR(1) | N |  |
| 11 | SECTNOI | INTEGER | N |  |
| 12 | APPLNAME | VARCHAR(24) | N |  |
| 13 | PROGNAME | VARCHAR(128) | N |  |
| 14 | COLLID | VARCHAR(128) | N |  |
| 15 | VERSION | VARCHAR(122) | N |  |
| 16 | EXPANSION_REASON | CHAR(2) | N |  |

Indici:

- `DSNU_PLTBIX25` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX26` (non unico): QUERYNO, TYPE, QUERY_STAGE, EXPLAIN_TIME, SEQNO
- `DSNU_PLTBIX27` (unique (ROWID generato)): QUERY_ROWID
- `DSNU_PLTBIX45` (non unico): EXPLAIN_TIME, QUERYNO

## DSN_SORTKEY_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | PLANNO | SMALLINT | N |  |
| 4 | APPLNAME | VARCHAR(24) | N |  |
| 5 | PROGNAME | VARCHAR(128) | N |  |
| 6 | COLLID | VARCHAR(128) | N |  |
| 7 | SORTNO | SMALLINT | N |  |
| 8 | ORDERNO | SMALLINT | N |  |
| 9 | EXPTYPE | CHAR(3) | N |  |
| 10 | TEXT | VARCHAR(128) | N |  |
| 11 | TABNO | SMALLINT | N |  |
| 12 | COLNO | SMALLINT | N |  |
| 13 | DATATYPE | CHAR(18) | N |  |
| 14 | LENGTH | INTEGER | N |  |
| 15 | CCSID | INTEGER | N |  |
| 16 | ORDERCLASS | INTEGER | N |  |
| 17 | EXPLAIN_TIME | TIMESTMP | N |  |
| 18 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 19 | SECTNOI | INTEGER | N |  |
| 20 | VERSION | VARCHAR(122) | N |  |
| 21 | EXPANSION_REASON | CHAR(2) | N |  |
| 22 | PER_STMT_ID | BIGINT | N |  |
| 23 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX30` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX47` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_SORTKEY_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_SORT_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | PLANNO | SMALLINT | N |  |
| 4 | APPLNAME | VARCHAR(24) | N |  |
| 5 | PROGNAME | VARCHAR(128) | N |  |
| 6 | COLLID | VARCHAR(128) | N |  |
| 7 | SORTC | CHAR(5) | N |  |
| 8 | SORTN | CHAR(5) | N |  |
| 9 | SORTNO | SMALLINT | N |  |
| 10 | KEYSIZE | SMALLINT | N |  |
| 11 | ORDERCLASS | INTEGER | N |  |
| 12 | EXPLAIN_TIME | TIMESTMP | N |  |
| 13 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 14 | SECTNOI | INTEGER | N |  |
| 15 | VERSION | VARCHAR(122) | N |  |
| 16 | EXPANSION_REASON | CHAR(2) | N |  |
| 17 | PER_STMT_ID | BIGINT | N |  |
| 18 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX29` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX46` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_SORT_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_STATEMENT_CACHE_AUX

*Tabella ausiliaria LOB* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | AUXID | VARCHAR(17) | N |  |
| 2 | AUXVER | SMALLINT | N |  |
| 3 | AUXVALUE | CLOB | N |  |

Indici:

- `DSNU_PLTBIX15` (UNIQUE): AUXID, AUXVER

## DSN_STATEMENT_CACHE_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | STMT_ID | INTEGER | N |  |
| 2 | STMT_TOKEN | VARCHAR(240) |  |  |
| 3 | COLLID | VARCHAR(128) | N |  |
| 4 | PROGRAM_NAME | VARCHAR(128) | N |  |
| 5 | INV_DROPALT | CHAR(1) | N |  |
| 6 | INV_REVOKE | CHAR(1) | N |  |
| 7 | INV_LRU | CHAR(1) | N |  |
| 8 | INV_RUNSTATS | CHAR(1) | N |  |
| 9 | CACHED_TS | TIMESTMP | N |  |
| 10 | USERS | INTEGER | N |  |
| 11 | COPIES | INTEGER | N |  |
| 12 | LINES | INTEGER | N |  |
| 13 | PRIMAUTH | VARCHAR(128) | N |  |
| 14 | CURSQLID | VARCHAR(128) | N |  |
| 15 | BIND_QUALIFIER | VARCHAR(128) | N |  |
| 16 | BIND_ISO | CHAR(2) | N |  |
| 17 | BIND_CDATA | CHAR(1) | N |  |
| 18 | BIND_DYNRL | CHAR(1) | N |  |
| 19 | BIND_DEGRE | CHAR(1) | N |  |
| 20 | BIND_SQLRL | CHAR(1) | N |  |
| 21 | BIND_CHOLD | CHAR(1) | N |  |
| 22 | STAT_TS | TIMESTMP | N |  |
| 23 | STAT_EXEC | INTEGER | N |  |
| 24 | STAT_GPAG | INTEGER | N |  |
| 25 | STAT_SYNR | INTEGER | N |  |
| 26 | STAT_WRIT | INTEGER | N |  |
| 27 | STAT_EROW | INTEGER | N |  |
| 28 | STAT_PROW | INTEGER | N |  |
| 29 | STAT_SORT | INTEGER | N |  |
| 30 | STAT_INDX | INTEGER | N |  |
| 31 | STAT_RSCN | INTEGER | N |  |
| 32 | STAT_PGRP | INTEGER | N |  |
| 33 | STAT_ELAP | FLOAT | N |  |
| 34 | STAT_CPU | FLOAT | N |  |
| 35 | STAT_SUS_SYNIO | FLOAT | N |  |
| 36 | STAT_SUS_LOCK | FLOAT | N |  |
| 37 | STAT_SUS_SWIT | FLOAT | N |  |
| 38 | STAT_SUS_GLCK | FLOAT | N |  |
| 39 | STAT_SUS_OTHR | FLOAT | N |  |
| 40 | STAT_SUS_OTHW | FLOAT | N |  |
| 41 | STAT_RIDLIMT | INTEGER | N |  |
| 42 | STAT_RIDSTOR | INTEGER | N |  |
| 43 | EXPLAIN_TS | TIMESTMP | N |  |
| 44 | SCHEMA | VARCHAR(128) | N |  |
| 45 | STMT_TEXT | CLOB | N |  |
| 46 | STMT_ROWID | ROWID | N |  |
| 47 | BIND_RO_TYPE | CHAR(1) | N |  |
| 48 | BIND_RA_TOT | INTEGER | N |  |
| 49 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 50 | STAT_EXECB | BIGINT | N |  |
| 51 | STAT_GPAGB | BIGINT | N |  |
| 52 | STAT_SYNRB | BIGINT | N |  |
| 53 | STAT_WRITB | BIGINT | N |  |
| 54 | STAT_EROWB | BIGINT | N |  |
| 55 | STAT_PROWB | BIGINT | N |  |
| 56 | STAT_SORTB | BIGINT | N |  |
| 57 | STAT_INDXB | BIGINT | N |  |
| 58 | STAT_RSCNB | BIGINT | N |  |
| 59 | STAT_PGRPB | BIGINT | N |  |
| 60 | STAT_RIDLIMTB | BIGINT | N |  |
| 61 | STAT_RIDSTORB | BIGINT | N |  |
| 62 | LITERAL_REPL | CHAR(1) | N |  |
| 63 | STAT_SUS_LATCH | FLOAT | N |  |
| 64 | STAT_SUS_PLATCH | FLOAT | N |  |
| 65 | STAT_SUS_DRAIN | FLOAT | N |  |
| 66 | STAT_SUS_CLAIM | FLOAT | N |  |
| 67 | STAT_SUS_LOG | FLOAT | N |  |
| 68 | EXPANSION_REASON | CHAR(2) | N |  |
| 69 | ACCELERATED | CHAR(10) | N |  |
| 70 | STAT_ACC_ELAP | BIGINT | N |  |
| 71 | STAT_ACC_CPU | BIGINT | N |  |
| 72 | STAT_ACC_ROW | BIGINT | N |  |
| 73 | STAT_ACC_BYTE | BIGINT | N |  |
| 74 | STAT_ACC_1ROW | BIGINT | N |  |
| 75 | STAT_ACC_DB2 | BIGINT | N |  |
| 76 | STAT_ACC_EXEC | BIGINT | N |  |
| 77 | STAT_ACC_WAIT | BIGINT | N |  |
| 78 | ACCEL_OFFLOAD_ELIGIBLE | CHAR(1) | N |  |
| 79 | ACCELERATOR_NAME | VARCHAR(128) |  |  |
| 80 | PER_STMT_ID | BIGINT | N |  |
| 81 | STBLGRP | VARCHAR(128) | N |  |
| 82 | QUERY_HASH | CHAR(16) | N |  |
| 83 | QUERY_HASH_VERSION | INTEGER | N |  |
| 84 | STABILIZED | CHAR(1) | N |  |
| 85 | APPLCOMPAT | VARCHAR(10) | N |  |
| 86 | CNO | BIGINT | N |  |
| 87 | STAT_SUS_CHILDLLOCK | FLOAT | N |  |
| 88 | STAT_SUS_OTHERLLOCK | FLOAT | N |  |
| 89 | STAT_SUS_PAGESETPLOCK | FLOAT | N |  |
| 90 | STAT_SUS_PAGEPLOCK | FLOAT | N |  |
| 91 | STAT_SUS_OTHERPLOCK | FLOAT | N |  |
| 92 | STAT_SUS_PIPE | FLOAT | N |  |
| 93 | STAT_SUS_PQSYNC | FLOAT | N |  |
| 94 | STAT_ACC_TWDP | BIGINT | N |  |
| 95 | STAT_ACC_NWDP | BIGINT | N |  |
| 96 | STMT_HASHID2 | CHAR(8) |  |  |
| 97 | STMT_HASH2VER | INTEGER |  |  |
| 98 | AP_PLANID | CHAR(16) |  |  |
| 99 | AP_PLANHASH | CHAR(8) |  |  |
| 100 | AP_PLANHASHVER | INTEGER |  |  |
| 101 | CONNECTION_TYPE | CHAR(8) |  |  |
| 102 | CLIENT_USERID | VARCHAR(128) |  |  |
| 103 | CLIENT_APPLNAME | VARCHAR(255) |  |  |
| 104 | CLIENT_WRKSTNNAME | VARCHAR(255) |  |  |
| 105 | STAT_ZIIP_CPU | FLOAT |  |  |

Indici:

- `DSNU_PLTBIX12` (non unico): STMT_ID
- `DSNU_PLTBIX13` (non unico): STMT_TOKEN
- `DSNU_PLTBIX14` (non unico): EXPLAIN_TS DESC
- `DSN_STATEMENT_CACHE_ML_IX1` (non unico): STMT_HASHID2, AP_PLANID

## DSN_STATEMNT_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | APPLNAME | VARCHAR(24) | N |  |
| 3 | PROGNAME | VARCHAR(128) | N |  |
| 4 | COLLID | VARCHAR(128) | N |  |
| 5 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 6 | EXPLAIN_TIME | TIMESTMP | N |  |
| 7 | STMT_TYPE | CHAR(6) | N |  |
| 8 | COST_CATEGORY | CHAR(1) | N |  |
| 9 | PROCMS | INTEGER | N |  |
| 10 | PROCSU | INTEGER | N |  |
| 11 | REASON | VARCHAR(254) | N |  |
| 12 | STMT_ENCODE | CHAR(1) | N |  |
| 13 | TOTAL_COST | FLOAT | N |  |
| 14 | SECTNOI | INTEGER | N |  |
| 15 | VERSION | VARCHAR(122) | N |  |
| 16 | EXPANSION_REASON | CHAR(2) | N |  |
| 17 | APCOMPARE_STATUS | CHAR(1) | N |  |
| 18 | APREUSE_STATUS | CHAR(1) | N |  |
| 19 | APREUSE_VERSION | VARCHAR(122) | N |  |
| 20 | APREUSE_COPYID | INTEGER | N |  |
| 21 | EXPLAIN_TYPE | CHAR(1) | N |  |
| 22 | PER_STMT_ID | BIGINT | N |  |
| 23 | QUERY_HASH | CHAR(16) | N |  |
| 24 | FUNCTION_LVL | VARCHAR(10) | N |  |
| 25 | STMT_HASHID2 | CHAR(8) |  |  |
| 26 | STMT_HASH2VER | INTEGER |  |  |
| 27 | AP_PLANID | CHAR(16) |  |  |
| 28 | AP_PLANHASH | CHAR(8) |  |  |
| 29 | AP_PLANHASHVER | INTEGER |  |  |
| 30 | AP_SERVICE_DATA | VARCHAR(512) |  |  |
| 31 | CONNECTION_TYPE | CHAR(8) |  |  |
| 32 | CLIENT_USERID | VARCHAR(128) |  |  |
| 33 | CLIENT_APPLNAME | VARCHAR(255) |  |  |
| 34 | CLIENT_WRKSTNNAME | VARCHAR(255) |  |  |

Indici:

- `DSNU_PLTBIX03` (non unico): EXPLAIN_TIME, QUERYNO
- `DSNU_PLTBIX07` (non unico): QUERYNO, EXPLAIN_TIME
- `DSN_STATEMNT_ML_IX1` (non unico): STMT_HASHID2, AP_PLANID

## DSN_STAT_FEEDBACK

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | APPLNAME | VARCHAR(24) | N |  |
| 3 | PROGNAME | VARCHAR(128) | N |  |
| 4 | COLLID | VARCHAR(128) | N |  |
| 5 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 6 | EXPLAIN_TIME | TIMESTMP | N |  |
| 7 | SECTNOI | INTEGER | N |  |
| 8 | VERSION | VARCHAR(122) | N |  |
| 9 | TBCREATOR | VARCHAR(128) | N |  |
| 10 | TBNAME | VARCHAR(128) | N |  |
| 11 | IXCREATOR | VARCHAR(128) | N |  |
| 12 | IXNAME | VARCHAR(128) | N |  |
| 13 | COLNAME | VARCHAR(128) | N |  |
| 14 | NUMCOLUMNS | SMALLINT | N |  |
| 15 | COLGROUPCOLNO | VARCHAR(254) | N |  |
| 16 | TYPE | CHAR(1) | N |  |
| 17 | DBNAME | VARCHAR(24) | N |  |
| 18 | TSNAME | VARCHAR(24) | N |  |
| 19 | REASON | CHAR(8) | N |  |
| 20 | REMARKS | VARCHAR(254) | N |  |
| 21 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX16` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_STAT_FEEDBACK_APID_IX` (non unico): AP_PLANID

## DSN_STRUCT_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | PARENT | SMALLINT | N |  |
| 6 | TIMES | FLOAT | N |  |
| 7 | ROWCOUNT | INTEGER | N |  |
| 8 | ATOPEN | CHAR(1) | N |  |
| 9 | CONTEXT | CHAR(10) | N |  |
| 10 | ORDERNO | SMALLINT | N |  |
| 11 | DOATOPEN_PARENT | SMALLINT | N |  |
| 12 | QBLOCK_TYPE | CHAR(6) | N |  |
| 13 | EXPLAIN_TIME | TIMESTMP | N |  |
| 14 | QUERY_STAGE | CHAR(8) | N |  |
| 15 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 16 | ORIGIN | CHAR(1) | N |  |
| 17 | SECTNOI | INTEGER | N |  |
| 18 | COLLID | VARCHAR(128) | N |  |
| 19 | VERSION | VARCHAR(122) | N |  |
| 20 | EXPANSION_REASON | CHAR(2) | N |  |
| 21 | PER_STMT_ID | BIGINT | N |  |
| 22 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX09` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX11` (non unico): EXPLAIN_TIME
- `DSN_STRUCT_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_USERQUERY_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | SCHEMA | VARCHAR(128) | N |  |
| 3 | HINT_SCOPE | SMALLINT | N |  |
| 4 | QUERY_TEXT | CLOB | N |  |
| 5 | QUERY_ROWID | ROWID | N |  |
| 6 | QUERYID | BIGINT | N |  |
| 7 | USERFILTER | CHAR(8) | N |  |
| 8 | OTHER_OPTIONS | CHAR(128) | N |  |
| 9 | COLLECTION | VARCHAR(128) | N |  |
| 10 | PACKAGE | VARCHAR(128) | N |  |
| 11 | VERSION | VARCHAR(128) | N |  |
| 12 | REOPT | CHAR(1) | N |  |
| 13 | STARJOIN | CHAR(1) | N |  |
| 14 | MAX_PAR_DEGREE | INTEGER | N |  |
| 15 | DEF_CURR_DEGREE | CHAR(3) | N |  |
| 16 | SJTABLES | INTEGER | N |  |
| 17 | OTHER_PARMS | VARCHAR(128) | N |  |
| 18 | SELECTVTY_OVERRIDE | CHAR(1) | N |  |
| 19 | ACCESSPATH_HINT | CHAR(1) | N |  |
| 20 | OPTION_OVERRIDE | CHAR(1) | N |  |

Indici:

- `DSNU_PLTBIX34` (PRIMARY KEY): QUERYNO DESC

## DSN_USERQUERY_TABLE_AUX

*Tabella ausiliaria LOB* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | AUXID | VARCHAR(17) | N |  |
| 2 | AUXVER | SMALLINT | N |  |
| 3 | AUXVALUE | CLOB | N |  |

Indici:

- `DSNU_PLTBIX35` (UNIQUE): AUXID, AUXVER

## DSN_VIEWREF_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | APPLNAME | VARCHAR(24) | N |  |
| 3 | PROGNAME | VARCHAR(128) | N |  |
| 4 | VERSION | VARCHAR(122) | N |  |
| 5 | COLLID | VARCHAR(128) | N |  |
| 6 | CREATOR | VARCHAR(128) | N |  |
| 7 | NAME | VARCHAR(128) | N |  |
| 8 | TYPE | CHAR(1) | N |  |
| 9 | MQTUSE | SMALLINT | N |  |
| 10 | EXPLAIN_TIME | TIMESTMP | N |  |
| 11 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 12 | SECTNOI | INTEGER | N |  |
| 13 | EXPANSION_REASON | CHAR(2) | N |  |
| 14 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX31` (non unico): QUERYNO, EXPLAIN_TIME
- `DSNU_PLTBIX48` (non unico): EXPLAIN_TIME, QUERYNO
- `DSN_VIEWREF_TABLE_APID_IX` (non unico): AP_PLANID

## DSN_VIRTUAL_INDEXES

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | TBCREATOR | VARCHAR(128) | N |  |
| 2 | TBNAME | VARCHAR(128) | N |  |
| 3 | IXCREATOR | VARCHAR(128) | N |  |
| 4 | IXNAME | VARCHAR(128) | N |  |
| 5 | ENABLE | CHAR(1) | N |  |
| 6 | MODE | CHAR(1) | N |  |
| 7 | UNIQUERULE | CHAR(1) | N |  |
| 8 | COLCOUNT | SMALLINT | N |  |
| 9 | CLUSTERING | CHAR(1) | N |  |
| 10 | NLEAF | INTEGER | N |  |
| 11 | NLEVELS | SMALLINT | N |  |
| 12 | INDEXTYPE | CHAR(1) | N |  |
| 13 | PGSIZE | SMALLINT | N |  |
| 14 | FIRSTKEYCARDF | FLOAT | N |  |
| 15 | FULLKEYCARDF | FLOAT | N |  |
| 16 | CLUSTERRATIOF | FLOAT | N |  |
| 17 | PADDED | CHAR(1) | N |  |
| 18 | COLNO1 | SMALLINT |  |  |
| 19 | ORDERING1 | CHAR(1) |  |  |
| 20 | COLNO2 | SMALLINT |  |  |
| 21 | ORDERING2 | CHAR(1) |  |  |
| 22 | COLNO3 | SMALLINT |  |  |
| 23 | ORDERING3 | CHAR(1) |  |  |
| 24 | COLNO4 | SMALLINT |  |  |
| 25 | ORDERING4 | CHAR(1) |  |  |
| 26 | COLNO5 | SMALLINT |  |  |
| 27 | ORDERING5 | CHAR(1) |  |  |
| 28 | COLNO6 | SMALLINT |  |  |
| 29 | ORDERING6 | CHAR(1) |  |  |
| 30 | COLNO7 | SMALLINT |  |  |
| 31 | ORDERING7 | CHAR(1) |  |  |
| 32 | COLNO8 | SMALLINT |  |  |
| 33 | ORDERING8 | CHAR(1) |  |  |
| 34 | COLNO9 | SMALLINT |  |  |
| 35 | ORDERING9 | CHAR(1) |  |  |
| 36 | COLNO10 | SMALLINT |  |  |
| 37 | ORDERING10 | CHAR(1) |  |  |
| 38 | COLNO11 | SMALLINT |  |  |
| 39 | ORDERING11 | CHAR(1) |  |  |
| 40 | COLNO12 | SMALLINT |  |  |
| 41 | ORDERING12 | CHAR(1) |  |  |
| 42 | COLNO13 | SMALLINT |  |  |
| 43 | ORDERING13 | CHAR(1) |  |  |
| 44 | COLNO14 | SMALLINT |  |  |
| 45 | ORDERING14 | CHAR(1) |  |  |
| 46 | COLNO15 | SMALLINT |  |  |
| 47 | ORDERING15 | CHAR(1) |  |  |
| 48 | COLNO16 | SMALLINT |  |  |
| 49 | ORDERING16 | CHAR(1) |  |  |
| 50 | COLNO17 | SMALLINT |  |  |
| 51 | ORDERING17 | CHAR(1) |  |  |
| 52 | COLNO18 | SMALLINT |  |  |
| 53 | ORDERING18 | CHAR(1) |  |  |
| 54 | COLNO19 | SMALLINT |  |  |
| 55 | ORDERING19 | CHAR(1) |  |  |
| 56 | COLNO20 | SMALLINT |  |  |
| 57 | ORDERING20 | CHAR(1) |  |  |
| 58 | COLNO21 | SMALLINT |  |  |
| 59 | ORDERING21 | CHAR(1) |  |  |
| 60 | COLNO22 | SMALLINT |  |  |
| 61 | ORDERING22 | CHAR(1) |  |  |
| 62 | COLNO23 | SMALLINT |  |  |
| 63 | ORDERING23 | CHAR(1) |  |  |
| 64 | COLNO24 | SMALLINT |  |  |
| 65 | ORDERING24 | CHAR(1) |  |  |
| 66 | COLNO25 | SMALLINT |  |  |
| 67 | ORDERING25 | CHAR(1) |  |  |
| 68 | COLNO26 | SMALLINT |  |  |
| 69 | ORDERING26 | CHAR(1) |  |  |
| 70 | COLNO27 | SMALLINT |  |  |
| 71 | ORDERING27 | CHAR(1) |  |  |
| 72 | COLNO28 | SMALLINT |  |  |
| 73 | ORDERING28 | CHAR(1) |  |  |
| 74 | COLNO29 | SMALLINT |  |  |
| 75 | ORDERING29 | CHAR(1) |  |  |
| 76 | COLNO30 | SMALLINT |  |  |
| 77 | ORDERING30 | CHAR(1) |  |  |
| 78 | COLNO31 | SMALLINT |  |  |
| 79 | ORDERING31 | CHAR(1) |  |  |
| 80 | COLNO32 | SMALLINT |  |  |
| 81 | ORDERING32 | CHAR(1) |  |  |
| 82 | COLNO33 | SMALLINT |  |  |
| 83 | ORDERING33 | CHAR(1) |  |  |
| 84 | COLNO34 | SMALLINT |  |  |
| 85 | ORDERING34 | CHAR(1) |  |  |
| 86 | COLNO35 | SMALLINT |  |  |
| 87 | ORDERING35 | CHAR(1) |  |  |
| 88 | COLNO36 | SMALLINT |  |  |
| 89 | ORDERING36 | CHAR(1) |  |  |
| 90 | COLNO37 | SMALLINT |  |  |
| 91 | ORDERING37 | CHAR(1) |  |  |
| 92 | COLNO38 | SMALLINT |  |  |
| 93 | ORDERING38 | CHAR(1) |  |  |
| 94 | COLNO39 | SMALLINT |  |  |
| 95 | ORDERING39 | CHAR(1) |  |  |
| 96 | COLNO40 | SMALLINT |  |  |
| 97 | ORDERING40 | CHAR(1) |  |  |
| 98 | COLNO41 | SMALLINT |  |  |
| 99 | ORDERING41 | CHAR(1) |  |  |
| 100 | COLNO42 | SMALLINT |  |  |
| 101 | ORDERING42 | CHAR(1) |  |  |
| 102 | COLNO43 | SMALLINT |  |  |
| 103 | ORDERING43 | CHAR(1) |  |  |
| 104 | COLNO44 | SMALLINT |  |  |
| 105 | ORDERING44 | CHAR(1) |  |  |
| 106 | COLNO45 | SMALLINT |  |  |
| 107 | ORDERING45 | CHAR(1) |  |  |
| 108 | COLNO46 | SMALLINT |  |  |
| 109 | ORDERING46 | CHAR(1) |  |  |
| 110 | COLNO47 | SMALLINT |  |  |
| 111 | ORDERING47 | CHAR(1) |  |  |
| 112 | COLNO48 | SMALLINT |  |  |
| 113 | ORDERING48 | CHAR(1) |  |  |
| 114 | COLNO49 | SMALLINT |  |  |
| 115 | ORDERING49 | CHAR(1) |  |  |
| 116 | COLNO50 | SMALLINT |  |  |
| 117 | ORDERING50 | CHAR(1) |  |  |
| 118 | COLNO51 | SMALLINT |  |  |
| 119 | ORDERING51 | CHAR(1) |  |  |
| 120 | COLNO52 | SMALLINT |  |  |
| 121 | ORDERING52 | CHAR(1) |  |  |
| 122 | COLNO53 | SMALLINT |  |  |
| 123 | ORDERING53 | CHAR(1) |  |  |
| 124 | COLNO54 | SMALLINT |  |  |
| 125 | ORDERING54 | CHAR(1) |  |  |
| 126 | COLNO55 | SMALLINT |  |  |
| 127 | ORDERING55 | CHAR(1) |  |  |
| 128 | COLNO56 | SMALLINT |  |  |
| 129 | ORDERING56 | CHAR(1) |  |  |
| 130 | COLNO57 | SMALLINT |  |  |
| 131 | ORDERING57 | CHAR(1) |  |  |
| 132 | COLNO58 | SMALLINT |  |  |
| 133 | ORDERING58 | CHAR(1) |  |  |
| 134 | COLNO59 | SMALLINT |  |  |
| 135 | ORDERING59 | CHAR(1) |  |  |
| 136 | COLNO60 | SMALLINT |  |  |
| 137 | ORDERING60 | CHAR(1) |  |  |
| 138 | COLNO61 | SMALLINT |  |  |
| 139 | ORDERING61 | CHAR(1) |  |  |
| 140 | COLNO62 | SMALLINT |  |  |
| 141 | ORDERING62 | CHAR(1) |  |  |
| 142 | COLNO63 | SMALLINT |  |  |
| 143 | ORDERING63 | CHAR(1) |  |  |
| 144 | COLNO64 | SMALLINT |  |  |
| 145 | ORDERING64 | CHAR(1) |  |  |
| 146 | KEYTARGET_COUNT | SMALLINT | N |  |
| 147 | UNIQUE_COUNT | SMALLINT | N |  |
| 148 | IX_EXTENSION_TYPE | CHAR(1) | N |  |
| 149 | DATAREPEATFACTORF | FLOAT | N |  |
| 150 | SPARSE | CHAR(1) | N |  |

Indici:

- `DSNU_PLTBIX32` (non unico): ENABLE, MODE, TBCREATOR, TBNAME, IXCREATOR, IXNAME
- `DSNU_PLTBIX33` (non unico): TBCREATOR, TBNAME

## DSN_VIRTUAL_KEYTARGETS

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | ENABLE | CHAR(1) | N |  |
| 2 | IXNAME | VARCHAR(128) | N |  |
| 3 | IXSCHEMA | VARCHAR(128) | N |  |
| 4 | KEYSEQ | SMALLINT | N |  |
| 5 | COLNO | SMALLINT | N |  |
| 6 | ORDERING | CHAR(1) | N |  |
| 7 | TYPESCHEMA | VARCHAR(128) | N |  |
| 8 | TYPENAME | VARCHAR(128) | N |  |
| 9 | LENGTH | SMALLINT | N |  |
| 10 | LENGTH2 | INTEGER | N |  |
| 11 | SCALE | SMALLINT | N |  |
| 12 | NULLS | CHAR(1) | N |  |
| 13 | CCSID | INTEGER | N |  |
| 14 | SUBTYPE | CHAR(1) | N |  |
| 15 | DERIVED_FROM | VARCHAR(4000) | N |  |
| 16 | CARDF | FLOAT | N |  |

## NRTAB

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | NRTAB_NOMECOL | VARCHAR(128) | N |  |
| 2 | NRTAB_NOMETAB | VARCHAR(128) | N |  |
| 3 | NRTAB_CREATOR | VARCHAR(128) | N |  |
| 4 | NRTAB_PROGR | SMALLINT | N |  |
| 5 | NRTAB_TIPO | CHAR(8) | N |  |
| 6 | NRTAB_LUNGH | SMALLINT | N |  |
| 7 | NRTAB_DECIMALI | SMALLINT | N |  |
| 8 | NRTAB_DESCR | VARCHAR(762) | N |  |

## PLAN_TABLE

*Tabella* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | QUERYNO | INTEGER | N |  |
| 2 | QBLOCKNO | SMALLINT | N |  |
| 3 | APPLNAME | VARCHAR(24) | N |  |
| 4 | PROGNAME | VARCHAR(128) | N |  |
| 5 | PLANNO | SMALLINT | N |  |
| 6 | METHOD | SMALLINT | N |  |
| 7 | CREATOR | VARCHAR(128) | N |  |
| 8 | TNAME | VARCHAR(128) | N |  |
| 9 | TABNO | SMALLINT | N |  |
| 10 | ACCESSTYPE | CHAR(2) | N |  |
| 11 | MATCHCOLS | SMALLINT | N |  |
| 12 | ACCESSCREATOR | VARCHAR(128) | N |  |
| 13 | ACCESSNAME | VARCHAR(128) | N |  |
| 14 | INDEXONLY | CHAR(1) | N |  |
| 15 | SORTN_UNIQ | CHAR(1) | N |  |
| 16 | SORTN_JOIN | CHAR(1) | N |  |
| 17 | SORTN_ORDERBY | CHAR(1) | N |  |
| 18 | SORTN_GROUPBY | CHAR(1) | N |  |
| 19 | SORTC_UNIQ | CHAR(1) | N |  |
| 20 | SORTC_JOIN | CHAR(1) | N |  |
| 21 | SORTC_ORDERBY | CHAR(1) | N |  |
| 22 | SORTC_GROUPBY | CHAR(1) | N |  |
| 23 | TSLOCKMODE | CHAR(3) | N |  |
| 24 | TIMESTAMP | CHAR(16) | N |  |
| 25 | REMARKS | VARCHAR(762) | N |  |
| 26 | PREFETCH | CHAR(1) | N |  |
| 27 | COLUMN_FN_EVAL | CHAR(1) | N |  |
| 28 | MIXOPSEQ | SMALLINT | N |  |
| 29 | VERSION | VARCHAR(122) | N |  |
| 30 | COLLID | VARCHAR(128) | N |  |
| 31 | ACCESS_DEGREE | SMALLINT |  |  |
| 32 | ACCESS_PGROUP_ID | SMALLINT |  |  |
| 33 | JOIN_DEGREE | SMALLINT |  |  |
| 34 | JOIN_PGROUP_ID | SMALLINT |  |  |
| 35 | SORTC_PGROUP_ID | SMALLINT |  |  |
| 36 | SORTN_PGROUP_ID | SMALLINT |  |  |
| 37 | PARALLELISM_MODE | CHAR(1) |  |  |
| 38 | MERGE_JOIN_COLS | SMALLINT |  |  |
| 39 | CORRELATION_NAME | VARCHAR(128) |  |  |
| 40 | PAGE_RANGE | CHAR(1) | N |  |
| 41 | JOIN_TYPE | CHAR(1) | N |  |
| 42 | GROUP_MEMBER | VARCHAR(24) | N |  |
| 43 | IBM_SERVICE_DATA | VARCHAR(254) | N |  |
| 44 | WHEN_OPTIMIZE | CHAR(1) | N |  |
| 45 | QBLOCK_TYPE | CHAR(6) | N |  |
| 46 | BIND_TIME | TIMESTMP | N |  |
| 47 | OPTHINT | VARCHAR(128) | N |  |
| 48 | HINT_USED | VARCHAR(128) | N |  |
| 49 | PRIMARY_ACCESSTYPE | CHAR(1) | N |  |
| 50 | PARENT_QBLOCKNO | SMALLINT | N |  |
| 51 | TABLE_TYPE | CHAR(1) |  |  |
| 52 | TABLE_ENCODE | CHAR(1) | N |  |
| 53 | TABLE_SCCSID | SMALLINT | N |  |
| 54 | TABLE_MCCSID | SMALLINT | N |  |
| 55 | TABLE_DCCSID | SMALLINT | N |  |
| 56 | ROUTINE_ID | INTEGER | N |  |
| 57 | CTEREF | SMALLINT | N |  |
| 58 | STMTTOKEN | VARCHAR(240) |  |  |
| 59 | PARENT_PLANNO | SMALLINT | N |  |
| 60 | BIND_EXPLAIN_ONLY | CHAR(1) | N |  |
| 61 | SECTNOI | INTEGER | N |  |
| 62 | EXPLAIN_TIME | TIMESTMP | N |  |
| 63 | MERGC | CHAR(1) | N |  |
| 64 | MERGN | CHAR(1) | N |  |
| 65 | SCAN_DIRECTION | CHAR(1) |  |  |
| 66 | EXPANSION_REASON | CHAR(2) | N |  |
| 67 | PER_STMT_ID | BIGINT | N |  |
| 68 | AP_PLANID | CHAR(16) |  |  |

Indici:

- `DSNU_PLTBIX01` (non unico): APPLNAME, PROGNAME, BIND_TIME, QUERYNO, QBLOCKNO
- `DSNU_PLTBIX06` (non unico): QUERYNO, QBLOCKNO, PLANNO, MIXOPSEQ
- `DSNU_PLTBIX17` (non unico): QUERYNO, APPLNAME, PROGNAME, VERSION, COLLID, OPTHINT
- `DSNU_PLTBIX18` (non unico): QUERYNO, BIND_TIME
- `DSNU_PLTBIX39` (non unico): EXPLAIN_TIME, QUERYNO
- `PLAN_TABLE_APID_IX` (non unico): AP_PLANID

## VWCOL

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | A | VARCHAR(128) | N |  |
| 2 | B | VARCHAR(762) | N |  |
| 3 | C | INTEGER | N |  |
| 4 | D | VARCHAR(128) | N |  |
| 5 | E | CHAR(8) | N |  |
| 6 | F | SMALLINT | N |  |
| 7 | G | SMALLINT | N |  |
| 8 | H | CHAR(1) | N |  |
| 9 | I | SMALLINT | N |  |
| 10 | L | VARCHAR(762) | N |  |

## V_AUTH

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | STNAME | VARCHAR(128) | N |  |
| 2 | GRANTEE | VARCHAR(128) | N |  |

## V_DBAUTH

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | GRANTEE | VARCHAR(128) | N |  |
| 2 | NAME | VARCHAR(24) | N |  |

## V_OGGETTOPLAN

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DNAME | VARCHAR(24) | N |  |
| 2 | BNAME | VARCHAR(128) | N |  |
| 3 | BTYPE | CHAR(1) | N |  |

## V_PLANOGGETTO

*Vista* – righe: n.d.

| # | Colonna | Tipo | Null | Descrizione |
|---:|---|---|---|---|
| 1 | DNAME | VARCHAR(24) | N |  |
| 2 | BNAME | VARCHAR(128) | N |  |
| 3 | BTYPE | CHAR(1) | N |  |
