### Credit-Card-Fraud-Detection model

This repository contains a predictive and classifying project for Credit Card Fraud Detection using Python and the Scikit-Learn library. The dataset used in this project is the "Credit Card Fraud Detection" dataset from Kaggle.

Dataset Description:
It includes transactions from two days, with 492 fraud cases out of a total of 284,807 transactions. This results in a highly unbalanced dataset, with the positive class (frauds) making up only 0.172% of all transactions.

The dataset comprises only numerical input variables that have been obtained through a PCA transformation. Due to confidentiality concerns, the original features and background information about the data are not provided. The principal components obtained through PCA are represented by features V1 through V28, while the features Time and Amount have not been transformed with PCA

The Time feature indicates the time elapsed in seconds between each transaction and the first transaction in the dataset, while the Amount feature represents the transaction amount. The Class feature serves as the response variable, taking a value of 1 in cases of fraud and 0 otherwise.

Project Goals:
1. Preprocess the data to handle missing values, outliers, and feature engineering.
2. Exploring the distribution of fraudulant transactions
3. Discover Features correlation
4. Fitting Random forest model
5. Assesing algorithm's quality based on its accuracy (AUC - Area Under the ROC Curve).

Project Structure:
The project is organized into the following directories and files:
- credit_card_fraud_detection/ (root directory)
  - data/ (contains the original dataset)
    - creditcard.csv (import original dataset)
    - data_preprocessing  (preprocessing the data - data wrangling)
    - Performing statistical analysis and visualization to assess data's distribution
    - Assessing important Features' correlation through visualization 
    - Fitting trainning data into Random Forest model and ranking variables' importance
    - Testing model's accuracy by confusion matrix and ROC-AUC score
