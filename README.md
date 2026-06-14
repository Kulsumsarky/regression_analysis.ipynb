# Marketing ROI Analysis - Simple Linear Regression

## Project Overview
This project analyzes a marketing dataset using Python and statsmodels 
to build a Simple Linear Regression model to identify the best 
marketing channel for ROI.

## Key Findings
- TV advertising has the strongest correlation with Sales (0.9995)
- Every $1 increase in TV budget generates $3.56 in Sales
- R-squared of 0.999 means TV explains 99.9% of Sales variation

## Environment Setup
Run the following to install required libraries:
pip install pandas numpy matplotlib seaborn statsmodels

## Files
- regression_analysis.ipynb - Main analysis notebook
- marketing_and_sales_data_evaluate_lr.csv - Dataset

## Regression Equation
Sales = -0.13 + 3.56 * TV

## Conclusion
Allocate majority of marketing budget to TV advertising for maximum ROI.
