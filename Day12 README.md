# Breast Cancer Survival Analysis

## Project Overview

This project performs survival analysis of breast cancer patients using Python.

The aim is to explore the relationship between clinical factors and patient survival outcomes.

Methods:

- Kaplan-Meier survival analysis
- Log-rank test
- Clinical subgroup analysis


## Dataset

The dataset contains breast cancer clinical information:

| Variable | Description |
|---|---|
| Patient_ID | Patient ID |
| Age | Age |
| Stage | Tumor stage |
| ER | Estrogen receptor status |
| PR | Progesterone receptor status |
| HER2 | HER2 status |
| Ki67 | Proliferation index |
| Survival_months | Survival time |
| Status | Event indicator |

Status:

- 1 = Event occurred
- 0 = Censored


## Analysis

Survival analysis was performed for:

1. Overall survival

2. Tumor stage groups:
- Stage I
- Stage II
- Stage III

3. ER status:
- ER+
- ER-

4. Ki67 expression:
- High Ki67
- Low Ki67


## Tools

Python packages:

- pandas
- lifelines
- matplotlib


Install:

```bash
pip install pandas lifelines matplotlib