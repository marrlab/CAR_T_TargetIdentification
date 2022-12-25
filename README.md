# Computational identification of targets for CAR-T cell therapy in AML

This repository contains all jupyter notebooks to reproduce the results of the single-cell data analysis from: 

A. Gottschlich, M. Thomas, R. Grünmeier et al., "Single-cell transcriptomic atlas-guided development of chimeric antigen-receptor (CAR) T cells for the treatment of acute myeloid leukemia", Nature Biotechnology (2023).

The notebooks contain code for the following analyses:

- Preprocessing and Analysis of AML datasets including query to reference mapping
- Preprocessing and harmonization of single cell data across multiple organs using public datasets
- Combining public databases to infer genes coding for surface- and druggable proteins as well as analysis of bulk sequencing data

Note that the analysis was done in python 3 using ```scanpy``` v.1.4.6 to 1.9.1 and ```anndata``` v.0.7.1 to 0.8.0 unless otherwise stated. Some functions may have changed when using other package versions. 
Additionally, ```numpy``` (v. 1.18.2+), ```pandas``` (v. 1.3.5+) and ```scipy``` (v. 1.4.1+) are required. Numeric results can vary depending on package versions and e.g. minor results. All scRNA-seq figures were plotted using ```matplotlib``` and ```seaborn```. 


If the materials in this repository are of use to you, please consider citing the above publication.
