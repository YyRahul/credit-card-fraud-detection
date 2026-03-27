# Credit Card Fraud Detection Analysis

## 📊 Project Overview

This project implements a comprehensive credit card fraud detection system using machine learning techniques. The analysis includes data exploration, feature engineering, model training, and performance evaluation to identify fraudulent transactions.

## 🎯 Objective

Detect fraudulent credit card transactions based on transaction patterns and customer behavior to prevent financial losses and enhance security.

## 📁 Dataset

**Source:** `cleaned_creditcfraud.csv`
- **Rows:** 10,001 transactions
- **Columns:** 10 features
- **Target:** Binary classification (fraud/not fraud)

### Features:
- `transaction_id` - Unique transaction identifier
- `amount` - Transaction amount ($)
- `transaction_hour` - Hour of transaction (0-23)
- `merchant_category` - Type of merchant
- `foreign_transaction` - International transaction flag (0/1)
- `location_mismatch` - Billing/shipping location mismatch (0/1)
- `device_trust_score` - Device security score (0-100)
- `velocity_last_24h` - Transaction frequency in last 24 hours
- `cardholder_age` - Age of cardholder
- `is_fraud` - Target variable (0=legitimate, 1=fraudulent)

## 🛠️ Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization
- **Scikit-learn** - Machine learning algorithms

## 📈 Analysis Components

1. **Data Exploration** - Understanding dataset structure and characteristics
2. **Statistical Analysis** - Summary statistics and distribution analysis
3. **Fraud Distribution** - Class imbalance analysis and visualization
4. **Correlation Analysis** - Feature relationships and multicollinearity
5. **Feature Engineering** - Categorical encoding and preprocessing
6. **Model Training** - Random Forest classifier implementation
7. **Model Evaluation** - Performance metrics, confusion matrix, ROC-AUC
8. **Feature Importance** - Understanding model decision factors

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Analysis
1. Clone this repository
2. Ensure `cleaned_creditcfraud.csv` is in the same directory
3. Open `fraud.ipynb` in Jupyter Notebook
4. Run all cells sequentially

## 📊 Key Findings

- **Fraud Rate:** ~X% of transactions are fraudulent
- **Top Predictors:** [Based on feature importance analysis]
- **Model Performance:** [ROC-AUC, Precision, Recall metrics]

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or additional analysis techniques.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or suggestions, please open an issue in this repository.

---

**Note:** This is an educational project demonstrating fraud detection techniques. For production use, additional security measures and regulatory compliance would be required.