# Heart-disease-risk-analysis
## Project Overview
### This project aims to analyze heart disease risk using machine learning techniques. The study leverages data from the Heart Disease UCI Dataset to identify patterns and risk factors that contribute to heart disease. The data used for this analysis is taken from kaggle.The analysis includes Exploratory Data Analysis (EDA), feature selection, machine learning modeling, and SHAP-based explainability.
## Dataset Description
### The dataset consists of 205 observations and 13 features related to patient health metrics, such as:
Age
Cholesterol Levels
Blood Pressure
Smoking Status
Diabetes
Exercise Frequency
Family History
Heart Disease Outcome (Binary: 0 = No, 1 = Yes)
## Exploratory Data Analysis (EDA)
### Key Findings:
Age Factor: Older patients (above 50) showed a higher risk of heart disease.
Cholesterol Levels: Patients with cholesterol levels above 240 mg/dL had a significantly higher incidence of heart disease.
Blood Pressure: High systolic blood pressure (>140 mmHg) correlated with heart disease cases.
Diabetes & Smoking: A clear trend was observed where smokers and diabetic individuals had a higher heart disease probability.
Feature Correlations: Strong correlations were observed between cholesterol, blood pressure, and heart disease.
## Hypothesis Testing
To validate key assumptions, hypothesis tests were conducted:
Chi-Square Test: Used to assess the association between categorical features like smoking status and heart disease.
T-Test: Used to compare cholesterol levels between heart disease and non-heart disease groups.
Findings: Statistically significant differences were found in cholesterol and blood pressure levels between affected and non-affected individuals.
## Machine Learning Model Performance
Several machine learning models were tested, including:
Logistic Regression
Deceision Tree
K-Nearest Neighbors (KNN)
## Hypothesis Testing
To validate key assumptions, hypothesis tests were conducted:
Chi-Square Test: Used to assess the association between categorical features like smoking status and heart disease.
T-Test: Used to compare cholesterol levels between heart disease and non-heart disease groups.
Findings: Statistically significant differences were found in cholesterol and blood pressure levels between affected and non-affected individuals.
## SHAP Analysis (Model Explainability)
### SHAP (SHapley Additive Explanations) was used to interpret the model’s predictions. Key takeaways:
Cholesterol and Blood Pressure had the highest impact on heart disease prediction.
SHAP dependency plots revealed that an increase in cholesterol directly increased the probability of heart disease.
### Feature importance:
Cholesterol (Most influential)
Blood Pressure
Age
Diabetes
## Key Insights & Business Impact
Patients above 50 with high cholesterol and high blood pressure are at significant risk.
Preventive healthcare strategies should target high-risk individuals for early intervention.
SHAP-based analysis helps explain why a patient is at risk, making models more interpretable for medical professionals.
Future work can integrate this analysis into a risk prediction dashboard.

## Refernce of the Data
https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci/code


