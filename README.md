# Credit-card-Fraud-Detection-2023
Dataset:
This dataset contains credit card transactions made by European cardholders in the year 2023. It comprises over 550,000 records, and the data has been anonymized to protect the cardholders' identities. The primary objective of this dataset is to facilitate the development of fraud detection algorithms and models to identify potentially fraudulent transactions.

Key Features:
id: Unique identifier for each transaction
V1-V28: Anonymized features representing various transaction attributes (e.g., time, location, etc.)
Amount: The transaction amount
Class: Binary label indicating whether the transaction is fraudulent (1) or not (0),


Potential Use Cases:
Credit Card Fraud Detection: Build machine learning models to detect and prevent credit card fraud by identifying suspicious transactions based on the provided features.
Merchant Category Analysis: Examine how different merchant categories are associated with fraud.
Transaction Type Analysis: Analyze whether certain types of transactions are more prone to fraud than others



Consclusion
We have done Exploratory Data analysis for different features.
We prepared our Data and build different ML Models.
We have seen how different models are performing w.r.t Accuracy,Precision,Recall and F1 Scores.
Random Forest with default parameters is giving 100% accuracy on training and test dataset.
We have tried using Boosting technique XGBoost and we have a model with 96% accuracy with improvement in False Poitive and False Negative.
We have further tried doing hyper parameter tuning for XGBoost.We can with different parameters and see if further we can reduce the FP and FN.


