# Credit Card Delinquency Prediction

## Abstract

This project aims to predict credit card delinquency for the upcoming month using a dataset from the UCI Machine Learning Repository. The dataset consists of 30,000 instances, 24 features, and one target variable, including credit limit, demographic details, payment history, and bill statements. We meticulously processed the data and engineered features to prepare it for model training. Four machine learning algorithms were developed and evaluated, including Logistic Regression using Gradient Descent, Hard-Margin SVM, Gaussian Naive Bayes, and a Neural Network implemented via TensorFlow and Keras. The models' performances were assessed based on precision, recall, accuracy, and other relevant metrics, with a focus on predictive power and computational efficiency to aid financial institutions in mitigating risks related to credit lending.

## Introduction

**Business Problem Definition:** Financial institutions aim to predict client delinquency on credit card payments to reduce financial risk, refine lending strategies, and enhance customer service. Accurate predictions facilitate preventive measures by identifying clients at risk of default. This research aims to estimate customer defaults in the following month based on historical data to minimize potential financial losses.

**Problem Setting:** This project tackles a binary classification task to predict whether a client will default (1) or not (0) in the next month using historical payment data and client information, without reliance on pre-built libraries for model development.

## Data Description

**Data Source:** The dataset is sourced from the UCI Machine Learning Repository, containing 30,000 records and 25 instances. It includes features such as credit limit, gender, education, marital status, age, past payment history, bill statements, and previous payment amounts.

**Data Dictionary:** The dataset includes features such as default payment next month, gender, education, marriage status, age, payment history, bill amounts, and payment amounts.

## Methods: Model Development

**Dataset Splitting:** We partitioned the balanced dataset into training and test sets with a 75-25 split to evaluate model performance against unseen data.

**Model Development:** Four machine learning algorithms were developed:
1. Logistic Regression Model Using Gradient Descent
2. Hard-Margin SVM
3. Gaussian Naive Bayes
4. Neural Networks (Multi-Layer Perceptron Classifier) implemented via TensorFlow and Keras.

Each model was tuned and calibrated to optimize performance and generalize well to new data, with performance tuning employed to avoid overfitting.

## Conclusion

This README provides an overview of the project, including the problem statement, data description, and model development methodology. Subsequent sections will delve into detailed implementation, optimization strategies, and comparative analysis of model performances.

---

**Note:** For detailed implementation code, analysis, and results, please refer to the respective project files in this repository.
