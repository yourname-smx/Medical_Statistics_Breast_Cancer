# Breast Cancer Survival Analysis

## 项目简介

本项目基于乳腺癌临床特征数据，利用 Python 进行生存分析，探索不同临床指标与患者总体生存（Overall Survival, OS）的关系。

主要方法包括：

- Kaplan-Meier 生存曲线
- Log-rank 检验
- Cox 比例风险回归
- C-index 模型评价


## 数据集

模拟构建100例乳腺癌患者数据，包括：

- Patient_ID
- Age
- Tumor_size
- TNM_stage
- ER
- PR
- HER2
- Ki67
- Survival_months
- Status

其中：

- Survival_months：随访时间（月）
- Status：生存状态（0=删失，1=死亡）


## 分析内容

### 1. Kaplan-Meier生存分析

绘制：

- 总体生存曲线
- TNM分期生存曲线
- ER分组生存曲线
- PR分组生存曲线
- HER2分组生存曲线
- Ki67高低表达生存曲线


### 2. Log-rank检验

比较不同临床因素分组之间的生存差异。


### 3. Cox回归分析

进行：

- 单因素Cox回归
- 多因素Cox回归

分析：

年龄、肿瘤大小、分期及分子指标对生存风险的影响。


### 4. 模型评价

使用：

- Hazard Ratio (HR)
- P value
- Concordance index (C-index)

评价预后因素和模型预测能力。
