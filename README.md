# payment-Fraud-Detection-project
* To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments.
* For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud.

### Dataset:
* It has 9 features
* Target variable is binary categorical (fraud/not)

### Data preprocessing:
* EDA, Encoding, Data cleaning

### Modelling:
* using Decision tree classifier
* gives an accuracy of 99%

### Problem with this dataset:
* This is an imbalanced dataset (ie. fraud payments < 1%)
* hence, normal ML models doesnot work well.

### Solution:
* We need to balance this dataset first:
    * using Undersampling techniques:
        * Tomek links
        * Cluster centroids
    * or using oversampling techniques:
        * SMOTE (Synthetic Minority Oversampling Technique)
* And then apply ML algorithm on the balanced dataset
