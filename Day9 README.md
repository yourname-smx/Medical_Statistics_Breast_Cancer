# Breast Cancer Clinical Statistical Analysis Using Python

## 项目简介

本项目基于乳腺癌临床数据，使用 Python 完成医学论文中常见的统计分析流程。

主要研究问题：

> 不同临床病理因素是否与乳腺癌淋巴结转移（Lymph Node Metastasis）相关？


本项目模拟真实 SCI 论文中的统计分析过程，包括：

- 临床数据整理
- 描述性统计
- 正态性检验
- 两组间差异分析
- 分类变量关联分析
- 基线表（Table 1）制作
- Logistic 回归分析
- OR值及95%置信区间计算
- 单因素和多因素危险因素分析


---

# 1. 项目研究问题


研究对象：

乳腺癌患者


研究结局：


Lymph_Node



定义：

|变量|含义|
|-|-|
|0|无淋巴结转移|
|1|有淋巴结转移|


研究因素：

|变量|含义|
|-|-|
|Age|年龄|
|Tumor_Size|肿瘤大小|
|Ki67|增殖指数|
|ER|雌激素受体|
|PR|孕激素受体|
|HER2|HER2状态|


---

# 2. 数据结构


数据文件：


breast_cancer_clinical3.csv