# Customer Churn Analysis - Fit.ly Tech

## Overview
Customer churn is critical for subscription-based companios. This project analyzes drivers of churn.
The objective was to determine which variables most strongly influence if a customer leaves.

## Tools
Python, Pandas, Seaborn, NumPy, LogisticRegression, StandardScaler

## Dataset
Contains 400+ customer records split amongst three files: 
- user activity
- customer support
- account info

These records contain predictors such as: 
- customer service ticket time, channel, topic, and resolution time
- activities event time and type
- customer information such as id, email, plan, price, churn status
  
## Methods
The analysis included:
- data cleaning and validation
- Exploratory data analysis (EDA)
- correlation analysis
- Identification of outliers and anomalous records

## Results
The strongest relationship discovered was between customer service resolution time and churn
- correlation coefficient: **-0.83**
- Faster issue resolution strongly correlates with higher customer retention.

During analysis, 46 right to be forgotten deltion requests were also identified. 

## Files


## Note
This analysis was originally developed as part of a DataCamp project and was expanded with logistic regression modeling to identify strongest predictors.   
