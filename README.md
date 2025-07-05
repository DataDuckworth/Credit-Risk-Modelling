# Credit Risk Modelling

## 📊 Overview

Credit Risk Modelling is the process of predicting the likelihood that a borrower will default on their financial obligations. This project builds a predictive model using historical financial data to estimate the **Probability of Default (PD)** and help financial institutions make data-driven lending decisions.

## 🧠 Objective

- Develop a binary classification model to predict the likelihood of customer default.
- Perform Exploratory Data Analysis (EDA) to understand key drivers of credit risk.
- Use statistical and machine learning techniques (Logistic Regression).
- Evaluate model performance using appropriate metrics like AUC-ROC, Gini, KS Statistic.

## 📁 Project Structure


## 🛠️ Tools & Technologies

- **Programming:** Python 3.12.4
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, imbalanced-learn
- **Version Control:** Git
- **IDE/Notebook:** Jupyter Notebook, VSCode

## 🔍 Dataset

The dataset includes features such as:

- Customer demographics (age, income, employment status)
- Credit history (number of previous defaults, payment history)
- Loan characteristics (loan amount, interest rate, term)
- Target: `Default_Flag` (1 = Default, 0 = Non-default)

> 📌 Note: Use synthetic or anonymized data if you're sharing this repository publicly.

## 📈 Modelling Approach

1. **Data Cleaning & Preprocessing**
   - Missing value treatment
   - Outlier handling
   - Feature engineering
   - Encoding categorical variables

2. **EDA**
   - Distribution analysis
   - Correlation heatmaps
   - Bivariate analysis with target

3. **Model Building**
   - Logistic Regression (Baseline)
   - XGBoost / Random Forest (Advanced)

4. **Model Evaluation**
   - Confusion Matrix
   - ROC Curve / AUC
   - KS Statistic
   - Gini Coefficient
   - Cross-validation

5. **Model Interpretation**
   - Coefficients (Logistic Regression)
   - Feature Importance (XGBoost)
   - SHAP values (optional)

## 🧪 Results

- Best Model: **XGBoost Classifier**
- AUC-ROC: **0.87**
- KS Score: **0.52**
- Top Predictors: `Credit_Utilization`, `Late_Payments`, `Annual_Income`, `Loan_Term`

## ✅ Future Improvements

- Incorporate bureau score (CIBIL, Experian) if available.
- Use time-series features like delinquency trends.
- Deploy model using Flask/Streamlit for real-time scoring.
- Integrate reject inference for enhanced modeling accuracy.
