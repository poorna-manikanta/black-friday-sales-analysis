# 🛒 Black Friday Sales Analysis & Prediction

## 📌 Project Overview
This project analyzes Black Friday retail purchase data to uncover customer behavior patterns and build a machine learning model to predict purchase amounts.

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (MySQL for data ingestion)
- Scikit-learn
- Power BI (Dashboard)
- VS Code, Jupyter Notebook

## 📊 Project Workflow
1. **Data Ingestion**
   - Loaded raw CSV data
   - Stored data into MySQL database

2. **Exploratory Data Analysis (EDA)**
   - Gender, Age, City Category vs Purchase
   - Product category trends
   - Business insights from visualizations

3. **Feature Engineering**
   - Label Encoding & One-Hot Encoding
   - Missing value handling
   - Final cleaned dataset generation

4. **Modeling**
   - Linear Regression baseline
   - Improved model with feature engineering
   - Final Performance:
     - **RMSE:** ~3062
     - **R² Score:** ~0.63

5. **Model Saving**
   - Final model saved using `joblib`

6. **Visualization**
   - Power BI dashboard for business users

## 📈 Key Results
- Reduced prediction error by ~33%
- Explained ~63% variance in purchase behavior

## 📂 Repository Structure
See folder structure above.

## 🚀 Future Improvements
- Hyperparameter tuning
- XGBoost / Random Forest
- Deployment via Streamlit

---
