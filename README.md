# Disparities in spatially variable gene calling highlight the need for benchmarking spatial transcriptomics methods

This repository contains all the scripts used to identify SVGs in the publicly available 10X Genomics FF Endometrial Adenocarcinoma Ovarian Tissue using 5 different packages:
  * SpatialDE
  * scGCO
  * SpaGCN
  * SPARK-X
  * Seurat
  
The raw data obtained from the 10X website is preprocessed using scanpy before the outputs are written to separate files that can be used downstream with all packages. To ensure the pre-processed data is available for downstream use with packages, the notebook for analysis with SpatialDE should be run first.
