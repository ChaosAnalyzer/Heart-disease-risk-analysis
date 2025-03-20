# Heart-disease-risk-analysis
## Project Overview
### This project aims to analyze heart disease risk using machine learning techniques. The study leverages data from the Heart Disease UCI Dataset available on Kaggle. The goal is to identify patterns and risk factors that contribute to heart disease.
### The analysis includes Exploratory Data Analysis (EDA), feature selection, machine learning modeling, and SHAP-based explainability.
## Dataset Description
### The dataset consists of 205 observations and 13 features related to patient health metrics, such as:
Age
Sex (0 = Female, 1 = Male)
Chest Pain Type (Categorical: 0–3)
Resting Blood Pressure (mmHg)
Cholesterol (mg/dL)
Fasting Blood Sugar (1 = High, 0 = Normal)
Resting ECG Results (Categorical: 0–2)
Maximum Heart Rate Achieved
Exercise-Induced Angina (1 = Yes, 0 = No)
ST Depression ("Oldpeak")
Slope of ST Segment (Categorical: 0–2)
Vessels Colored by Fluoroscopy (0–3)
Thalassemia (Categorical: 0–3)
Target (Heart Disease Outcome) (1 = Disease, 0 = No Disease)
## Exploratory Data Analysis (EDA)
### Key Findings:
Age Factor: Older patients (above 50) showed a higher risk of heart disease.
Cholesterol Levels: Patients with cholesterol levels above 240 mg/dL had a significantly higher incidence of heart disease.
Blood Pressure: High systolic blood pressure (>140 mmHg) correlated with heart disease cases.
Chest Pain Type: Specific types (e.g., atypical angina) have higher risk association.
Exercise & Max Heart Rate: Those with heart disease tend to have lower max heart rates.
## Hypothesis Testing
To validate key assumptions, hypothesis tests were conducted:
#### Chi-Square Test: Determines if categorical features (e.g., chest pain type) influence heart disease.
#### T-Test: Compares cholesterol and BP levels between disease-positive and negative groups.
### Findings:
Cholesterol and Blood Pressure show statistically significant differences in diseased vs. non-diseased groups.
Chest pain types and exercise-induced angina significantly correlate with heart disease outcomes.
## Machine Learning Model Performance
Several machine learning models were tested, including:
Logistic Regression
Deceision Tree
K-Nearest Neighbors (KNN)
## SHAP Analysis (Model Explainability)
### SHAP (SHapley Additive Explanations) was used to interpret the model’s predictions. Key takeaways:
Cholesterol and Blood Pressure had the highest impact on heart disease prediction.
SHAP dependency plots revealed that an increase in cholesterol directly increased the probability of heart disease.
### Feature importance:
Cholesterol (Most influential)
Blood Pressure
Age
Max Heart Rate
 SHAP Dependency Plots: Cholesterol and BP show a direct positive impact on heart disease risk.
## Key Insights & Business Impact
Patients above 50 with high cholesterol and high blood pressure are at significant risk.
Preventive healthcare strategies should target high-risk individuals for early intervention.
SHAP-based analysis helps explain why a patient is at risk, making models more interpretable for medical professionals.
Future work can integrate this analysis into a risk prediction dashboard.

## Reference 
### Dataset Source: Kaggle - UCI Heart Disease Dataset
### SHAP Explainability: SHAP Documentation
### Machine Learning Libraries: Scikit-Learn



