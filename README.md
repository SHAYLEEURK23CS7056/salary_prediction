# Salary Prediction

This machine learning project aims to predict the salaries of data scientists using regression models. Based on various features such as experience level, employment type, remote work ratio, and company size, the model helps estimate salaries in USD.

## 📌 Problem Statement
With the increasing demand for data professionals, it's important to understand how various job-related factors influence salary. This project builds a regression model to predict salaries based on job details.

##  Dataset
- **Name**: ds_salaries.csv
- **Format**: CSV
- **Source**:  kaggle
- **Features**:  
  - `work_year`, `experience_level`, `employment_type`, `job_title`, `remote_ratio`, `company_size`, etc.
- **Target**: `salary_in_usd`

##  Tech Stack / Tools Used
- Python  
- Google Colab  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn (GradientBoostingRegressor)

## 🛠 Steps Performed
1. Loaded and cleaned the dataset
2. Performed exploratory data analysis
3. Encoded categorical variables
4. Built a regression model using Gradient Boosting
5. Evaluated model using R², MAE, RMSE

##  Final Model Performance
- **Model Used**: Gradient Boosting Regressor  
- **R² Score**: 0.2218  
- **MAE**: 39,249  
- **RMSE**: 54,610





