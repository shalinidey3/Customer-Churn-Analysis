# Customer Churn Analysis

## Project Objective

This project analyzes customer churn behavior using a large customer dataset.

The analysis focuses on:
- Overall customer churn rate
- Churn by subscription type
- Churn by support calls
- Churn by customer tenure
- Churn by payment delay
- Churn by contract length

The goal is to identify patterns in customer churn and present the findings through data analysis and visualizations.

## Dataset

The project uses the Customer Churn Dataset from Kaggle.

Training data: 440,833 rows  
Testing data: 64,374 rows

After removing missing values, the cleaned training dataset contains 440,832 rows.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

## Analysis Performed

### 1. Overall Churn Rate

The overall churn rate in the cleaned training dataset is **56.71%**.

### 2. Churn by Subscription Type

- Basic: 58.18%
- Premium: 55.94%
- Standard: 56.07%

### 3. Churn by Support Calls

Higher churn rates were observed among customers with more support calls. Customers with 5 support calls had a churn rate of **94.71%** in this dataset.

### 4. Churn by Tenure

Churn rates were analyzed across different customer tenure periods using a line chart.

### 5. Churn by Payment Delay

Payment delay was analyzed to understand how observed churn rates vary across different payment-delay values.

### 6. Churn by Contract Length

- Annual: 46.08%
- Monthly: 100.00%
- Quarterly: 46.03%

## Key Findings

- The overall churn rate is 56.71%.
- Subscription types show differences in observed churn rates.
- Higher numbers of support calls are associated with higher observed churn rates in this dataset.
- Payment delay values from 21 to 30 days show a 100% churn rate in the dataset.
- Monthly contracts show a 100% churn rate in this dataset.

## Project Notebook

The complete analysis is available in:

`Customer_Churn_Analysis.ipynb`
