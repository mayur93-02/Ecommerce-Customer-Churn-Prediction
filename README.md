# E-Commerce Customer Churn Prediction

## Customer Churn Prediction

![Customer Churn Prediction](images/churn_prediction.png)
Project Overview
Customer churn is one of the most critical challenges for e-commerce businesses. This project focuses on predicting whether a customer is likely to churn using machine learning techniques. The objective is to identify high-risk customers and provide actionable business insights to improve customer retention.

Business Problem

Customer acquisition is often more expensive than customer retention. By predicting churn in advance, businesses can take proactive measures such as personalized offers, loyalty programs, and improved customer support to reduce customer attrition.

Dataset Information

The dataset contains customer demographics, purchasing behavior, engagement metrics, satisfaction scores, complaints, cashback information, and order history.

Target Variable:

Churn (0 = Not Churned, 1 = Churned)
Project Workflow
1. Data Cleaning
Handled missing values
Corrected data types
Treated inconsistent values
Performed data quality checks
2. Exploratory Data Analysis (EDA)
Univariate Analysis
Bivariate Analysis
Churn Distribution Analysis
Correlation Analysis
Feature Relationship Exploration
3. Feature Engineering
Encoded categorical variables
Prepared features for machine learning models
Selected relevant variables for prediction
4. Model Building

Machine Learning Algorithm:

Random Forest Classifier
5. Model Evaluation

Metrics Used:

Accuracy Score
Precision
Recall
F1 Score
Confusion Matrix
Model Performance
Metric	Score
Accuracy	90.23%
Precision	74%
Recall	64%
F1 Score	68%

Confusion Matrix:


	Predicted No Churn	Predicted Churn
Actual No Churn	897	42
Actual Churn	68	119
Key Factors Influencing Churn

Feature Importance Analysis revealed the following major churn drivers:

Tenure
Complain
CashbackAmount
NumberOfAddress
DaySinceLastOrder
WarehouseToHome
SatisfactionScore
Business Insights
Customers with shorter tenure are more likely to churn.
Customers who have raised complaints show a significantly higher churn probability.
Long periods of inactivity increase churn risk.
Cashback programs may improve customer retention.
Customer satisfaction plays an important role in reducing churn.
Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
Project Outcome

The Random Forest model successfully predicted customer churn with an accuracy of 90.23%. The project provides valuable business insights that can help organizations improve customer retention strategies and reduce churn rates.
