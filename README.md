# Fraud-Detection
Unbalanced Classification for Fraud Detection

Context:
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers 
are not charged for items that they did not purchase.

Content:
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The input dataset contains features such as credit card transaction time, amount, and other hidden features. 
The outcome is class (fraud or not).
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Objective:
Using machine learning, we will predict whether a transaction is fraud or not.

In particular, we need to deal with an imbalanced dataset. To do so, we consider these approaches:
- Collecting more data, if possible
- Changing the performance metrics (precision, recall, f1-score, ...)
- Resampling the data (oversampling, undersampling, SMOTE, ...)
- Changing the MLAs

This dataset is available by Kaggle. I studied the data, performed an exploratory data analysis, used multiple 
resampling methods, and developed various MLAs.
