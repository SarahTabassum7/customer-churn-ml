# Customer Churn Prediction (Logistic Regression)

This project builds a **customer churn prediction model** using the **Telco Customer Churn dataset**.  
The goal is to identify customers most likely to churn and highlight the key business drivers behind churn.

---

## Project Objective
- Predict whether a customer will **churn (Yes/No)** using customer service and billing features  
- Apply **Logistic Regression** for interpretability
- Evaluate performance using **classification metrics and threshold tuning**
- Extract top churn drivers using model coefficients

---

## Dataset
- **Dataset:** Telco Customer Churn (IBM sample dataset)
- Rows: ~7,000 customers  
- Target variable: `Churn`

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Key ML Concepts Demonstrated
- Data cleaning and preprocessing
- Converting categorical features using **one-hot encoding**
- Train-test split with **stratification**
- Handling class imbalance using `class_weight='balanced'`
- Model evaluation:
  - Confusion Matrix
  - Precision, Recall, F1-score
  - ROC Curve and ROC-AUC
  - Precision-Recall Curve
- **Threshold tuning** to improve F1-score

---

## Results Summary
- ROC-AUC Score: **0.836**
- Best Threshold (F1 optimized): **0.65**
- Best F1 Score: **0.623**
- Precision: **0.576**
- Recall: **0.679**

---

## Business Insights
Customers with **longer contracts (1–2 year)** are far less likely to churn, while churn risk increases for customers using **electronic check payment**, **fiber optic internet**, and those with **no phone service or limited support add-ons**. These drivers can help prioritize retention campaigns and targeted service improvements.

---

## Files in this Repository
- [`customer_churn_logistic_regression.ipynb`](./customer_churn_logistic_regression.ipynb) → Full model pipeline + evaluation plots  
- [`Telco-Customer-Churn.csv`](./Telco-Customer-Churn.csv) → Dataset used for training/testing  
- [`README.md`](./README.md) → Project overview  

---

## Author
**Sarah Tabassum**  
Business Analyst | Data Analytics | ML Projects  
