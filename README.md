# Statistical Analysis of Megaline Pricing Plans

## Project Overview
Megaline, a telecommunications company, offers two prepaid plans: Surf and Ultimate. The commercial department wants to determine which plan generates higher revenue in order to optimize the advertising budget.

In this project, a statistical analysis is performed using data from 500 Megaline customers to evaluate customer behavior and compare the profitability of both plans.

## Objective
The main goals of this project are to:
- Analyze customer usage behavior for calls, messages, and mobile data.
- Calculate monthly revenue per user based on plan conditions.
- Compare average revenue between the Surf and Ultimate plans.
- Test business hypotheses using statistical methods.

## Dataset
The analysis is based on five datasets:
- `users`: customer information and subscribed plan.
- `calls`: call records and durations.
- `messages`: SMS activity.
- `internet`: internet usage data.
- `plans`: plan details and pricing rules.

The data represents customer activity during the year 2018.

## Data Preparation
- Converted columns to appropriate data types.
- Cleaned and validated datasets.
- Aggregated monthly usage per user.
- Calculated monthly revenue per customer based on plan limits and overage charges.

## Analysis Performed
- Monthly usage analysis for calls, messages, and data by plan.
- Calculation of mean, variance, and standard deviation.
- Visualization of distributions using histograms.
- Comparative analysis of customer behavior across plans.

## Hypothesis Testing
The following hypotheses were tested:
1. The average revenue of users on the Ultimate plan differs from that of users on the Surf plan.
2. The average revenue of users in the New York–New Jersey area differs from that of users in other regions.

Statistical tests were conducted using a defined significance level (alpha), and results were interpreted in a business context.

## Tools Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Business Value
This analysis helps Megaline:
- Identify the most profitable pricing plan.
- Make data-driven decisions for marketing budget allocation.
- Better understand customer usage behavior.
- Support strategic business planning using statistical evidence.

This project demonstrates the application of statistical analysis and hypothesis testing to solve real-world business problems.
