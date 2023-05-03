# BHUMP_paper_translation_zh_cn

## Abstract

Lithium-ion batteries are ubiquitous in applications ranging from portable electronics to electric vehicles. Irrespective of the application, reliable real-time estimation of battery state of health (SOH) by on-board computers is crucial to the safe operation of the battery, ultimately safeguarding asset integrity. In this Article, we design and evaluate a machine learning pipeline for estimation of battery capacity fade—a metric of battery health—on 179 cells cycled under various conditions. The pipeline estimates battery SOH with an associated confidence interval by using two parametric and two non-parametric algorithms. Using segments of charge voltage and current curves, the pipeline engineers 30 features, performs automatic feature selection and calibrates the algorithms. When deployed on cells operated under the fast-charging protocol, the best model achieves a root-mean-squared error of 0.45%. This work provides insights into the design of scalable data-driven models for battery SOH estimation, emphasizing the value of confidence bounds around the prediction. The pipeline methodology combines experimental data with machine learning modelling and could be applied to other critical components that require real-time estimation of SOH.

## 获取原文

原文在[这里](https://www.nature.com/articles/s42256-021-00312-3)。

在arXiv上有原文[预印本](https://arxiv.org/abs/2102.00837)，请参考。

## 说明

图表内容不做翻译，保留原文格式。

要编译[document.tex](./document.tex)请先下载作者在arXiv发布的相关[资源](https://arxiv.org/e-print/2102.00837v1)，解压到`assets`目录下。本仓库提供编译好的[pdf文档](./document.pdf)。