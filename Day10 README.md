Risk Factor Analysis of Lymph Node Metastasis in Breast Cancer

1. Project Overview
Background

Lymph node metastasis is an important prognostic factor in breast cancer and plays a critical role in:

TNM staging
Treatment decision-making
Prognostic evaluation

This project aims to investigate whether clinical and pathological characteristics are associated with lymph node metastasis in breast cancer patients.

The main research question:

Which clinical factors are associated with lymph node metastasis in breast cancer?

Outcome variable:

Lymph_Node

0 = No lymph node metastasis
1 = Lymph node metastasis

Potential risk factors:

Age
Tumor size
Ki67 proliferation index
ER status
PR status
HER2 status
2. Research Workflow
Clinical Dataset
        |
        ↓
Data Cleaning & Quality Check
        |
        ↓
Descriptive Statistics
        |
        ↓
Distribution Assessment
        |
        ↓
Comparison Between LN(-) and LN(+)
        |
        ↓
Univariate Logistic Regression
        |
        ↓
Multivariate Logistic Regression
        |
        ↓
OR + 95% CI + P value
        |
        ↓
Publication-style Tables
3. Dataset Description

Dataset:breast_cancer_clinical3.csv


4. Environment
Python Libraries
pandas
numpy
scipy
statsmodels
matplotlib