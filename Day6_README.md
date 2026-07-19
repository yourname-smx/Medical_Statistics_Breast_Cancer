# Breast Cancer Clinical Data Analysis

## Day 6: Categorical Variable Analysis

## Chi-square Test & Fisher Exact Test


---

# 1. Project Introduction


在医学研究中，除了连续变量（Age、Tumor_Size、Ki67）外，
临床数据中还包含大量分类变量。


例如：

- ER status
- PR status
- HER2 status
- Lymph Node metastasis


本项目学习：

> 如何分析两个分类变量之间是否存在统计学关联。


研究问题：

> 乳腺癌患者的ER、PR、HER2表达状态是否与淋巴结转移有关？
# 2. Statistical Workflow



Categorical Variables

    ↓

Contingency Table

    ↓

Chi-square Test

    ↓

Check Expected Frequency

    ↓

Expected frequency adequate

    ↓

Chi-square test

Expected frequency too small

    ↓

Fisher Exact Test



---

# 3. Dataset


数据文件：


breast_cancer_clinical3.csv