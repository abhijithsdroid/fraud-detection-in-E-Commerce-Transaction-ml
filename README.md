# 🚀 Fraud Detection in Financial Transactions (PaySim)

## 📌 Overview

This project focuses on detecting fraudulent transactions using machine learning techniques on the PaySim dataset.

* 📊 Dataset: 6.3M+ transactions
* ⚠️ Fraud Rate: 0.13%
* 🏆 Best Model: XGBoost (ROC-AUC: 0.98)

---

## 📂 Files in this Repository

* `fraud-detection.ipynb` → Complete analysis (EDA + ML)
* `Fraud_Detection_Project_Report.pdf` → Detailed report

---

## 📊 Key Insights

* Fraud occurs only in:

  * TRANSFER
  * CASH_OUT
* Fraud peaks between **3 AM – 6 AM**
* High-value transactions are high risk
* Severe class imbalance present

---

## ⚙️ Techniques Used

* Exploratory Data Analysis (EDA)
* Feature Engineering
* SMOTE (class imbalance handling)
* Machine Learning Models:

  * Logistic Regression
  * Random Forest
  * XGBoost
  * LightGBM

---

## 📈 Results

* ROC-AUC: **0.98**
* PR-AUC: **0.62**
* Precision: ~47%
* Recall: ~64%

---

## 💼 Business Impact

* Improves fraud detection accuracy
* Reduces false alerts
* Helps financial institutions prevent losses

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 👤 Author

**Abhijith S**

