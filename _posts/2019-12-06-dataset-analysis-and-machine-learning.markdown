---
title: Dataset Analysis & Machine Learning
date: 2019-12-06 02:08:00 Z
layout: post
---

# **Diabetes prediction**
## **Introduction**
*Diabetes is considered as one of the deadliest and chronic diseases. Our project aims to predict diabetes based on many factors(features), like: age, family history, blood pressure, ... etc. You can check and download our dataset [here](https://www.kaggle.com/edubrq/diabetes).*
## **Data Analysis**
*By looking into our dataset, we found that we have some missing data, so we solved this by replacing these missing values in each attribute with the mean value of the data of this attribute.*
## **Methods**
*When model is divided into train and validation, it means that the training part wasn't considered in the validation part, and similarly the validation part wasn't considered in the training part. That's why we used the cross-validation, so that the whole data will be considered in both training and validation. See following diagram show more explanation.]*
![train.png](/uploads/train.png)
## **Linear Discriminant & Logistic Regression**
![lda.gif](/uploads/lda.gif)

## **K Nearest Neighbors**
![KNN.png](/uploads/KNN.png)

## **Here are the results:**
|                  | Linear Discriminant Analysis| K Nearest Neighbors Classifier|
| -------------    |:-------------:|  -----:|
| Accuracy         | 0.7708      |    0.77  |
| Sensitivity      | 0.5672      |    0.92  |
| Specificity      | 0.88        |    0.49  |
| P-value(CI 95%)  | 0.0000339   |  0.0005  |





