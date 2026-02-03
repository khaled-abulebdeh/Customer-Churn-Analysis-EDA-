# 📊 Customer Churn – Data Preprocessing & EDA

## Overview
This project performs **data preprocessing and exploratory data analysis (EDA)** on a synthetic customer churn dataset.  
The goal is to clean the data, explore customer behavior, and identify patterns related to churn in preparation for future predictive modeling.

This work was completed as part of the **Machine Learning and Data Science (ENCS5341)** course.

---

## Dataset
The dataset simulates a customer database where each record represents a customer and their interaction history.

**Target variable:** `ChurnStatus`  
- `0` → Customer stayed  
- `1` → Customer churned  

**Main features include:**
- Age  
- Gender  
- Income  
- Tenure  
- Product type  
- Number of support calls  

---

## Tools & Technologies
- Python  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  

---

## Workflow
1. **Data Loading & Inspection**  
   Initial exploration of structure, types, and distributions.

2. **Missing Value Handling**  
   Numerical features were imputed using mean or median depending on distribution.

3. **Outlier Treatment**  
   Extreme values in selected numerical features were detected and removed.

4. **Feature Scaling**  
   Numerical variables were standardized using Z-score normalization.

5. **Exploratory Data Analysis**  
   - Univariate analysis  
   - Bivariate analysis with churn  
   - Correlation analysis  
   - Insight-driven visualizations  

---

## Key Findings
- Customer churn is relatively rare, resulting in class imbalance.
- Demographic variables alone show weak correlation with churn.
- **Support call frequency** is the strongest indicator of churn.
- Customers with **short tenure** and **lower income** show higher churn risk.

---

## Future Improvements
- Build churn prediction models
- Address class imbalance
- Perform feature engineering
- Evaluate models using standard metrics

---

## Authors
- Khaled Abu Lebdeh  
- Aws Hammad  
---
