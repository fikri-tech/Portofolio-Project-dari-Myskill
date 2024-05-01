Title: Credit Card Payment Delay Prediction Model

## Problem Statement
FinanKu is concerned about potential credit card payment delays that could adversely affect their business. Predicting customers who are likely to experience payment delays enables the implementation of proactive strategies to mitigate future risks effectively.

## Objective
Develop a model capable of predicting at least 60% of customers who will experience credit card payment delays with an accuracy and recall rate above 60%.

## Available Variables
From the dataset provided, the following variables are available:

1. **Customer ID**: Unique Customer ID
2. **Branch**: Customer's Registered Branch Location
3. **City**: Customer's Registered City Location
4. **Age**: Customer's Age during Observation Period
5. **Avg. Annual Income/Month**: Customer's Average Annual Income
6. **Balance (Q1-Q4)**: Customer's End-of-Quarter Deposits Balance
7. **Num of Products (Q1-Q4)**: Number of Products Owned by Customer at End of Quarter
8. **HasCrCard (Q1-Q4)**: Status of Customer's Credit Card Ownership at End of Quarter
9. **Active Member (Q1-Q4)**: Customer's Active Membership Status
10. **Unpaid Tagging**: Customer's Payment Delay Status

## Experiment
Review Periods:

1. Customers reviewed over the last one year
2. Customers reviewed over the last six months

Variable Adjustments:

- Balance observed as average during the review horizon & viewed as changes at the end and beginning of the review.
- Product ownership viewed from the average, maximum, and minimum during the review period.
- Customer activity status observed in months.

## Deliverables
- Detailed analysis report on credit card payment delay predictions.
- Python notebook or script for replicating the prediction model.
- Visualizations illustrating key insights and model performance.
- Recommendations for proactive strategies based on prediction outcomes.

This project aims to provide FinanKu with a robust model for identifying potential credit card payment delays, empowering them to take proactive measures to mitigate financial risks effectively.
