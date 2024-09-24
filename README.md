# Overview
"Exploring real-world datasets focused on solving Regression and Classification problems using machine learning, deep learning, data visualization, and statistical analysis techniques to derive actionable insights."

# Regression Projects Portfolio

This repository contains data science projects focused on solving **regression problems**, where the target variable is continuous. Each project involves exploratory data analysis (EDA), feature engineering, and various regression techniques to predict outcomes.

## Table of Contents

1. [the_effect_of_foreign_trade_on_Egptian_GPP](#the_effect_of_foreign_trade_on_Egptian_gdp)
2. [Predicting_the_effect_of_Telecome_sector_on_GPP](#predicting_the_effect_of_Telecome_sector_on_gdp)
3. [Non-Performing Loans (NPL) Analysis](#non-performing-loans-npl-analysis)

---

## 1. the_effect_of_foreign_trade_on_Egptian_GPP

.
- [Project Files](./the_effect_of_foreign_trade_on_Egptian_gdp)
  
**Description**: Measure the effect of foreign trade (exports, imports) and other economic features (like debt and foreign assets) on Egypt's GDP using time series regression models.
- **Techniques**: ElisticNet Regression, VAR Model, SVR model, and LSTM.
- **Dataset**: GDP data.
---

## 2. Predicting the effect of the Telecom sector on GDP

- [Project Files](./Predicting_the_effect_of_the_Telecom_sector_on_GDP)
  
**Description**: Predicting the effect of the Telecom sector on Egypt's GDP using time series regression models.
- **Techniques**: Ridge -VAR -Xgboost -RandomForest.
- **Dataset**: Telecom data


---

## 3. Understand what factors influence non-performing loans

- [Project Files](./factors_influence_non-performing_loans)

### Problem Overview

**Non-Performing Loans (NPL)** refer to loans where borrowers have defaulted or are close to defaulting. In this project, we use regression techniques to predict the **time until default** (continuous target variable), making it a regression problem.

### Key Objectives

- **Predict the time to default**: Estimate how long it will take before a loan becomes non-performing.
- **Understand the factors influencing default risk**: Analyze features like loan amount, borrower credit score, and debt-to-income ratio.

### Project Workflow

1. **Data Collection**: The dataset contains loan characteristics, borrower information, and repayment history.
2. **Exploratory Data Analysis (EDA)**: Explore patterns in the data and identify correlations between features and the time to default.
3. **Feature Engineering**: Create new features like debt-to-income ratio, loan-to-value ratio, and payment delays to improve model performance.
4. **Modeling**: Use regression models such as:
   - **Linear Regression**: For basic time-to-default predictions.
   - **Random Forest Regression**: To capture non-linear relationships.
   - **Gradient Boosting Models**: For improved predictive accuracy.
5. **Evaluation**: Evaluate models using metrics like Mean Squared Error (MSE) and R-squared.

### Dependencies:

Most of the dependencies are installed automatically. But, if not installed when you install MSDA, then these dependencies must be installed as shown below.

*pip install pandas*
*pip install numpy*
*pip install matplotlib*
*pip install datetime*
*pip install statistics*
*pip install seaborn*
*pip install sklearn*
*pip install scipy*
*pip install keras*

### Example Code for Modeling

```python
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, r2_score

# Fit a Random Forest model
rf_model = RandomForestRegressor()
rf_model.fit(X_train, y_train)

# Predictions
y_pred = rf_model.predict(X_test)

Evaluation:

mse = mean_squared_error(y_test, y_pred)
r2 = r2_score(y_test, y_pred)


