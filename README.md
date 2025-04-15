# 📊 Telco Customer Churn Analysis

This project aims to analyze customer churn for a telecom company using data analytics and machine learning techniques. It identifies patterns and key factors contributing to customer churn, helping businesses make data-driven retention strategies.


## 🔍 Problem Statement

Customer churn is a major issue for telecom companies. Retaining customers is more cost-effective than acquiring new ones. This project seeks to:

- Understand the characteristics of customers who churn.
- Identify important features influencing churn.
- Build a predictive model to forecast churn.

## 📦 Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** ~7,000 rows, 21 columns
- **Features:**
  - Demographics: Gender, Age, SeniorCitizen
  - Services: PhoneService, InternetService, etc.
  - Account Info: Contract, Tenure, MonthlyCharges, etc.
  - Target Variable: `Churn` (Yes/No)

## 🧪 Technologies Used

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost
- **Notebook:** Jupyter

## 📈 EDA Highlights

- Visualized churn by contract type, tenure, and internet services.
- Correlation matrix to understand feature relationships.
- Feature encoding and missing value treatment.

## 🤖 Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- K-Nearest Neighbors (KNN)

### ✅ Model Evaluation

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

## 📊 Key Findings

- Month-to-month contract customers have higher churn rates.
- Fiber optic internet service users are more likely to churn.
- Longer tenure = Lower churn probability.
- Paperless billing and higher monthly charges are also churn indicators.
