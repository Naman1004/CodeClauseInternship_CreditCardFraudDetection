# CodeClauseInternship_CreditCardFraudDetection
# Problem Statement
The project's chosen problem statement is to use machine learning models to predict fraudulent credit card transactions.
In this project, we have analyzed the customer-level data that has been collected by the WorldLine and the Machine Learning Group.
The dataset has been extracted from Kaggle.
492 of the 2,84,807 transactions in the dataset—which was obtained from the Kaggle website—are fake. The severely unbalanced dataset must be addressed before developing a model.

# Recognizing and Characterising Fraud
Any dishonest act or conduct to collect information without the account holder's lawful consent for financial gain is considered credit card fraud. 
The most popular fraud tactic is "skimming," which involves copying the data on a credit card's magnetic strip. 
In addition to this, the additional methods are:
Manipulation/Falsification of authentic cards,
Generation of Counterfeit Cards,
Stolen/lost credit cards,
Dishonest telemarketing.

# Data Dictionary
The data collection consists of credit card purchases made by cardholders in Europe during two days in September 2013. 
There were 492 fraudulent transactions out of 2,84,807 in total. 
The positive class (frauds) accounts for 0.172% of all transactions in this severely skewed data set. 
To ensure secrecy, Principal Component Analysis (PCA) has also been used to modify the data set. 
All features (V1, V2, V3, up to V28) other than "time" and "amount" are the principal components that were found using PCA. 
The seconds that pass between the initial transaction in the data set and the subsequent transactions are contained in the feature called "time." 
The transaction amount is the feature 'amount'. 
The attribute 'class' denotes class labelling, and its default value is 1.
