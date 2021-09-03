# Credit Card Fraud Detection

## 1. Problem Statement 
Detecting Fraudulent Credit Card transactions with the help of the given data.

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

***

## 2. The Dataset
The data can be taken from the [here](https://www.kaggle.com/mlg-ulb/creditcardfraud).

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

***

## 3. Model Building

### 3.1 Scikit-Learn 
A Logistic Regression model with anomaly weight of 10 given to the minority class was able to provide the following metrics:
- ***Accuracy: 0.9985979670522257***
- ***AUC: 0.9749591657243373***
  
### 3.2 PySpark
Logistic Regression implementation from PySpark was able to give us the following results:
- ***Pyspark AUC Score: 98.271%***
- ***Accuracy: 99.909%***
  
***

***Note: All the Model runs have been logged using MLflow and can be found in the `mlruns` directory***
