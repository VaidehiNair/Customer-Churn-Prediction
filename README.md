# 📊 Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-scikit--learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-green)

A machine learning project that predicts whether a telecom customer will churn (leave the service) based on customer demographics and usage behavior.

---

## 🚀 Project Overview

Customer churn is a major problem in subscription-based businesses.  
This project builds a classification model to predict churn using historical customer data.

---

## 📂 Dataset

- Source: Telco Customer Churn Dataset (Kaggle)  
- Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn  

**Target Variable:**
- `Churn` → Whether the customer left the service (Yes/No)

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- scikit-learn
- XGBoost
- LightGBM
- imbalanced-learn (SMOTE)

---

## 🧠 Machine Learning Workflow

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Handling Missing Values
- Handling Class Imbalance (SMOTE)
- Model Training:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - LightGBM
- Model Evaluation
- Hyperparameter Tuning (RandomizedSearchCV)
- Final Model Selection

---

## 🏆 Best Model

- Random Forest Classifier
- Tuned using RandomizedSearchCV
- Evaluated using F1-score and Accuracy

---

## 📦 How to Run

```bash
git clone https://github.com/VaidehiNair/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt