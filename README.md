# Disparities in spatially variable gene calling highlight the need for benchmarking spatial transcriptomics methods

This repository contains all the scripts used to identify SVGs in each of the publicly available 10X Genomics Visium datasets associated with the study using 6 different packages:
  * SpatialDE
  * scGCO
  * SpaGCN
  * SPARK-X
  * Seurat
  * Squidpy
  
The raw data obtained from the 10X website is preprocessed using scanpy before the outputs are written to separate files that can be used downstream with all packages. To ensure the pre-processed data is available for downstream use with packages, the notebook for analysis with SpatialDE should be run first. The notebook for SVG analysis using Squidpy runs the same preprocessing steps on the raw data using Scanpy.

Simulated datasets generated for this study are available on Zenodo.

Links to the raw data used for the study can be found at the following links:
*[FF Left Ventricle](https://www.10xgenomics.com/resources/datasets/human-heart-1-standard-1-0-0)
*[FF Invasive Ductal Carcinoma Breast Tissue](https://www.10xgenomics.com/resources/datasets/human-breast-cancer-block-a-section-1-1-standard-1-0-0)
*[FF Lymph Node](https://www.10xgenomics.com/resources/datasets/human-lymph-node-1-standard-1-0-0)
*[FF Cerebellum](https://www.10xgenomics.com/resources/datasets/human-cerebellum-whole-transcriptome-analysis-1-standard-1-2-0)
*[FF Endometrial Adenocarcinoma Ovarian Tissue](https://www.10xgenomics.com/resources/datasets/human-ovarian-cancer-whole-transcriptome-analysis-stains-dapi-anti-pan-ck-anti-cd-45-1-standard-1-2-0)
*[FF Mouse Brain Coronal Section](https://www.10xgenomics.com/resources/datasets/mouse-brain-section-coronal-1-standard-1-1-0)
*[FFPE Prostate](https://www.10xgenomics.com/resources/datasets/normal-human-prostate-ffpe-1-standard-1-3-0)
*[FFPE Adenocarcinoma Prostate](https://www.10xgenomics.com/resources/datasets/human-prostate-cancer-adenocarcinoma-with-invasive-carcinoma-ffpe-1-standard-1-3-0)
*[FFPE Invasive Ductal Carcinoma Breast Tissue](https://www.10xgenomics.com/resources/datasets/human-breast-cancer-ductal-carcinoma-in-situ-invasive-carcinoma-ffpe-1-standard-1-3-0)


