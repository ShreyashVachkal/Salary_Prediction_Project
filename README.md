# Salary_Prediction_Project
# 💼 Salary Prediction Using Machine Learning

This project aims to predict developer salaries using machine learning models based on real-world data from the Stack Overflow Developer Survey. The goal is to analyze how various features like education level, work experience, country, programming languages, and employment type influence the expected salary of software professionals.

---

## 📌 Project Overview

In the tech industry, salary expectations vary significantly based on multiple factors. This project leverages data science to build a predictive model that estimates salary using key developer profile features.

---

## 📊 Features Used

- **Education Level**  
- **Years of Experience**  
- **Country**  
- **Employment Type**  
- **Programming Languages Worked With** *(multi-label, binarized)*

---

## 🧹 Data Preprocessing

- Used Stack Overflow Developer Survey dataset.
- Categorical encoding for `Education`, `Country`, and `Employment Type`.
- Multi-label binarization for `Programming Languages`.
- Handled missing values and outliers.
- Normalization where necessary.

---

## ⚙️ Models Used

- `LinearRegression`  
- `DecisionTreeRegressor`  
- `RandomForestRegressor` *(Best Performance)*

Models were evaluated using metrics like **MAE**, **RMSE**, and **R² score**.

---

## 🏆 Best Model: Random Forest Regressor

- Provided highest accuracy and generalization.
- Robust against overfitting due to ensemble nature.
- Highlighted feature importance effectively.

---

## 📈 Results and Insights

- Predicted salaries were closest to real-world trends using Random Forest.
- Key features influencing salary:
  - Experience
  - Country
  - Programming Languages
- Visualizations (included in report) provide deep insights into data and predictions.

---

## 🚧 Challenges

- Real-world data introduces noise and inconsistencies.
- Some imbalance in regional salary distributions.
- Multiple languages per person required multi-label processing.

---

## 🔮 Future Scope

- Integration into career guidance tools for real-time salary estimations.
- Expand to include job roles, company size, and benefits.
- Deploy as a web-based prediction app.

---



