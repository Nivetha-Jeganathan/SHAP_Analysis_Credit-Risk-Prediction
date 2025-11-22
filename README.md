# SHAP_Analysis_Credit-Risk-Prediction
This project applies explainable AI (XAI) techniques to a real-world credit risk prediction problem. Using customer financial data, a high-performing XGBoost model is trained to predict loan default probability.The project uses SHAP (SHapley Additive exPlanations) to analyze both global feature importance and individual loan decision explanations.

**#Project Objectives**
Build a robust classification model for predicting loan default
Apply SHAP to interpret model predictions at both global and local levels
Identify the top features driving risk assessments
Generate SHAP force plots for three key customer profiles:
High approval probability
High denial probability
Borderline case
Provide a clear, non-technical explanation suitable for business stakeholders
🚀 Key Features
✔ End-to-End Machine Learning Pipeline
Data cleaning & preprocessing
One-hot encoding for categorical variables
XGBoost model training
AUC + F1-score evaluation
✔ Explainable AI (XAI) with SHAP
Global SHAP summary plot showing overall feature importance
Local SHAP force plots visualizing individual loan decisions
Full explanation for the high-risk (denial) case
✔ Business-Level Interpretability
Narrative interpretation of how factors such as:
credit score
income
debt-to-income ratio delinquency history
impact approval decisions.
