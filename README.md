## Introduction to PSI Framework 

## Background 

This article provides a detailed introduction specifically targeting the PSI framework. The article is divided into two parts: controlled experiments and ablation experiments. The control experiments involve replacing various components within the PSI framework to achieve changes and verification of the overall model performance status. The ablation experiments involve removing each component from the PSI model to demonstrate whether different inputs actually improve prediction accuracy. Relevant researchers can utilize the code from this experiment for further refinement. 

##  Data source 

The data for the PSI framework is sourced from the SHEIN website. Considering the security requirements of company data and the need to protect the company, researchers can obtain the data from the website themselves. The specific website is https://us.shein.com/flash-sale.html 

To facilitate the dissemination of knowledge and enable relevant experts and scholars to provide critiques and corrections on PSI, we have provided 20 pieces of data used to train the PSI framework. 

## Specific file description 

Data.xlsx contains relevant data scraped from flash sales, totaling 20 entries. 

The code in different_keywords.py is related to comment keyword extraction. 

EBBM25.py is the code proposed in this study for extracting keywords from comments using VADER and BM25 .

"Ablation_Experiment.py" is a test code for evaluating the performance of different components of the PSI model. 

Different network models.py are test codes for different PSI network model architectures .

"text_encoding_model_comparison.py" is a test code for different text encoding pre-training models related to PSI. 

"image_encoding_model_comparison.py" is a test code for different image encoding pre-training models related to PSI. 

###### Considering the cumbersome process of downloading images through the website for researchers, we have added code for image downloading, named "Image Download.py". To enhance the comprehensibility of the paper, we have also provided a detailed .docx file, named "Online Appendix", which includes detailed proportions related to classification, image features, text features, and other pertinent details. Furthermore, it compares the prediction performance of various network models against actual values. 











# PSI框架简介

## 背景介绍

本文是专门针对PSI框架的详细介绍，主要分成控制实验和消融实验两个部分，控制实验通过更换PSI框架中的各个组件来实现对于整体模型表现状态的更换和验证，消融实验通过利用移除PSI模型中的每一个组件来实现对于不同的输入输入是否对预测精度有实际性的提升有了详细的论证，相关研究人员可以利用本实验的代码做进一步的完善。

## 相关数据

PSI框架的数据来源于SHEIN网站，考虑到公司数据的安全需求和对该公司的保护，研究人员可以自行从网站上获取数据，具体网站为https://us.shein.com/flash-sale.html

在这里为了让知识更便于扩散，同时方便相关专家学者的对PSI的批评指正，我们加入了20条用来训练PSI框架的数据。

## 具体文件说明

Data.xlsx 是flash sales上爬取到的相关的数据，总共20条数据。

不同关键词.py 的代码是关于评论关键词提取的代码。

EBBM25.py 是本研究提出的利用VADER和BM25提取评论中关键词的代码。

消融实验.py 是关于PSI 模型不同组件部分性能的测试代码。

不同网络模型.py 是关于PSI不同网络模型架构的测试代码。

文本编码模型对比.py 是关于PSI的不同文本编码预训练模型的测试代码。

图像编码模型对比.py 是关于PSI的不同图像编码预训练模型的测试代码。

###### 考虑到研究人员通过网站下载图像过于繁琐， 我们补充了图像下载的代码，命名为 图像下载.py。 同时为了使论文内容更加便于理解，我们详细的补充了名为Online Appendix的.docx文件，其中有关于分类的详细比例，图像特征，文本特征等细节内容，并且对照了不同网络模型在真实值的预测情况。

