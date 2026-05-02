# Credit Card Fraud Detection

A machine learning project for identifying fraudulent credit card transactions using behavioral and transactional patterns.

---

## Overview

This project builds a fraud detection pipeline from scratch — starting with raw transaction data, moving through exploratory analysis, and ending with a trained Random Forest classifier evaluated on real performance metrics.

The goal is practical: flag suspicious transactions before they cause financial damage.

---

## Dataset

File: cleaned_creditcfraud.csv
10,001 transactions × 10 columns

Column | Description
transaction_id | Unique ID per transaction
amount | Transaction value in USD
transaction_hour | Hour of day (0–23)
merchant_category | Merchant type
foreign_transaction | 1 if international
location_mismatch | 1 if billing/shipping differ
device_trust_score | Device security score (0–100)
velocity_last_24h | Number of transactions in past 24h
cardholder_age | Age of the cardholder
is_fraud | Target — 0 = legit, 1 = fraud

---

## What the Notebook Covers

1. Data exploration and sanity checks
2. Class imbalance analysis
3. Correlation between features
4. Encoding categorical variables
5. Training a Random Forest model
6. Evaluating with confusion matrix, precision/recall, and ROC-AUC
7. Feature importance breakdown

---

## Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

---

## Running It

1. Clone the repo
2. Place cleaned_creditcfraud.csv in the root directory
3. Open fraud.ipynb in Jupyter
4. Run all cells top to bottom

---

## Notes

This is an educational project. Production fraud systems require additional layers — real-time scoring, regulatory compliance, model monitoring, and more. This is a starting point, not a finished product.
