
Thera Bank Credit Card Churn Analysis
Project Overview
Thera Bank recently experienced a steep decline in credit card users, impacting its revenue streams from various fees (annual, transaction, late payment, etc.). This project aims to analyze customer data to identify individuals likely to leave the bank's credit card services and understand the key factors behind their decision. The ultimate goal is to help Thera Bank enhance its credit card offerings, reduce churn, and retain customers.

Objectives
Explore and visualize customer data to identify patterns and trends in credit card attrition.

Build and compare classification models to predict customer churn.

Optimize the chosen model using appropriate techniques to maximize performance.

Generate actionable insights and recommendations based on model outcomes to help Thera Bank retain credit card customers.

Dataset Description
The dataset includes customer profile and activity information:

Variable	Description
CLIENTNUM	Unique identifier for the customer
Attrition_Flag	Account status: "Attrited Customer" or "Existing Customer"
Customer_Age	Customer's age in years
Gender	Male/Female
Dependent_count	Number of dependents
Education_Level	Educational qualification
Marital_Status	Marital status
Income_Category	Annual income category
Card_Category	Type of credit card held
Months_on_book	Relationship duration with the bank
Total_Relationship_Count	Total products held
Months_Inactive_12_mon	Months inactive in last 12 months
Contacts_Count_12_mon	Bank-customer contacts in last 12 months
Credit_Limit	Credit card limit
Total_Revolving_Bal	Outstanding revolving balance
Avg_Open_To_Buy	Average open-to-buy amount (last 12 months)
Total_Trans_Amt	Total transaction amount (last 12 months)
Total_Trans_Ct	Total transaction count (last 12 months)
Total_Ct_Chng_Q4_Q1	Ratio of transaction count (Q4/Q1)
Total_Amt_Chng_Q4_Q1	Ratio of transaction amount (Q4/Q1)
Avg_Utilization_Ratio	Proportion of credit used


Workflow
Data Exploration & Visualization: Understand churn patterns through descriptive statistics and visualizations.

Feature Engineering: Prepare and select the most informative features for modeling.

Model Building: Train various classification models (e.g., Logistic Regression, Random Forest, XGBoost).

Evaluation: Compare models using metrics like accuracy, precision, recall, F1-score, ROC-AUC.

Optimization: Tune model parameters for best performance.

Insights & Recommendations: Present findings to stakeholders to inform customer retention strategies.

Getting Started
