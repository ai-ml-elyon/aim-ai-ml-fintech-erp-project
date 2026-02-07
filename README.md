# aim-ai-ml-fintech-erp-project
FinTech AI for ERP: Predicting Invoice Payment Risk Using Machine Learning to Improve Cash Flow Management  (AIM AI ML Project)
# 🛡️ Invoice Payment Delay Prediction for ERP Systems
### AIM AI/ML Pillar 5 Capstone Project | Elyon Solutions International Inc.

## 📌 Executive Summary
[cite_start]This project implements an end-to-end machine learning solution to predict invoice payment delays within ERP (Odoo/SAP) environments[cite: 12]. By repurposing the UCI "Default of Credit Card Clients" dataset, this model provides CFOs and collections teams with proactive risk scoring and explainable AI (XAI) insights to improve cash flow management.

## 📂 Project Structure
[cite_start]As per AIM Capstone requirements[cite: 65, 66]:
- [cite_start]`/data`: Dataset overview and data dictionary[cite: 32].
- [cite_start]`/notebooks`: Exploratory Data Analysis (EDA), Feature Engineering, and Model Training[cite: 40, 49].
- [cite_start]`/src`: Python scripts for reproducible preprocessing and modeling[cite: 67].
- [cite_start]`/models`: Saved model artifacts (.pkl/XGBoost) and configurations[cite: 48].
- [cite_start]`/reports`: Final HTML Export and Bias & Fairness Analysis[cite: 57].

## 🚀 Key Features
- [cite_start]**Predictive Modeling:** Comparison between Logistic Regression (Baseline) and XGBoost[cite: 43, 49].
- [cite_start]**Explainable AI (XAI):** Integration of SHAP and LIME to explain individual invoice risk factors[cite: 37, 51].
- [cite_start]**Bias & Fairness Audit:** Evaluation of demographic parity and disparate impact across sensitive groups (Gender, Age)[cite: 53, 55].

## 📊 View the Results
[**Click Here to View the Full HTML Technical Report**](./reports/Celeste_Panlilio_AIMP5_Capstone_Fintech_ERP_AI_ML_Payment_Risk_Prediction.html)

## 🛠️ Installation & Reproducibility
1. Clone the repo: `git clone <repo-url>`
2. [cite_start]Install dependencies: `pip install -r requirements.txt` 
3. Run the notebook: `jupyter notebook notebooks/Capstone_Final.ipynb`

## ⚖️ Ethical Statement
[cite_start]This project adheres to Ethical AI principles by performing rigorous bias audits to ensure financial risk predictions do not unfairly penalize protected demographic groups[cite: 50, 54].
