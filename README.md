# Multiple Linear Regression – Multi-Channel Marketing Analysis

## Project Overview
This repository contains a multivariate data science project demonstrating how to use Multiple Linear Regression to analyze complex marketing datasets. Using Python and `statsmodels`, the project evaluates the simultaneous impact of TV, Radio, and Social Media advertising on total Sales. 

The analysis successfully handles categorical data encoding, checks for multicollinearity using Variance Inflation Factors (VIF), validates advanced OLS assumptions via residual diagnostics, and leverages Adjusted R-squared and p-values to formulate an evidence-based marketing budget recommendation.

## Dataset Description
The dataset (`c107fa55-45be-4f9c-8f61-088e88d1fb0c.csv`) contains multi-channel marketing data. 
* **TV:** Categorical advertising tier (Low, Medium, High).
* **Radio:** Continuous budget spend.
* **Social Media:** Continuous budget spend.
* **Influencer:** Categorical influencer size (Macro, Mega, Micro, Nano).
* **Sales:** The continuous target variable representing total revenue.

## Environment Setup
Ensure you have Python installed, then install the required dependencies using your terminal:
`pip install pandas numpy seaborn statsmodels matplotlib scipy`

## Execution
Open `multiple regression.pdf`
