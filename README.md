Customer Churn Prediction
📌 Project Overview

Customer churn is a critical business problem where organizations aim to identify customers who are likely to discontinue a service. This project focuses on performing end-to-end exploratory data analysis (EDA) and data cleaning on a real-world telecom dataset to uncover churn-driving patterns and prepare the data for predictive modeling.

🎯 Objectives

Analyze customer behavior using historical data

Identify key factors associated with customer churn

Clean and preprocess data for machine learning readiness

Extract actionable business insights through visualization

🧠 Approach

Data Loading & Inspection

Loaded structured telecom customer data

Reviewed dataset dimensions, schema, and data types

Data Cleaning & Preprocessing

Identified data type inconsistencies in numeric fields

Detected hidden missing values caused by string-based numeric columns

Applied domain-driven imputation logic to resolve missing values

Exploratory Data Analysis (EDA)

Analyzed churn distribution

Studied relationships between churn and key features such as tenure and monthly charges

Visualized insights using boxplots and count plots

🔍 Key Insights

Churn is imbalanced, with a majority of customers not churning

Low-tenure customers are significantly more likely to churn

Customers with higher monthly charges show higher churn probability

New customers (tenure = 0) logically have zero total charges, which required special handling

🛠️ Tech Stack

Programming: Python

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook (Anaconda)
