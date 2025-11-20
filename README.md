# 💊 Predicting Medical Costs: Linear Regression Analysis

## 🌟 Project Summary

This project applies **Linear Regression** to predict **individual medical costs** based on key **demographic and lifestyle factors**.  
By analyzing variables such as **age, BMI, smoking status, number of dependents, and region**, the model identifies the **primary drivers of healthcare expenses**.  

The predictions can support **healthcare planning**, **resource allocation**, and **preventative interventions** by identifying high-cost individuals before medical expenses escalate.  
The analysis emphasizes interpretable, actionable insights, making it practical for healthcare policy and operational decisions.  

---

## 🎯 Key Insights & Findings

### Model Performance
- **Test R²:** 0.77 → 77% of variance in medical charges explained  
- **Validation R²:** 0.78 → Consistent predictive performance  
- **RMSE:** \$5,773 – \$6,102 → Average deviation from actual charges  

### Key Drivers of Medical Costs
1. **Smoking Status** – strongest predictor; smokers have significantly higher medical charges.  
2. **Age** – older individuals incur higher costs due to increased risk of health complications.  
3. **BMI** – higher BMI correlates with higher medical costs.  
4. **Other variables (gender, region, number of children)** – minimal influence compared to the top drivers.  

### Actionable Insights
- **Targeted Interventions:** Focus wellness programs on smokers and high-BMI individuals to reduce costs.  
- **Preventative Care:** Use predicted costs to proactively identify high-risk patients for monitoring and early interventions.  
- **Resource Allocation:** Healthcare providers can prioritize high-cost groups for programs and services.  

---

## 📈 Visualizations

Key plots from the analysis:

### 1. Correlation Heatmap
*Shows relationships between all numeric variables.*  
`![Correlation Heatmap](path/to/correlation_heatmap.png)`  

### 2. Distribution of Categorical Variables
*Gender and smoker status distribution.*  
`![Gender Distribution](path/to/gender_distribution.png)`  
`![Smoker Distribution](path/to/smoker_distribution.png)`  

### 3. Age and Charges Distribution
*Highlights right-skewed charges and age trends.*  
`![Age Distribution](path/to/age_distribution.png)`  
`![Charges Distribution](path/to/charges_distribution.png)`  

### 4. Medical Costs by Gender
*Boxplot showing cost patterns by gender.*  
`![Medical Costs by Gender](path/to/medical_costs_gender.png)`  

### 5. Regression: Age vs Charges
*Scatter plot with regression line illustrating trend.*  
`![Regression: Age vs Charges](path/to/age_vs_charges.png)`  

---

## 🛠️ Technology Stack & Key Skills

**Skills:** Regression Modeling, Feature Engineering, Data Preprocessing, Exploratory Data Analysis (EDA), Correlation Analysis, Model Evaluation (R², RMSE), Predictive Analytics, Actionable Insights, Data Visualization, Risk Factor Identification  

**Tools & Libraries:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - One-hot encoding of categorical variables (sex, smoker, region)  
   - Train/validation/test split (50/25/25)  

2. **Exploratory Data Analysis**
   - Descriptive statistics for all features  
   - Distribution plots, boxplots, and correlation heatmaps  

3. **Model Training**
   - Linear Regression model trained on the training set  

4. **Evaluation**
   - Performance metrics: R² and RMSE  
   - Validation on unseen data to check generalization  

5. **Interpretation & Insights**
   - Identified primary cost drivers  
   - Recommended actionable strategies for healthcare planning and intervention  

---

## 📂 Repository Contents

- `medical_cost_prediction.ipynb` – Jupyter Notebook with all code (data cleaning, EDA, model training, evaluation, visualizations)  
- `insurance.csv` – Dataset used for analysis  
- `README.md` – This documentation  

---

## 💡 Conclusion

This project demonstrates a practical application of **linear regression** for **predicting healthcare costs**.  
Smoking, age, and BMI emerged as the most influential factors, confirming known healthcare patterns and validating the model.  

By combining predictive modeling with interpretable insights, this project provides a **foundation for data-driven healthcare interventions**, helping policymakers and providers prioritize resources effectively and design preventative strategies.
