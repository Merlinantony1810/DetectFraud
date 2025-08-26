
# Credit Card Fraud Detection: Defeating Fraud with Machine Learning

A comprehensive machine learning solution for real-time credit card fraud detection that achieves high precision with minimal customer friction.

## Project Overview

Financial fraud detection requires balancing two critical objectives: catching fraudulent transactions while maintaining customer trust. This project analyzes real-world credit card transaction data to build an intelligent fraud detection system that minimizes both false positives and false negatives.

---

## Key Results

- **Precision:** 96% — When flagged as fraud, the model is correct 96% of the time.  
- **Recall:** 76% — Detects 3 out of 4 fraud attempts.  
- **ROC-AUC:** 0.97 — Near-perfect discrimination between fraud and legitimate transactions.  
- **False Positives:** Only 3 per 57,000 transactions — Minimal customer friction.

---

## Dataset

**Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

**Characteristics:**
- Total Transactions: 284,807 (over 2 days)  
- Fraudulent Transactions: 492 (0.172% fraud rate)  
- Features: V1–V28 (PCA-transformed anonymized features)  
- Additional Features:
  - **Time:** Transaction timestamp  
  - **Amount:** Transaction amount  
  - **Class:** Target variable (0 = legitimate, 1 = fraud)

---
