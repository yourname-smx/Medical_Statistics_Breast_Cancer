# Breast Cancer Clinical Data Analysis

## Day 2: Descriptive Statistics Analysis

基于乳腺癌临床数据，使用 Python 进行描述性统计分析，
了解患者基本临床特征，并按照淋巴结转移状态进行分组比较。


---

# 1. Project Introduction


医学研究中，在进行假设检验和模型分析之前，
首先需要了解研究对象的基本特征。


描述性统计（Descriptive Statistics）主要用于：

- 描述患者基线特征
- 总结连续变量分布
- 比较不同患者组之间的临床特点


本项目以乳腺癌患者数据为例：

研究问题：

> 不同淋巴结状态（Lymph Node Negative vs Positive）
> 的患者，其年龄、肿瘤大小和Ki67表达是否存在临床特征差异？
> # 2. Dataset


数据文件：


breast_cancer_clinical1.csv
# 3. Analysis Objectives


本次分析主要完成：

## 1. 连续变量描述


包括：

- Mean（均值）
- Standard Deviation（标准差）
- Median（中位数）
- Minimum（最小值）
- Maximum（最大值）
- Q1（25%百分位数）
- Q3（75%百分位数）


---

## 2. 分组描述


根据：


Lymph_Node



分为：

### Lymph Node Negative

无淋巴结转移：


Lymph_Node = 0



### Lymph Node Positive

有淋巴结转移：


Lymph_Node = 1



比较：

- Age
- Tumor_Size
- Ki67


---

# 4. Statistical Concepts


## Continuous Variables


连续变量通常使用：


### 正态分布：


Mean ± SD


---

### 非正态分布：

Median (Q1,Q3)



