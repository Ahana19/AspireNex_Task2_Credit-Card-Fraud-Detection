
# Credit Card Fraud Detection

## Table of Contents
- [Project Overview](https://pip.pypa.io/en/stable/)
- [Dataset](https://pip.pypa.io/en/stable/)
- [Usage](https://pip.pypa.io/en/stable/)
- [Exploratory Data Analysis](https://pip.pypa.io/en/stable/)
- [Feature Engineering](https://pip.pypa.io/en/stable/)
- [Model Training](https://pip.pypa.io/en/stable/)
- [Evaluation](https://pip.pypa.io/en/stable/)

## Project Overview
The Credit Card Fraud Detection project aims to detect fraudulent credit card transactions using various machine learning algorithms. The goal is to create a model that can identify potentially fraudulent transactions with high accuracy.

## Dataset
The dataset used for this project is the Credit Card Fraud Detection dataset, which is available on Kaggle. It contains transactions made by European cardholders in September 2013, with a total of 284,807 transactions. The dataset is highly imbalanced, with only 492 fraudulent transactions.

Time: The number of seconds elapsed between this transaction and the first transaction in the dataset.
V1-V28: The principal components obtained with PCA.
Amount: The transaction amount.
Class: The label (1 for fraud, 0 for non-fraud).
Link for the dataset - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Usage
1. Clone the repository
   ```sh
    https://github.com/Ahana19/AspireNex_Task2_Credit-Card-Fraud-Detection
    ```
2.Explore the dataset and visualize the features
3.Perform feature engineering
4.Train the model
5.Evaluate the model

## Exploratory Data Analysis
Before building the model, exploratory data analysis (EDA) is performed to understand the distribution of the data, detect outliers, and identify patterns or correlations between features. 

## Feature Engineering
Feature engineering involves creating new features or transforming existing features to improve the performance of the machine learning model. This step includes handling missing values, scaling features, encoding categorical variables, and addressing class imbalance.

## Model Training
Machine learning algorithm is been trained on the dataset, including Logistic Regression. The training process involves splitting the dataset into training and testing sets, fitting the model on the training data, and tuning hyperparameters for optimal performance.

## Evaluation
The performance of the model is evaluated using a metric such as  accuracy,precision,recall,F1-score.
