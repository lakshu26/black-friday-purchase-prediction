# Black Friday Customer Purchase Analysis & Prediction

A machine learning project analyzing customer purchasing patterns from the Black Friday sales dataset and predicting purchase amounts using regression models.

## 📌 Project Overview

This project explores customer purchase behavior during Black Friday sales and builds machine learning models to predict the purchase amount for a transaction.

The project covers:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Customer and product analysis
- Feature preprocessing
- Regression modeling
- Model evaluation
- Actual vs predicted analysis
- Residual analysis

## 📊 Dataset

The dataset contains **550,068 transactions** and **12 columns**.

### Features

| Feature | Description |
|---|---|
| User_ID | Unique customer identifier |
| Product_ID | Unique product identifier |
| Gender | Customer gender |
| Age | Customer age group |
| Occupation | Occupation category |
| City_Category | City category |
| Stay_In_Current_City_Years | Years spent in current city |
| Marital_Status | Marital status |
| Product_Category_1 | Primary product category |
| Product_Category_2 | Secondary product category |
| Product_Category_3 | Tertiary product category |
| Purchase | Purchase amount (target) |

## 🔎 Exploratory Data Analysis

The dataset was analyzed from multiple perspectives, including:

- Distribution of purchase amounts
- Purchase behavior by gender
- Purchase behavior across age groups
- Purchase behavior across city categories
- Product category analysis
- Customer-level transaction and spending analysis
- Correlation analysis

### Key observations

- The **26–35 age group** has the highest number of transactions and the highest total purchase amount.
- The **51–55 age group** has the highest average purchase amount among the age groups.
- **City B** has the highest number of transactions and total purchase amount.
- **City C** has the highest average purchase amount.
- Product Category 1 has the highest total purchase amount.
- Product Category 10 has the highest average purchase amount.

## 🤖 Machine Learning

The target variable is:

```text
Purchase
