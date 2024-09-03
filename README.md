# Predicting Fraudulent Transactions

This project focuses on detecting fraudulent transactions using machine learning techniques. The notebook contains exploratory data analysis (EDA) and model development steps to identify potentially fraudulent activities in a dataset.


## Overview

The objective of this project is to develop a model that can accurately predict fraudulent transactions based on various features provided in the dataset. The project involves data preprocessing, EDA, model training, and evaluation.

## Dataset

The dataset used in this project is publicly available on Kaggle:

[Fraudulent Transactions Dataset](https://www.kaggle.com/datasets/venkateshblks/fraudulent-transactions)

The dataset contains the following columns:

- `step`: Time step of the transaction
- `type`: Type of transaction
- `amount`: Amount of the transaction
- `nameOrig`: Identifier of the origin account
- `oldbalanceOrg`: Initial balance before the transaction
- `newbalanceOrig`: New balance after the transaction
- `nameDest`: Identifier of the destination account
- `oldbalanceDest`: Initial balance of the destination account before the transaction
- `newbalanceDest`: New balance of the destination account after the transaction
- `isFraud`: Indicator of whether the transaction is fraudulent
- `isFlaggedFraud`: Indicator of whether the transaction was flagged as fraudulent by the system

## Results

The model's performance is evaluated using various metrics, including accuracy, precision, recall, F1-score and ROC-AUC score. The results are visualized and discussed in the notebook.

![image](https://github.com/user-attachments/assets/6a347065-b136-4e5b-84ad-56673189a8d1)

Based on the metrics above, we can say that the "best xgb classifier" is the best model compared to all the others

