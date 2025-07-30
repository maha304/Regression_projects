# 🌍 Emissions Forecasting using Machine Learning

## 📘 Project Description

This project aims to analyze and forecast carbon emissions using multiple machine learning models, with a focus on the relationship between emissions and key economic and environmental indicators.

The work was developed for a master's research application and includes full model development, evaluation, forecasting, and deployment-ready code.

---

## 🎯 Objective

To investigate how selected independent variables, such as:

- **GDP per capita**
- **Fossil fuel consumption**
- **Urbanization rate**

affect the dependent variable:

- **Carbon Emissions (Y)**

---

## 🛠️ Tools & Techniques

- Python (Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn, Streamlit)
- Models:  SVR, Random Forest, XGBoost
- Evaluation Metrics: R², RMSE, MAE, MAPE
- Forecasting: Recursive predictions for future years (2024–2026)
- Deployment: Streamlit web app

---

## 📊 Model Comparison (Test Set Performance)

| Model         | R² Score | RMSE  | MAE   | MAPE (%) |
|---------------|----------|-------|-------|----------|
| SVR           | 0.97     | 0.11  | 0.08  | 5.80     |
| XGBoost       | 0.98     | 0.10  | 0.08  | 5.91     |
| Random Forest | 0.98     | 0.08  | 0.07  | 4.69     |

> ✅ **Random Forest** achieved the best overall performance on the test set.

---


## 🚀 Deployment (Optional)

A simple **Streamlit application** is available for users to input values and receive instant predictions.

To run locally:

```bash
pip install streamlit joblib
streamlit run app.py
