## Introduction to PSI Framework 

## Background 

This article provides a detailed introduction specifically targeting the PSI framework. The article is divided into two parts: controlled experiments and ablation experiments. The control experiments involve replacing various components within the PSI framework to achieve changes and verification of the overall model performance status. The ablation experiments involve removing each component from the PSI model to demonstrate whether different inputs actually improve prediction accuracy. Relevant researchers can utilize the code from this experiment for further refinement. 

##  Data source 

The data for the PSI framework is sourced from the SHEIN website. Considering the security requirements of company data and the need to protect the company, researchers can obtain the data from the website themselves. The specific website is https://us.shein.com/flash-sale.html 

To facilitate the dissemination of knowledge and enable relevant experts and scholars to provide criticism and corrections on PSI, we have made approximately 10% of the training data publicly available for experts to verify the operability of the code. The complete data will be made public after ensuring that it will not affect SHEIN's interests.

## Specific file description 

Data.csv contains relevant data crawled from flash sales, totaling 200 entries (approximately 10% of the data used in the paper. The complete data will be published only when it is confirmed that it will not harm the interests of the research subjects).

The code within Fumeus.zip, which compares various methods, serves as an experimental record of the methods employed within Fumeus.

The code for "Comparative experiment of different keywords.zip" is an experimental record of comparing different keywords.

The code in Comparative experiments across different networks.zip is the experimental record of comparisons among different networks.

The code in Baseline model comparison experiment.zip is an experimental record comparing PSI with linear regression and machine learning.

The code in Image and text encoding comparison experiment.zip is an experimental record of the image-text combination method.

The code in Ablation experiment.zip is the experimental record of the ablation experiment.

1_Dot_plot.docx represents the performance of each model on various random number seeds

###### Considering the cumbersome process of downloading images through the website for researchers, we have supplemented the code for image download, named Image Download.ipynb. To truly apply PSI as a method in the industrial sector, we will proceed with software development in the future and incorporate large language models (LLM) and retrieval-augmented generation (RAG) technologies as auxiliary tools to assist PSI in providing better decision support. The overall plan is scheduled to be completed in May-June 2025, and the complete software and underlying code will be uploaded to the specified website. Furthermore, to facilitate researchers in better applying our research findings, we have uploaded a portion of the research data and the complete PSI code (PSI framework.ipynb)











# PSI框架简介

## 背景介绍

本文是专门针对PSI框架的详细介绍，主要分成控制实验和消融实验两个部分，控制实验通过更换PSI框架中的各个组件来实现对于整体模型表现状态的更换和验证，消融实验通过利用移除PSI模型中的每一个组件来实现对于不同的输入输入是否对预测精度有实际性的提升有了详细的论证，相关研究人员可以利用本实验的代码做进一步的完善。

## 相关数据

PSI框架的数据来源于SHEIN网站，考虑到公司数据的安全需求和对该公司的保护，研究人员可以自行从网站上获取数据，具体网站为https://us.shein.com/flash-sale.html

在这里为了让知识更便于扩散，同时方便相关专家学者的对PSI的批评指正，我们公开了训练数据的约百分之十，以便各位专家检验代码的可运行性，完整的数据在确定不会影响到SHEIN的利益后公开。

## 具体文件说明

Data.csv 是flash sales上爬取到的相关的数据，总共200条数据（论文中数据的约10%，完整数据在确定不会对研究对象产生利益影响时进行公布）。

Comparison of various methods within Fumeus.zip 的代码是Fumeus内部各种方法的实验记录。

Comparative experiment of different keywords.zip 的代码是不同关键词对比的实验记录。

Comparative experiments across different networks.zip 的代码是不同网络对比的实验记录。

Baseline model comparison experiment.zip 的代码是PSI与线性回归和机器学习对比的实验记录。

Image and text encoding  comparison experiment.zip的代码是图像文本组合方法的实验记录。

Ablation experiment.zip的代码是消融实验的实验记录。

1_Dot_plot.docx是各个随机数种子上各模型的表现

###### 考虑到研究人员通过网站下载图像过于繁琐， 我们补充了图像下载的代码，命名为Image Download.ipynb。 为了让PSI作为一种方式真正的应用到工业界，我们在后续将进行软件的开发，并且加入large language models (LLM) 和 retrieval-augmented generation (RAG) 技术作为辅助帮助PSI更好进行决策支持，整体计划将于2025年5-6月份完成，完整的软件和底层代码将会上传至该网址。并且为了让研究人员更好的应用我们的研究，我们上传了部分研究数据和完整的PSI代码（PSI framework.ipynb）.
