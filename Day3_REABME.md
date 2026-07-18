Day 3: Normality Test Analysis

基于乳腺癌临床数据，使用 Python 进行连续变量正态性检验，
判断数据分布特点，并为后续统计分析方法选择提供依据。

---

# 1. Project Introduction

在医学统计分析中，对于连续变量（continuous variables），
选择统计方法前需要判断数据是否符合正态分布。

本项目以乳腺癌患者临床数据为例：

研究问题：

> 不同淋巴结状态（Lymph Node Negative vs Positive）的患者，
> 其年龄、肿瘤大小和Ki67表达是否具有不同的数据分布特征？
> # 2. Dataset

数据文件：


breast_cancer_clinical1.csv
# 3. Analysis Objective

本次分析主要关注三个连续变量：

## 1. Age

患者年龄


## 2. Tumor_Size

原发肿瘤大小


## 3. Ki67

肿瘤细胞增殖指数


目标：

判断：

- 是否符合正态分布
- 后续是否适合使用t检验

或者：

- 使用非参数检验Mann-Whitney U test
