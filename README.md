### Credit-Card-Fraud-Detection model

This repository contains a predictive and classifying project for Credit Card Fraud Detection using Python and the Scikit-Learn library. The dataset used in this project is the "Credit Card Fraud Detection" dataset from Kaggle.

Dataset Description:
The dataset consists of 284,807 transactions, out of which 492 are fraudulent. Each transaction is represented by 28 features, including variables such as transaction amount, time, and merchant category.

Project Goals:
1. Preprocess the data to handle missing values, outliers, and feature engineering.
2. Split the data into training and testing sets.
3. Train and evaluate Random Forest machine learning algorithm for Credit Card Fraud Detection dataset.
4. Assesing algorithm's quality based on its accuracy (AUC - Area Under the ROC Curve)
5. Deploy the selected algorithm in a production environment for real-time fraud detection.

Project Structure:
The project is organized into the following directories and files:
- credit_card_fraud_detection/ (root directory)
  - data/ (contains the original dataset)
    - creditcard.csv (import original dataset)
    - data_preprocessing  (preprocessing the data - data wrangling)
    - train_test_split  (splitting the data into training and testing sets)
    - model_training (training and evaluating random forest algorithms)
    - model_deployment (deploying the selected algorithm in a production environment)
