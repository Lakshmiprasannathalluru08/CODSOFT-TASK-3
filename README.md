# CODSOFT-TASK-3
### CUSTOMER CHURN PREDICTION

This project aims to predict customer churn — whether a customer will leave a service or not — using machine learning techniques. The dataset contains customer behavior, service usage, and contract details. The goal is to build a predictive model to help businesses take preventive actions to retain customers.

### About the Dataset

This dataset contains information about bank customers and whether they have churned (i.e., left the bank) or not. The data is sourced from a U.S. bank and includes various customer attributes like credit score, age, balance, tenure, etc.

###  Dataset Features:

RowNumber – Index of the row in the dataset

CustomerID – Unique ID assigned to each customer

Surname – Last name of the customer

CreditScore – Customer's credit score

Geography – Country (e.g., France, Germany, Spain)

Gender – Male or Female

Age – Age of the customer

Tenure – Number of years with the bank

Balance – Account balance

NumOfProducts – Number of bank products the customer uses

HasCrCard – Whether the customer has a credit card (1 = Yes, 0 = No)

IsActiveMember – Whether the customer is active (1 = Active, 0 = Inactive)

EstimatedSalary – Customer’s estimated salary

Exited – Target variable (1 = Customer churned, 0 = Customer stayed)

###  Target:

The goal is to predict the Exited column — whether a customer will leave the bank (churn) or stay.

### Usage

1.Predicts whether a customer will leave the bank (churn) based on their details.

2.Helps banks and businesses identify at-risk customers and take action to retain them.

3.Useful for learning and applying machine learning techniques like classification and feature engineering.

### Model Training

Three models are used:

1. Logistic Regression

2. Random Forest

3. Gradient Boosting

Each model was evaluated on four metrics:

Accuracy

Precision (Macro Average)

Recall (Macro Average)

F1-Score (Macro Average)

### Accuracy

Logistic Regression :0.811

Random Forest:0.866

Gradient Boosting:0.8675

**BEST MODEL OF CUSTOMER CHURN PREDICTION:GRADIENT BOOSTING**

### Contributors

Thalluru Lakshmi Prasanna

### Future Scope

1.Improve prediction accuracy using advanced models like XGBoost, LightGBM, or deep learning.

2.Develop a real-time churn prediction system that alerts businesses instantly about high-risk customers.

3.Include customer feedback or transaction history for more personalized churn prediction.

4.Deploy the model as a web or mobile application for use by banks and customer support teams.

