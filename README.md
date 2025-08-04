This repository contains the finalized Jupyter notebook used for imputation and correlation analysis of trauma patient proteomics data. The analysis was developed to support a manuscript focused on identifying biomarker patterns and subgroup-specific protein correlations in trauma populations.

FILE ----------------

Proteomics_Paper_Final_Code.ipynb: Main analysis notebook with code and markdown explanations.

OVERVIEW ----------------

The notebook performs the following steps:

Data Preprocessing: Filters and prepares protein abundance data, handling missing values and applying inclusion criteria.

Imputation: Uses Multivariate Imputation by Chained Equations (MICE) to impute missing protein values using a Random Forest estimator.

Correlation Analysis: Computes and visualizes correlation matrices for protein features and/or clinical metadata, highlighting phenotype-specific associations.

Visualization: Generates clear plots including heatmaps and scatterplots.


REQUIREMENTS ----------------

This notebook uses the following Python packages:

pandas

numpy

matplotlib

scikit-learn

openpyxl


Install requirements using:

pip install pandas numpy matplotlib scikit-learn openpyxl

USE CASE ----------------

This workflow is intended for researchers working with high-dimensional trauma proteomics datasets, especially those interested in robust handling of missing data and exploring correlation patterns among proteins across patient groups.


CITATION ----------------

If you use this code in your work, please cite the associated manuscript. 

HajerAliSinan. (2025). HajerAliSinan/TraumaProteomicsPaper2025: Trauma Proteomics Imputation and Correlation (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.16741038
