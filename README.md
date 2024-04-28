# Business Data Science Final Project Blog Publication & Code - 2021 Fall
**_Use Machine Learning models (KNN Classifier, Logistic Regression, Random Forest Classifier, XGBoost, CatBoost; technique: Voting Classifier, Pseudo Labeling) on previous credit card data to predict the likelihood of future default credit payments._**
[**Credit Card Default Detection**](https://medium.com/@shete.harshika/credit-card-default-detection-kaggle-a47c6bb5a35e)

## Introduction

In this blog post, we will walk you through the following concepts:

- Implementing custom transformer for sklearn pipeline (TargetCounter Feature)
- Constructing Feature Processing Pipeline using sklearn pipeline
- Hyperparameter tuning of various Classification models using simple for loops and GridSearchCV
- Classification Algorithms covered are as follows:
    - Logistic Regression
    - KNeighborsClassifier
    - RandomForestClassifier
    - XGBClassifier
    - CatboostClassifier
- Training a VotingClassifier using multiple models
- Pseudo Labeling technique to improve model performance

## Problem Description
- We have chosen a Kaggle dataset to explore and explain the different techniques described in the Introduction section.
- The business problem we are trying to solve is to detect whether the person will default in making the credit card payment for the next month.
- We had 30K rows describing data for different users, which we split in the 75/25 (train/test) split to describe the whole process of feature engineering, model training etc.
