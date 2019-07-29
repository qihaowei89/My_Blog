---
title: 使用Bioconductor软件包分析癌症基因组学和表观基因组学数据(基于TCGA数据库)
author: ''
date: '2019-07-16'
slug: 使用bioconductor软件包分析癌症基因组学和表观基因组学数据-基于tcga数据库
categories:
  - R
  - TCGA
tags: []
css: []
description: ''
highlight: yes
scripts: []
---

该工作流程基于[TCGA Workflow: Analyze cancer genomics and epigenomics data using Bioconductor packages ](https://f1000research.com/articles/5-1542/v2) 

---
示例数据可以在`TCGAWorkflowData`包中找到   
---

# 安装

```
if (!"BiocManager" %in% rownames(installed.packages()))
     install.packages("BiocManager")
BiocManager::install("TCGAWorkflow")
```


