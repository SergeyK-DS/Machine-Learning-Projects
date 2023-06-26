# Project: Customer Behavior Prediction for Retention

## Project Goal
The goal of this project is to predict customer behavior in order to retain them in the company.

## Contents
- Introduction
- Dataset Description
- Best Model and its Metrics

## Introduction
This project is based on analyzing customer data and their behavior, as well as using various machine learning models to predict customer churn. One of the best models applied is the CatBoostClassifier with default hyperparameters.

## Dataset Description
The dataset contains information about customers, including customer attributes described in the "Metadata" column. The dataset includes the following aspects:
- Customer churn in the last month (column "Churn").
- Services customers have subscribed to, including phone, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV, and movies.
- Customer account information, such as subscription duration, contract type, payment method, paperless billing usage, monthly and total charges.
- Demographic information about customers, including gender, age range, presence of partners and dependents.

## Best Model and its Metrics
The best model applied in the project is the CatBoostClassifier with default hyperparameters. The model evaluation metrics are as follows:

- Model(CatBoostClassifier)
- Precision_yes: 0.7
- Recall_yes: 0.53
- F1_yes: 0.6
- Accuracy: 0.81
- Precision_no: 0.84
- Recall_no: 0.92
- F1_no: 0.88
- AUC: 0.84

