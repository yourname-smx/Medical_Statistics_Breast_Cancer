# Breast Cancer Patient Characteristics Analysis

## 乳腺癌患者临床病理特征统计分析

## 1. Project Introduction

本项目使用 Python 对模拟乳腺癌临床数据进行统计分析，
比较有淋巴结转移和无淋巴结转移患者的临床病理特征。

研究问题：

> 有淋巴结转移和无淋巴结转移的乳腺癌患者，其临床病理特征是否存在差异？

本项目综合应用描述性统计、正态性检验、Welch t 检验、
Mann-Whitney U 检验、卡方检验和 Fisher 精确检验，
完成乳腺癌患者基线特征分析。

---

## 2. Research Variables

本项目分析以下变量：

| Variable | 中文 | Variable Type |
|---|---|---|
| Age | 年龄 | Continuous |
| Tumor_Size | 肿瘤大小 | Continuous |
| Ki67 | Ki67表达水平 | Continuous |
| ER | 雌激素受体状态 | Binary |
| PR | 孕激素受体状态 | Binary |
| HER2 | HER2状态 | Binary |
| Lymph_Node | 淋巴结转移状态 | Binary |

其中：

Lymph_Node = 0：无淋巴结转移

Lymph_Node = 1：有淋巴结转移

---

## 3. Statistical Analysis Workflow

本项目统计分析流程如下：

Clinical Data

↓

Variable Classification

↓

Continuous Variables / Categorical Variables

↓

Continuous Variables:

- Descriptive Statistics
- Normality Test
- Welch t-test
- Mann-Whitney U Test

Categorical Variables:

- Contingency Table
- Chi-square Test
- Expected Frequency Check
- Fisher Exact Test

↓

P Value

↓

Characteristics of Breast Cancer Patients

---

## 4. Data Import

使用 pandas 读取乳腺癌临床数据：

```python
import pandas as pd

df = pd.read_csv(
    "breast_cancer_clinical3.csv"
)

print(
    "读取 breast_cancer_clinical3.csv 成功"
)