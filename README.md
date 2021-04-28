# scRNAseq_PBMCs

This repo contains scripts used to finish scRNA-seq analysis from seven porcine PBMC samples, detailed in the manuscript "Reference transcriptomes of porcine peripheral immune cells created through bulk and single-cell RNA sequencing" by Herrera-Uribe & Wiarda et al, 2021 (Preprint), available at https://doi.org/10.1101/2021.04.02.438107.

Initial analyses (scripts steps 001 thorugh 006) were completed by myself (Jayne Wiarda) and Sathesh Sivasankaran (https://github.com/satheshsiva/). I designed the workflow and scripts used for analysis, originally created for analysis of a different scRNA-seq dataset (not yet published). Sathesh then used these scripts as template and plugged in data for the seven PBMC samples, and this yielded a file called 'PBMC7IntegratedNormalized_11042020.RData' that I used to further analyze the data. The initial scripts are located in Sathesh's personal repository, https://github.com/satheshsiva/PBMC_scRNAseq.

Further scripts in this repository include:

| Script Name | Script Description |
| ----------- | ------------------ |
| 007_ClusterCharacterization | Further characterizing cell clusters to identify general cell types described in previous porcine literature |
| 008_GeneSetEnrichmentAnalysis | Performing gene set enrichment analyses based on gene set signatures for particular sorted cell populations used for bulk RNA-seq analyses; bulk RNA-seq gene sets are compared to single-cell gene profiles to determine enrichment for each individual cell in our scRNA-seq dataset |
| 009_CD4subset | Revamped analysis of only CD4+ T cells from scRNA-seq data |
| 010_GDsubset | Revamped analysis of only CD4+ T cells from scRNA-seq data |

All scripts used for this manuscript are collated and deposited at https://github.com/USDA-FSEPRU/PorcinePBMCs_bulkRNAseq_scRNAseq as well.
