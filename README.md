# Telecom Customer Churn Analysis
## Project Overview

This project analyzes customer churn in a telecommunications company and builds a logistic regression model to identify the strongest drivers of customer churn. The goal is to combine exploratory data analysis (EDA) with an interpretable model to understand which customer characteristics are most associated with churn and provide actionable retention insights.

---

## Business Problem

Customer churn is a major driver of revenue loss for subscription-based businesses. Retaining existing customers is typically less expensive than acquiring new ones, making early identification of at-risk customers critical. This analysis focuses on identifying key churn drivers and building a predictive model that supports retention strategies.

---

## Dataset

- Source: Kaggle — Telco Customer Churn dataset  
- Observations: ~7,000 customers  
- Features: demographics, tenure, contract type, internet service, billing, payment method, add-on services, and churn status  

---

## Key Findings

- Month-to-month contracts were the strongest driver of churn.  
- Churn is heavily concentrated in the first 6–12 months of tenure.  
- Fiber optic customers show higher churn than DSL customers.  
- Higher monthly charges are associated with increased churn risk.  
- Add-on services (Online Security, Tech Support, Backup, Device Protection) reduce churn likelihood.  
- Electronic check users are more likely to churn than users of automated payment methods.  
- Demographic variables such as gender have minimal predictive power.  

---

## Model Performance (Class-Weighted Logistic Regression)

| Metric | Value |
|------|------|
| Accuracy | 72.6% |
| Recall (Churn) | 79% |
| Precision (Churn) | 49% |
| F1-score (Churn) | 0.61 |
| ROC-AUC | 0.834 |

---

## Business Recommendations

- Focus retention efforts on month-to-month customers.  
- Target early-tenure customers (first year of service).  
- Improve experience or pricing strategy for fiber optic users.  
- Promote adoption of add-on services that reduce churn risk.  
- Encourage transition away from electronic check payments.  

---

## Notes

- Logistic regression was chosen for interpretability and business clarity.  
- The model is intended for insight generation, not just prediction accuracy.  
- Results should be interpreted as statistical associations, not causation.
