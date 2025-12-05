# Predicting Medical Costs: A Linear Regression Analysis

## 🚀 Project Overview

Rising medical expenses are a major challenge for healthcare providers, insurers, and patients. Understanding cost drivers helps **predict claims, set fair premiums, and optimize wellness program budgets**.  

This project demonstrates how **linear regression** can predict medical charges based on **demographic and lifestyle factors**, while linking to **Industrial Engineering (IE) principles** by providing a **cost function that can be used for resource optimization and risk management**.

---

## 🎯 Project Objectives

- Predict individual medical costs using demographic and lifestyle features.  
- Identify key cost drivers (e.g., age, BMI, smoking status).  
- Evaluate model performance and provide actionable recommendations for healthcare analytics and resource allocation.

---

## 🛠️ Methodology

1. **Data Collection & Cleaning**  
   - Dataset: `insurance.csv` (1,338 records, 7 variables: age, sex, BMI, children, smoker, region, charges).  
   - Checked for missing values, duplicates, and correct formatting.

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics for numeric and categorical variables.  
   - Grouped summaries: charges by **smoker status, gender, region**.  
   - Correlation analysis and heatmaps to highlight strong predictors of charges.  
   - Visualizations: histograms, bar charts, boxplots, regression plots.  

<img width="975" height="539" alt="image" src="https://github.com/user-attachments/assets/908f33e8-389f-41c5-9af0-6376ee200fa2" />


3. **Data Preprocessing**  
   - Categorical variables encoded with **one-hot encoding**.  
   - Dataset split: training (50%), validation (25%), test (25%).

4. **Modeling**  
   - Linear Regression model trained on the training set.  
   - Evaluated with **R²** (variance explained) and **RMSE** (average prediction error).  
   - Regression assumptions checked; skewness noted in charges distribution.  

<img width="725" height="556" alt="image" src="https://github.com/user-attachments/assets/fbed117f-9350-414d-b165-7d211ed8bb12" />


5. **Insights & Recommendations**  
   - Identified main cost drivers and key opportunities for optimization.  
   - Proposed improvements for real-world application.

---

## 📊 Key Findings

- **Smoking** is the largest driver of medical costs — smokers incur much higher charges.  
- **Age & BMI** moderately increase costs.  
- **Gender & region** have minimal effect.  
- **Model performance:** R² ≈ 0.77, RMSE ≈ $6,000 — captures main trends but some variability remains.  

<img width="705" height="479" alt="image" src="https://github.com/user-attachments/assets/d0723c16-b3d1-4781-ad7a-3346ab224ab3" />


---

## 📌 Potential Improvements

1. **Feature Transformation (Critical):** Apply a log transformation to the skewed target variable (charges) to satisfy linear regression assumptions and potentially reduce RMSE.  
2. Explore **interactions between variables** (e.g., age × smoker, BMI × smoker) to capture non-additive effects.  
3. Test **non-linear models** (Random Forest, XGBoost) to model complex relationships.  
4. Incorporate additional **health indicators** (pre-existing conditions, medications) for better predictions.  
5. Implement **cross-validation** for more robust evaluation.

---

## 🔗 Project Deliverables

- **Jupyter Notebook:** Full EDA, modeling, evaluation, visualizations, and insights.  
- **Source Data:** `insurance.csv`  
- **Portfolio-ready insights:** Actionable recommendations linked to IE/Optimization principles.

---

## 🎯 IE / Optimization Angle

This predictive model is not only a healthcare analytics tool but also a **cost function** for Industrial Engineering applications:  

- Helps optimize **wellness program budgets**.  
- Guides **resource allocation** based on predicted high-cost individuals.  
- Supports **risk management** and data-driven decision-making.

