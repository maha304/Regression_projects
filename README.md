# Regression & Statistical Analysis Portfolio

> Applied projects that use regression, forecasting, experimentation, and exploratory analysis to turn economic, environmental, and product data into practical decisions.

## Portfolio Overview

This repository brings together projects across environmental forecasting, digital experimentation, lending analysis, and macroeconomic research. The work demonstrates the full analytical workflow: defining a question, cleaning data, exploring relationships, selecting an appropriate statistical or machine-learning method, evaluating results, and communicating a recommendation.

## Featured Projects

### 1. Carbon Emissions Forecasting

**Question:** How accurately can carbon emissions be estimated from economic and environmental indicators such as GDP per capita, fossil-fuel consumption, and urbanization?

Three models were compared using a chronological test set. Random Forest achieved the strongest reported performance with **R² = 0.98**, **RMSE = 0.08**, and **MAPE = 4.69%**.

![Actual versus predicted emissions](assets/emissions-actual-vs-predicted.png)

[View project](./Emission_prediction)

### 2. E-commerce A/B Test

**Question:** Should an e-commerce company replace its existing landing page with a new design?

The experiment analyzed **290,584 valid user records** using probability analysis, simulation, a proportions z-test, and logistic regression. The new page did not produce a statistically significant improvement, so the evidence supported keeping the existing page rather than launching the redesign.

![A/B test null distribution](assets/ab-test-null-distribution.png)

[View project](./AB%20test%20for%20website)

## Additional Research Projects

| Project | Business or research question | Methods |
|---|---|---|
| [Foreign trade and Egyptian GDP](./the_effect_of_foreign_trade_on_Egptian_GDP) | Which trade and macroeconomic indicators contain useful information for explaining and predicting GDP? | ADF, Granger, Johansen, Elastic Net, Ridge, SVR |
| Telecom sector and GDP | What is the relationship between telecom-sector indicators and economic output? | Ridge, VAR, XGBoost, Random Forest |
| Prosper loan exploration | Which borrower and loan characteristics are associated with lending outcomes? | Data cleaning, univariate and multivariate EDA |

## Core Skills Demonstrated

- Statistical hypothesis testing and experiment interpretation
- Time-series preparation and forecasting
- Regression model comparison and error analysis
- Feature engineering and exploratory data analysis
- Translating model outputs into clear recommendations

## Tools

Python · Pandas · NumPy · Scikit-learn · XGBoost · Statsmodels · Matplotlib · Seaborn · Jupyter Notebook

## Contact

[GitHub Profile](https://github.com/maha304) · [LinkedIn](https://www.linkedin.com/in/maha-abbas-100270126/)


