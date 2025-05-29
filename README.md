
<h1 align="center">📉 Customer Churn Prediction</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Logistic%20%7C%20Random%20Forest%20%7C%20XGBoost-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Python-3.9+-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square"/>
</p>

---

## 🧠 Overview

This project predicts **customer churn** using machine learning models. It covers the entire data science lifecycle:
- 📊 Exploratory Data Analysis (EDA)
- 🧼 Data preprocessing & feature scaling
- 🤖 Model training: Logistic Regression, Random Forest, XGBoost
- 🧪 Model evaluation: ROC curves, confusion matrix, F1-score
- 💾 Model saving using `joblib`

---

## 🔍 Model Performance

| Model                | Accuracy | ROC AUC | F1 Score |
|---------------------|----------|---------|----------|
| Logistic Regression | ~0.79    | ~0.83   | ~0.72    |
| Random Forest       | ~0.82    | ~0.87   | ~0.75    |
| XGBoost             | ~0.85    | ~0.89   | ~0.78    |

> ℹ️ *Replace these values with your actual scores.*

---

## 💾 Saved Models

Models are exported using `joblib` and stored in the `/models/` directory:
```
models/
├── logistic_regression_model.pkl
├── random_forest_model.pkl
└── xgboost_model.pkl
```

---

## 📈 Evaluation Metrics

- ✔️ Accuracy
- 📉 Precision / Recall / F1 Score
- 🔁 Confusion Matrix
- 📊 ROC-AUC Score & ROC Curve

---

## 📦 Dataset Info

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Target column**: `Churn`
- Contains demographics, account info, service usage

---

## 💡 Future Enhancements

- 🚀 Streamlit or FastAPI deployment
- 🧠 SHAP for model explainability
- 🎯 Hyperparameter tuning with Optuna
- 🐳 Docker containerization

---

## 🤝 Contact

📧 eshaguptacorp@gmail.com  
🌐 [LinkedIn](kedin.com/in/esha-gupta-07b3521a6)

---

<p align="center">
  Made with ❤️ by Esha Gupta
</p>

