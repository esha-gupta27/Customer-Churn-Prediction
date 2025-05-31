# 🧠 Customer Churn Prediction  
**Bachelor’s Thesis – Final Year Project**  
St. Xavier’s College, BSc IT  
By: Esha Gupta  

---

## 📌 Overview  
This project was developed as part of my Bachelor’s final year thesis. The objective was to predict customer churn using machine learning models and interpret the factors that influence it. Predicting churn helps businesses understand customer behavior and take proactive steps to retain customers.

---

## 🎯 Objective  
To design and evaluate machine learning models that can predict whether a customer is likely to leave (churn) based on their demographic and behavioral attributes.

---

## 🛠️ Tools & Technologies  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- Jupyter Notebook  

---

## 📊 Dataset  
A publicly available telecom dataset was used. It includes features like:  
- Customer demographics  
- Contract details  
- Monthly and total charges  
- Tenure and usage patterns  

The target variable was `Churn` (Yes/No).

---

## 🧪 Methodology  

1. **Data Preprocessing**  
   - Handled missing values  
   - Encoded categorical variables  
   - Normalized numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and correlations  
   - Identified key features influencing churn  

3. **Model Training & Comparison**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

4. **Model Evaluation**  
   - Accuracy  
   - F1 Score  
   - ROC AUC Score  
   - Confusion Matrix  

---

## 📈 Results  

| Model                | Accuracy | ROC AUC | F1 Score |
|---------------------|----------|---------|----------|
| Logistic Regression | 0.79     | 0.83    | 0.72     |
| Random Forest       | 0.82     | 0.87    | 0.75     |
| XGBoost             | 0.85     | 0.89    | 0.78     |

XGBoost performed the best and was selected as the final model. Feature importance scores revealed that tenure, contract type, and monthly charges were major contributors to churn.

---

## 🔍 Key Learnings  
- Applied complete ML pipeline: preprocessing → training → evaluation  
- Gained experience with model interpretability using feature importance  
- Compared multiple models to optimize performance  
- Understood real-world issues like class imbalance and overfitting

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

