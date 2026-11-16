# Colorectal Cancer Biomarkers and Drug Candidates — Supplementary Data

## Overview

This repository contains supplementary datasets, bioinformatics analysis outputs, and machine learning results related to the identification of potential biomarkers and drug candidates in colorectal cancer (CRC).

The repository organizes gene expression datasets, differential expression analysis results, functional enrichment outputs, protein–protein interaction network information, and machine learning analyses to facilitate data accessibility, transparency, and reproducibility.

## Repository Structure

The repository is organized into five main directories:

### 1. Data Collection

Contains gene expression datasets and supporting files used for the analysis.

Included materials comprise:

- Publicly available gene expression datasets obtained from the Gene Expression Omnibus (GEO).
- Raw gene expression count matrices.
- Dataset metadata and sample information.
- Merged gene expression datasets.
- Differentially expressed gene lists and related data files.

### 2. Data Preprocessing and Machine Learning

Contains data preprocessing materials, machine learning outputs, and model evaluation results.

Included materials comprise:

- Data preprocessing and analysis scripts.
- Gene expression matrices used for downstream analysis.
- Feature selection results.
- Selected gene lists generated using different machine learning approaches.
- Model performance comparisons.
- Receiver operating characteristic (ROC) curves.
- Gene expression heatmaps and boxplots.

Machine learning approaches represented in the repository include Random Forest, Support Vector Machine (SVM), XGBoost, LASSO, Linear Discriminant Analysis (LDA), and Gaussian Naive Bayes.

### 3. DEGS Visualization

Contains graphical outputs and supporting materials from differential gene expression analysis.

Included materials comprise:

- Volcano plots illustrating differential gene expression.
- Visualizations of upregulated and downregulated genes.
- Differential expression analysis scripts and supporting documents.

These visualizations support the interpretation of gene expression differences between the analyzed sample groups.

### 4. Enrichment Analysis

Contains outputs related to the functional interpretation of differentially expressed genes and candidate biomarkers.

These analyses support the investigation of biological processes, molecular functions, cellular components, and potentially relevant signaling pathways associated with colorectal cancer.

### 5. String

Contains supporting materials related to protein–protein interaction (PPI) network analysis using STRING.

These materials support the exploration of protein interactions and the identification of potentially important molecular targets within the analyzed gene sets.

## Data Sources

The gene expression datasets included in this repository are associated with the following GEO accession numbers:

- GSE156451
- GSE164492
- GSE180440
- GSE221925
- GSE50760

The original datasets are accessible through the [NCBI Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/).

## Research Applications

The supplementary materials may be useful for:

- Investigating gene expression alterations associated with colorectal cancer.
- Exploring potential diagnostic and prognostic biomarkers.
- Comparing machine learning approaches for biomarker prioritization.
- Examining functional enrichment and molecular interaction networks.
- Supporting computational investigations of potential therapeutic targets.
- Facilitating further validation and independent analysis of candidate genes.

## Data Availability

The supplementary datasets, analytical outputs, and supporting materials are available in the corresponding directories of this repository.

Original publicly available gene expression datasets can be accessed through the NCBI Gene Expression Omnibus using their respective accession numbers.

## Reproducibility and Limitations

The repository provides supporting datasets, results, and available analytical documentation to facilitate examination of the computational workflow.

Reproducibility depends on the availability of the relevant preprocessing procedures, analysis scripts, software dependencies, model parameters, and data processing settings.

The identified biomarkers and potential therapeutic targets should be considered computational candidates requiring appropriate independent and experimental validation.

## Repository Maintainer

**GitHub:** [zeeshandani999](https://github.com/zeeshandani999)

## Intended Use

This repository is intended for academic research, bioinformatics analysis, and educational purposes. The included computational findings should not be interpreted as clinically validated diagnostic biomarkers or approved therapeutic recommendations.
