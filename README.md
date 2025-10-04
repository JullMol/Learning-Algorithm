# Evaluation Metrics Analysis of Classification and Regression Models  
**Case Studies: Customer Churn Prediction & Poverty Forecasting**

## 📄 Description
This repository contains the scientific report **"Evaluation Metrics Analysis of Classification and Regression Models Using Confusion Matrix and Performance Metrics in Churn Prediction and Poverty Forecasting Case Studies."**  

The study combines two main approaches:
- **Classification**: Predicting *customer churn* to support customer retention strategies.
- **Regression**: Forecasting poverty levels at the district/city level in East Java based on socio-economic indicators.

## 📝 Authors
- Dimas Rafi Izzulhaq (24031554084)  
- Nazril Ravi Pratama (24031554129)  
- Halilatunnisa (24031554130)  
Faculty of Mathematics and Natural Sciences, State University of Surabaya  

## 📊 Summary of Results
### 1. Classification – Customer Churn Prediction
- Algorithm: **LightGBM**
- Dataset: 5,000 rows, 70:30 train-test split
- Target: Churn (1) vs Non-churn (0)
- Key Metrics:
  - Recall: **95.0%**
  - F1-Score: **87.1%**
  - ROC-AUC: **91%**
- Insight: **Recall** is the most relevant metric for business contexts, reducing the risk of missing potential churners.

### 2. Regression – Poverty Forecasting in East Java
- Algorithm: **XGBoost Regression**
- Dataset: Socio-economic indicators of districts/cities from 2020–2024, 75:25 train-test split
- Target: Percentage of poor population (%)
- Key Metrics:
  - R²: **0.9793** (97.93% of data variation explained by the model)
  - RMSE: **0.5977**
  - MAPE: **6.48%**
- Insight: **R²** is the most relevant metric for assessing model explanatory power in public policy contexts.

## 🛠️ Research Workflow
1. **Data Collection** – Separate datasets for classification and regression  
2. **Modeling** – LightGBM for classification, XGBoost for regression  
3. **Evaluation** – Confusion matrix & classification metrics; MAE, MSE, RMSE, R² for regression  
4. **Interpretation** – Identify the most suitable metrics for each context  
5. **Recommendations** – Data-driven strategies for customer retention & poverty alleviation  

## 📌 Core Focus
> **Understanding the meaning behind evaluation metrics is more important than the accuracy score alone.**  
> - Classification: Focus on *Recall* to minimize missing churners.  
> - Regression: Focus on *R²* to evaluate model explanatory power.  

## 📜 License
This document was created for academic purposes as part of the Artificial Intelligence course at the State University of Surabaya.
