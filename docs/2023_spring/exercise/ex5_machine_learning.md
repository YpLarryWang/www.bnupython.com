---
prev: ./ex4_crawler
---

# EX5: 机器学习作业

## 任务介绍

本次作业以kaggle数据科学竞赛的形式呈现。竞赛中，你将使用一些特征对公民的贷款审批状况进行二分类。具体细节请见[此处](https://www.kaggle.com/competitions/loan-status-binary-classification/overview)。

注意到，该比赛是私有比赛，需通过[本链接](https://www.kaggle.com/t/9396a44d01eb4156983cf68dc6f870fb)来参赛。


## 步骤

Step 1. 分析与预处理数据

- 对预测目标 **Y** 进行分析
  - 这是一个分类任务还是回归任务，这决定了你需要使用何种模型

- 对特征集 **X** 进行分析
  - 特征的含义是什么?
  - 是否包含缺省值?
  - 特征对预测有价值吗?
  - 特征需要数值化吗?

Step 2. 训练模型

- 测试各种模型
- 使用交叉验证
- 调参 (看文档)
- 模型集成

Step 3. 预测与提交

- 请将实验思路、流程、代码等整理到一个`.ipynb`文件中，直接在kaggle平台上提交。**注意在文件开头注明你的姓名和学号。**

## 温馨提示

请务必阅读kaggle上对本任务的背景介绍、数据介绍、比赛规则介绍等全部信息，并保证所提交的代码使用本比赛提供的数据并最终得到kaggle平台可用于评分的`submission.csv`文件。你无需提交任何额外文件。
