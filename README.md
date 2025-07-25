# Projectsiitm

1. Credit card fraud detection 
## ABSTRACT

Credit card fraud poses a major financial threat, resulting in billions of dollars in losses annually. Leveraging machine learning offers a promising approach to identifying suspicious patterns and detecting fraudulent transactions. Credit card fraud encompasses both the physical theft of cards and the compromise of sensitive card information. Various machine learning algorithms can be employed for fraud detection. This project aims to develop a machine learning model capable of identifying credit card fraud. The model will be trained using historical transaction data and evaluated on a separate dataset of previously unseen transactions.

## PROJECT GOALS

The primary objective of this project is to accurately detect fraudulent credit card transactions, thereby preventing customers from being wrongly charged for purchases they did not make. Multiple machine learning techniques will be applied to identify suspicious activities within transaction data. The performance of each technique will be analyzed and compared to determine the most effective model for fraud detection. The results will be presented using relevant graphs and metrics. Additionally, the project will review existing literature and explore various methodologies previously employed to detect fraud in similar datasets.

DATASET : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset was retrieved from an open-source website, Kaggle.com. The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Algorithm

- K-Nearest Neighbor (KNN)
- Logistic Regression 
- Support Vector Machine (SVM)
- Decision Tree

## Conclusion
In conclusion, the main objective of this project was to find the most suited model for creditcard fraud detection in terms of the machine learning techniques chosen for the project. It was met by building the four models and finding the accuracies of them all which increased the customer’s satisfaction as it will provide themwith a better experience and feeling secure.

2. EV Battery life predictor

This project predicts the Remaining Useful Life (RUL) of lithium-ion batteries using machine learning techniques. It uses real-world battery cycling data and interprets the model's decisions using SHAP explainability.

Dataset Summary
- Source: Hawaii Natural Energy Institute
- Battery Type: 14 NMC-LCO 18650 cells (nominal capacity: 2.8 Ah)
- Testing Conditions: 1000+ charge-discharge cycles at 25°C

Linear Regression
- MAE: 4.64 seconds
- RMSE: 7.39 seconds
- R² Score: 0.99947

Random Forest Regressor 
- MAE: 2.08 seconds
- RMSE: 3.75 seconds
- R² Score: 0.99986

The Random Forest model showed significantly lower error values and a better fit to the data, making it the optimal choice for RUL prediction.
