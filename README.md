# 📊 Sales Prediction Using XGBoost

## 🔍 Project Overview
This project demonstrates an end-to-end data analysis and machine learning pipeline to predict total sales using a real-world sales dataset.

The workflow includes data cleaning, feature engineering, encoding categorical variables, and training a regression model using XGBoost.

---

## ⚠️ Data Issues Handled
- Missing values (handled using mean/mode)
- Inconsistent category names (standardized)
- Date formatting issues (converted to datetime features)
- Negative values (removed as invalid entries)
- Outliers (analyzed and handled carefully)

---

## 🛠️ Data Preprocessing
- Converted date column into Year, Month, Day
- Target Encoding applied on high-cardinality feature (`Product`)
- One-Hot Encoding applied on:
  - Category
  - Payment Method
  - Order Status
- Train-test split applied (80-20)
- Feature alignment ensured between train and test sets

---

## 🤖 Model Used
- **XGBoost Regressor**
  - n_estimators = 100
  - learning_rate = 0.1
  - max_depth = 5

---

## 📈 Model Performance
- **R² Score:** ~0.96
- **RMSE:** ~265

---

## 🔁 Cross Validation
- 5-Fold Cross Validation applied
- Ensures model stability and generalization

---

## 📊 Visualizations
- Distribution plots for numerical features
- Category-wise sales analysis
- Actual vs Predicted scatter plot

---

## 🚀 Key Insights
- Electronics and Home categories generate higher revenue
- Some outliers represent high-value transactions
- Data cleaning significantly improved model performance

---

## 🧠 Skills Demonstrated
- Data Cleaning & Preprocessing
- Feature Engineering
- Handling Categorical Variables
- Machine Learning (Regression)
- Model Evaluation & Validation
- Data Visualization

---

## 📌 Conclusion
This project shows how proper data preprocessing and feature engineering can significantly improve model performance in real-world datasets.

---

## 📎 Technologies Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- XGBoost

---

## ⭐ Author
Bhasker Paul
