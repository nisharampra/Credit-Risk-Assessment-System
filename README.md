# Credit-Risk-Assessment-System
# 💳 Credit Risk Assessment System

A machine learning-powered system built in Python using Google Colab to assess credit risk and simulate loan approval decisions based on customer financial and demographic data.

---

## 📌 Overview

This project uses the **German Credit dataset** to build a classifier that predicts whether a loan applicant is a *good* or *bad* credit risk. It performs data preprocessing, model training, evaluation, and real-time risk prediction.

---

## 🚀 Features

- Data preprocessing (label encoding & feature scaling)
- ML model training using **Random Forest**
- Accuracy evaluation and classification report
- Real-time loan approval simulation
- Model saving and export using `joblib`
- Easy-to-understand output for predictions

---

## 📊 Dataset

- **Source**: [German Credit Data on Kaggle](https://www.kaggle.com/datasets/uciml/german-credit)
- **Features**: credit history, loan amount, age, housing status, job type, etc.
- **Target**: `credit_risk` (good/bad)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Python` | Programming Language |
| `Pandas`, `NumPy` | Data manipulation |
| `scikit-learn` | Machine Learning algorithms |
| `LabelEncoder`, `StandardScaler` | Data preprocessing |
| `RandomForestClassifier` | Model training |
| `Google Colab` | Development environment |
| `joblib` | Model persistence |

---

## 🧪 Example Prediction

Sample input (from dataset):
```plaintext
Age: 67, Duration: 6, Credit History: 4, Amount: 1169, Employment: 1, etc.
