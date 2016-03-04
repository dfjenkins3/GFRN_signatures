# GFRN_signatures

This repository presents all analyses done for the paper "Genomic signature networks identify unique growth phenotypes and predict drug response in breast cancer patients." `ASSIGN` folder describes pathway prediction generation in cell lines and in patient samples.`GFRN_characterization_in_breast_cancer.Rmd`script has code for all the results described in the paper. 

# Datasets

You will need the following datasets for running the `GFRN_characterization_in_breast_cancer.Rmd` script:

1. ICBP breast cancer cell line gene expression dataset: icbp_Rsubread_tpmlog.txt
2. ICBP breast cancer cell line drug response dataset: [ICBP_drugs.txt](https://static-content.springer.com/esm/art%3A10.1186%2Fs13059-015-0658-5/MediaObjects/13059_2015_658_MOESM2_ESM.xlsx)
3. TCGA cancer tumor gene expression dataset: [GSM1536837_06_01_15_TCGA_24.tumor_Rsubread_TPM.txt.gz](http://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM1536837&format=file&file=GSM1536837%5F06%5F01%5F15%5FTCGA%5F24%2Etumor%5FRsubread%5FTPM%2Etxt%2Egz)
4. TCGA "normal" adjacent breast cancer gene expression dataset: [GSM1697009_06_01_15_TCGA_24.normal_Rsubread_TPM.txt.gz](http://www.ncbi.nlm.nih.gov/geo/download/?acc=GSM1697009&format=file&file=GSM1697009%5F06%5F01%5F15%5FTCGA%5F24%2Enormal%5FRsubread%5FTPM%2Etxt%2Egz)
5. TCGA PAM50 classification of tumor samples: [BRCA.547.PAM50.SigClust.Subtypes.txt](https://tcga-data.nci.nih.gov/docs/publications/brca_2012/BRCA.547.PAM50.SigClust.Subtypes.txt)
6. TCGA clinical dataset: [GSE62944_06_01_15_TCGA_24_548_Clinical_Variables_9264_Samples.txt.gz](http://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE62944&format=file&file=GSE62944%5F06%5F01%5F15%5FTCGA%5F24%5F548%5FClinical%5FVariables%5F9264%5FSamples%2Etxt%2Egz) 
7. ICBP cell line single pathway optimized prediction
8. ICBP cell line multi-pathway optimized prediction
9. TCGA cell line single pathway optimized prediction
10. TCGA cell line multi-pathway optimized prediction
11. Drug response assay 

# Required R packages
1. gplots
2. RColorBrewer
3. data.table
4. mclust

# Other Required Files:
`Key_ASSIGN_functions_balancedsig.R` - This file is available in this repository.
