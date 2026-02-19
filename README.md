# Customer Churn Prediction — ML & Causal AI Analysis

---

## Overview

Customer churn is a critical challenge for subscription-based businesses. This project predicts which customers will churn, why they churn, and how much revenue is at risk — using Machine Learning and Causal AI.

---

## Dataset

| Property | Detail |
|----------|--------|
| Records | 10,000 customers |
| Target | churn (0 = No, 1 = Yes) |
| Domain | Subscription / SaaS / Telecom |
| Source | Synthetic (business-logic driven) |
| Features | Demographics, usage, billing, support, engagement |

---

## Models & Results

| Model | Accuracy | AUC-ROC |
|-------|----------|---------|
| Logistic Regression | 89.60% | 0.7251 |
| Decision Tree | 81.25% | 0.5589 |
| Random Forest | 89.70% | 0.7881 |
| **Gradient Boosting** ✅ | **89.30%** | **0.8032** |
| XGBoost | 88.65% | 0.7573 |

> Best Model: **Gradient Boosting** — AUC-ROC: 0.8032

---

## Key Outputs

| Risk Level | Customers | Action |
|------------|-----------|--------|
| 🔴 High Risk | Predicted | Immediate retention call |
| 🟡 Medium Risk | Predicted | Email campaign |
| 🟢 Low Risk | Predicted | Upsell opportunity |

---

## Technologies

| Category | Tools |
|----------|-------|
| Data | Python, Pandas, NumPy |
| ML Models | Scikit-learn, XGBoost |
| Causal ML | DoWhy, EconML |
| Visualization | Matplotlib, Seaborn |

---

## Disclaimer

This dataset is synthetically generated for educational and portfolio purposes only. It does not represent real customer data.

---

## Author

**Shad Ali Shah** — Data Scientist & Economist

