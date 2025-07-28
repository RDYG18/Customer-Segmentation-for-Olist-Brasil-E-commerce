# Customer Segmentation Olist 

## Table of Contents
- [Project Background](#project-background)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Models Building](#models-building)
  - [Model building (original data)](#model-building-original-data)
  - [Model building oversampled data (SMOTE)](#model-building-oversampled-data-smote)
  - [Model building undersampled data](#model-building-undersampled-data)
- [Evaluation and Optimization ](#evaluation-and-optimization)
  - [Hyperparameter Tuning comparison](#hyperparameter-tuning-comparison)
  - [Final Model Evaluation on Test Set ](#final-model-evaluation-on-test-set)
  - [Future importances](#future-importances)
  - [Pipeline Evaluation](#pipeline-evaluation)
- [Insights](#insights)
- [Business Recommendations](#business-recommendations)
- [Assumptions & Limitations](#assumptions--limitations)
- [Setup Instructions](#setup-instructions)

---

## Project Background 
Olist is a leading Brazilian e-commerce marketplace that connects small and medium-sized sellers to major online retail platforms. With thousands of active customers, it became clear that a one-size-fits-all approach to retention and marketing was no longer effective. As part of the Data Science team at Olist a leading Brazilian e-commerce marketplace I partnered with Marketing and Customer Relationship teams to address a key challenge, segmenting a rapidly growing and diverse customer base. We applied **RFM (Recency, Frequency, Monetary)** analysis to capture behavioral patterns in purchasing activity.

I led the development of an **unsupervised clustering model** to group customers into actionable segments such as VIPs, high-potential buyers, and inactive users. This segmentation enabled the design of personalized retention strategies, loyalty programs, and targeted campaigns. The results helped optimize marketing investments. 

--- 

## Exploratory Data Analysis 


