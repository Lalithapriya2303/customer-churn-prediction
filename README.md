# customer-churn-prediction
End-to-end customer churn prediction using Python and machine learning

## Project Overview 
Customer churn refers to customers leaving a company.
This project aims to predict whether a customer is likely to churn based on
their demographics, services used, and billing information.
Understanding churn helps businesses improve customer retention and reduce
revenue loss.

## Objective
- Identify customers who are likely to churn
- Analyze key factors influencing churn
- Provide data-driven business recommendations

## Dataset
Source: IBM Telco Customer Churn Dataset (via Kaggle)
Records: ~7,000 customers
Features include:
- Customer demographics
- Contract type
- Monthly charges
- Services subscribed
- Churn status (Yes / No)

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- GitHub

## Exploratory Data Analysis (EDA)
Analyzed churn distribution among customers
Studied churn behavior based on:
- Contract type
- Tenure
- Monthly charges
Identified that customers on month-to-month contracts have higher churn rates

## Data Cleaning & Preparation
Converted total charges to numeric values
Handled missing values
Encoded categorical variables using one-hot encoding
Split data into training and testing sets

## Model Building
Built a Logistic Regression model as a baseline
Evaluated performance using:
- Precision
- Recall
- F1-score
- ROC-AUC score

## Model Performance
- The model achieved a strong ROC-AUC score
- Demonstrated good ability to distinguish between churned and retained customers

## Business Insights
Customers with:
- Month-to-month contracts
- Higher monthly charges
- Lower tenure are more likely to churn
Targeted retention strategies can be applied to high-risk customers

## Conclusion
This project demonstrates an end-to-end data analytics workflow:
- Data exploration
-Cleaning
- Modeling
- Business interpretation
It provides actionable insights that can help organizations reduce customer churn.

## Author
** Lalitha Priya **



