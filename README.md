# Credit Card Fraud Detection

## Introduction

Fraud that involves cell phones, insurance claims, tax return claims, credit card transactions, government procurement etc. represent significant problems for governments and businesses and specialized analysis techniques for discovering fraud using them are required. These methods exist in the areas of Knowledge Discovery in Databases (KDD), Data Mining, Machine Learning and Statistics. They offer applicable and successful solutions in different areas of electronic fraud crimes.

In general, the primary reason to use data analytics techniques is to tackle fraud since many internal control systems have serious weaknesses. For example, the currently prevailing approach employed by many law enforcement agencies to detect companies involved in potential cases of fraud consists in receiving circumstantial evidence or complaints from whistleblowers. As a result, a large number of fraud cases remain undetected and unprosecuted. In order to effectively test, detect, validate, correct error and monitor control systems against fraudulent activities, businesses entities and organizations rely on specialized data analytics techniques such as data mining, data matching, sounds like function, Regression analysis, Clustering analysis and Gap. Techniques used for fraud detection fall into two primary classes: statistical techniques and artificial intelligence.

## Understanding Fraud

Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card. Apart from this, the other ways are:

1. Manipulation/alteration of genuine cards
2. Creation of counterfeit cards
3. Stolen/lost credit cards
4. Fraudulent telemarketing

## Features

This Kaggle dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, it is not provided the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Feature Information:

Time: This feature is contains the seconds elapsed between each transaction and the first transaction in the dataset.

Amount: This feature is the transaction Amount, can be used for example-dependant cost-senstive learning.

Class: This feature is the target variable and it takes value 1 in case of fraud and 0 otherwise.

## Conclusion:
Random Forest Classifier had and overall better performance than Logistic Regression

**Accuracy score:99.95%**

**Recall score:77.55%**

**Precision score:98.70%**

This model yields a **precision** of **98.7%** and a **recall** of **77.5%**.

This means that **98%** of actual fraud transactions were flagged as fraud.

Random Forest CLassifier performs well.

Thus, Random Forest Classifier model can be used for checking whether a transaction is Legit or Fraud provided the features and other information of transaction is unbias and not manipulated.


