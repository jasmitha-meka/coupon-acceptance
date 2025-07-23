# Will a customer accept the coupon?

A data analysis project to explore factors influencing customer acceptance of driving-related coupons.

## Overview

This repository includes a dataset sourced from the UCI Machine Learning Repository and collected via a survey on Amazon Mechanical Turk. The survey presents various driving scenarios—such as destination, time of day, weather, and passenger type—and asks respondents whether they would accept a coupon if they were the driver.

The goal of this project is to explore how different features influence coupon acceptance using visualizations, statistical summaries, and probability distributions.

See full analysis in the Jupyter Notebook ( link).

## Observations:
### 1. Bar Coupons
- Bar coupons rank **4th out of 5** in terms of issuance volume among all coupon types.
- Only **41%** of customers who were offered a bar coupon accepted it.
- Customers who go to bars more than 3 times a month are twice as likely to accept a bar coupon compared to those who go less frequently.
- Customers over the age of 25 who go to bars more than once a month are twice as likely to accept a bar coupon compared to other groups.
- Customers who go to bars more than once a month, travel with passengers other than kids, and have occupations outside of farming, fishing, or forestry accept more bar coupons than all others.
- Customer who go to bars more than once a month, travel with passengers other than kids and were not widowed OR who go to bars more than once a month and are under the age of 30 OR who go to cheap restaurants more than 4 times a month and income is less than 50K accept more bar coupons than all others.

### 2. Coffee House Coupons:
- Coffee house coupons rank **1st out of 5** among the different categories of coupons issued.
- Only **49.9%** of customers accepted a coffee house coupon when offered.
- Customers who go to coffee house more than once a month and are either students or unemployed show 70% coupon acceptance rates than all others.


## Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook


