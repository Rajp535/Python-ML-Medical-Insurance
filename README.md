# 🏥 Medical Insurance Cost Prediction

## 📌 Objective
To predict the insurance charges for individuals based on their age, BMI, number of children, smoking habits, gender, and region using regression models. The goal is to help insurance companies and users estimate costs accurately.

## 📊 Dataset
- **Source:** Local file – `medical_insurance.csv`
- **Features:** 
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`
- **Target:** 
  - `charges`

## 🧠 Techniques Used
- Data Cleaning and Handling Missing Values
- Outlier Treatment (IQR method on `bmi`)
- Label Encoding and One-Hot Encoding
- Feature Scaling with StandardScaler
- Log Transformation applied to target `charges`
- Train-test split (60-40 split)
- Linear Regression Modeling
- Regularization using Ridge Regression
- Evaluation using MSE, MAE, and R² Score

## 📈 Model Performances
| Model | Train R² Score | Test R² Score |
|:------|:--------------:|:-------------:|
| Linear Regression | 78.10% | 77.77% |
| Ridge Regression (α=5) | 77.79% | 77.95% |

## 🔍 Key Insights
- Smoking status is the strongest predictor of insurance charges.
- BMI and number of children also slightly influence costs.
- Ridge Regularization slightly improved test R² compared to plain Linear Regression.
- The Residuals (errors) are roughly normally distributed, suggesting a good fit.

## 📁 Files
- `Medical_Insurance_Analysis_Modeling.ipynb` – Full code, EDA, model building, and evaluation.
- `medical_insurance.csv` – Dataset used for model development.

## ✅ Outcome
Built a regression model with around **78% accuracy** in predicting medical insurance charges, helping in risk assessment and cost prediction for insurance applications.

---

# 🚀 Project Badges
![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-brightgreen.svg)
![Regression](https://img.shields.io/badge/Regression-Model-orange.svg)
![Medical Insurance](https://img.shields.io/badge/Domain-Insurance-blue.svg)
