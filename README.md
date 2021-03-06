## analysis codes and flows in cell line comparison.

We analized expression pattern among liver cancer cell lines.

There are Rmarkdown files (.rmd) and their output htmls (.html) by Rstudio.  
Starting materials such as "CCLE_Expression.Arrays_2013-03-18.tar.gz" are not deposited here.  
Please get them from Broad Institute, TCGA, NCBI GEO and so on.  

Analysis environment is described by "SessionInfo" function at last part of htmls.
Used packages are listed up at the section.

Description of each file and the purpose.

- 77GEarray_re 
    - Clustering in digestive cell lines from CCLE.

- 87_2garray_re_mod
    - Clustering in liver cancer cell lines.
    - DEG analysis in liver cancer cell line cluster.

- R385_cellline_pca
    - Principal Component Analysis about liver cancer cell lines.
    - Ploting score plot.

- R400_dapc_test
    - DAPC analysis about liver cancer cell lines
    - Searching suitable number of cluster.
    - Ploting loading plot

- 103_g2array_david _mod
    - Gene ontology enrichment analysis using DAVID

- 145cell_establish_rep
    - Comparison of cell line establishment reports.
    - Examination of age between patients who cell line established from.

- 126TCGA_Celllinecomparison_mod
    - Expression pattern analysis using TCGA HCC cohort.
    - Proportion of expression pattern evaluated.

- 157clin_clust_anals_mod
    - Analysis clinical sample cluster
    - survival analysis is done

- R174_cln_clst_re
    - Analysis clinical sample cluster
    - several clinical information, such as age, bmi, and fetoprotein was evaluated.

- R176_clin_clst_expanal_re_mod
    - Analysis clinical sample cluster
    - sample information such as percent tumor cell was evalueted.

- 137PCA_renormalize_redo
    - Comparison of expression pattern using Primary Cell Atlas
    - Clustering in liver cancer cell lines

- R180_cor_with_FB_visualize_mod
    - Comparison of expression pattern using Primary Cell Atlas
    - Representitive vector comparison

- 150compare_FB_mod2
    - Comparison CCLE cell lines by Fibroblast representitive vector

- 81emt_cntr
    - expression check of EMT
    - GSE10393

- 82emt_cntr2
    - expression check of EMT
    - GSE28798

- 83emt_cnt_GSE74996
    - expression check of EMT
    - GSE74996

- R387_hcc_tcga_gsva
    - GSVA analysis in TCGA HCC RNA seq data
    
- R389_cellline_and_tissue
    - Number of cell line and TCGA tissue

- R390_limore_check
    - Expression analysis about LIMORE RNA-Seq Data




License: GPLv3 about my codes.

Citation: xxx