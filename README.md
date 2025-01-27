## Customer Analytics and Lookalike Model Project

## Overview
This project is focused on analyzing customer, product, and transaction data to derive actionable insights and build a recommendation system. The project is divided into three tasks:

1.Exploratory Data Analysis (EDA) and Business Insights
2.Lookalike Model for Customer Recommendations
3.Prediction of Transaction Trends

## Task 1: Exploratory Data Analysis (EDA) and Business Insights
# Objective
Perform an in-depth analysis of the provided datasets to identify trends, patterns, and actionable business insights.

# Datasets
Customers.csv: Contains customer details such as CustomerID, Name, Region, and more.
Products.csv: Contains product information, including ProductID, Category, and Price.
Transactions.csv: Contains transaction data like TransactionID, CustomerID, ProductID, Date, and Amount.

## Task 2: Lookalike Model
# Objective
Build a model that recommends the top 3 similar customers for a given user based on their profile and transaction history.

# Approach
Feature Engineering:

Combined customer and product information to create a feature matrix for similarity analysis.
Similarity Calculation:

Used cosine similarity to measure the closeness between customers.
Recommendation:

Generated a list of the top 3 similar customers for each user, along with similarity scores.
Output:

Created a Lookalike.csv file that maps customer IDs (C0001 to C0020) to their top 3 lookalikes and similarity scores.

## Task 3: Prediction of Transaction Trends
# Objective
Build a machine learning model to predict future transaction trends based on historical data.

# Approach
Data Preparation:

Aggregated transaction data by time periods (e.g., monthly).
Created features like total transactions, average transaction amount, and customer activity.

