# Computational identification of targets for CAR-T cell therapy in AML

This repository contains all scripts to reproduce the results of the single-cell data from: 

A. Gottschlich, M. Thomas, R. Grünmeier et al., "Single-cell transcriptomic atlas-guided development of chimeric antigen-receptor (CAR) T cells for the treatment of acute myeloid leukemia", Nature Biotechnology (2023).

The notebooks contain code for the following analyses:

- Preprocessing and Analysis of AML datasets including query to reference mapping
- Preprocessing and harmonization of single cell data across multiple organs using public datasets
- Combining public databases to infer genes coding for surface- and druggable proteins as well as analysis of bulk sequencing data

Note that the analysis was done with scanpy v.1.4.6 to 1.9.1 and anndata v.0.7.1 to 0.8.0. Some functions have changed when using other package versions. 
Numeric results can vary depending on package versions and e.g. minor results.

If the materials in this repository are of use to you, please consider citing the above publication.
