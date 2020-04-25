# Predicted_enh_gene_regulation_ENCODE_Roadmap
Resource of predicted long-range enhancer-gene regulation based on diverse versions of data from ENCODE + Roadmap consortia
# Introduction
This repository contains predicted enhancer-gene links based on diverse versions of epigenetic data from ENCODE + Roadmap consortia. Currently (*04/24/2020*), three versions are provided, which are based on imputed DNase-seq and RNA-seq across 127 cell types, non-imputed DNase-seq and RNA-seq across 29 cell types and imputed H3K27ac and RNA-seq across 127 cell types. More versions will be provided in the near future.
# File
Three versions are stored in the different sub-repositories and the version is specified as the name of the repositories. In each repo, the predicted enhancer-gene links in each cell type are listed in different files, which is named as `cell_index.txt`. 
The name and detailed description of the cell type can be found at `ENCODE_cell_index.csv`. The description of the cell can be retrived by matching the `cell_index` from the file name and the `ID` column from the `ENCODE_cell_index.csv`. Since number of available cell types are different across versions, the `ENCODE_cell_index.csv` is specific to each version and can NOT be used for other versions.
