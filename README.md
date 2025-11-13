# Customer Churn Analysis

## Project Overview
This project analyzes customer churn data to identify key factors that influence whether a customer leaves or stays with a company.  
The goal is to use data-driven insights and machine learning models to predict churn and help businesses improve customer retention.

##  Dataset
The dataset includes various customer-related attributes such as:
- CustomerID
- Tenure
- PreferredLoginDevice
- CityTier
- WarehouseToHome
- PreferredPaymentMode
- Gender
- SatisfactionScore
- OrderCount
- Complain
- Churn (Target Variable)

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy – Data cleaning and manipulation  
- Matplotlib, Seaborn – Data visualization  
- Scikit-learn (sklearn) – Machine learning models  

## Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Normalized numerical columns  
- Performed exploratory data analysis (EDA) to detect trends and correlations

## Model Building
Applied multiple classification algorithms to predict churn:
| Algorithm | Accuracy (%) |
|------------|---------------|
| Logistic Regression | 81.97 |
| Random Forest | 96.27 |
| XGBoost | 97.07 |

Best Model: **XGBoost** – Highest accuracy.

---

## 📊 Results & Insights
- Customers with **low satisfaction** and **short tenure** are more likely to churn.
- **PreferredPaymentMode** and **CityTier** significantly impact churn rate.

