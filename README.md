# Customer Churn Prediction
# Introduction
Customer churn is a critical challenge for businesses, especially in subscription-based industries like telecom. This project aims to predict customer churn based on various demographic, account, and service-related factors.

The model helps businesses take proactive measures to retain customers by identifying those likely to leave.

# Dataset
The dataset used for this project is Telco Customer Churn. It includes customer demographic details, service usage, and payment-related information.

# Features Considered
Demographics: Gender, Senior Citizen, Partner, Dependents
Service Details: Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies
Contract Details: Contract Type, Paperless Billing, Payment Method
Billing & Tenure: Monthly Charges, Total Charges, Tenure Group
# Model Used
The project uses a Gradient Boosting Classifier for churn prediction, trained on the Telco Customer Churn dataset.

# Implementation
Model Training: The model is trained using sklearn's Gradient Boosting Classifier.
Preprocessing: Categorical variables are encoded into numerical values for model compatibility.
Deployment: The trained model is deployed using Streamlit, making it easy to interact with.
