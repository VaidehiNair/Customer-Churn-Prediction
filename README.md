# Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

A machine learning project that predicts whether a telecom customer will churn (leave the service) based on customer demographics and usage behavior.

---

## 🚀 Project Overview

Customer churn is a major problem in subscription-based businesses. This project builds a classification model to predict churn using historical customer data.

The workflow includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding
- Handling class imbalance using SMOTE
- Model training and comparison
- Hyperparameter tuning
- Final prediction pipeline

---

## 📂 Dataset

- Source: Telco Customer Churn Dataset (Kaggle)
- Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Features:
- Customer demographics (gender, senior citizen, partner, dependents)
- Account information (contract type, payment method)
- Services (internet, phone, streaming)
- Billing information (monthly charges, total charges)

Target:
- `Churn` → Whether the customer left the service (Yes/No)

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- Imbalanced-learn (SMOTE)

---

## 📊 Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Encoding categorical variables
5. Handling missing values
6. Handling class imbalance (SMOTE)
7. Model training:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
   - LightGBM
8. Model evaluation using accuracy, confusion matrix, classification report
9. Hyperparameter tuning using RandomizedSearchCV
10. Final model selection

---

## 🧠 Best Model

- **Random Forest Classifier**
- Tuned using RandomizedSearchCV
- Evaluated using F1-score and accuracy

---

## 📦 How to Run the Project

### 1. Clone repository
```bash
git clone https://github.com/VaidehiNair/customer-churn-prediction.git