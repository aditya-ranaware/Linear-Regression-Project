# 🏠 House Price Prediction using Linear Regression

## 📌 Problem Statement

Accurately predicting house prices is essential for buyers, sellers, and real estate investors. House prices depend on multiple factors such as size, number of bedrooms, location, condition, and furnishing.

This project aims to build a machine learning model that predicts house prices based on these features.

---

## 🎯 Objective

* Analyze housing data and identify key factors affecting house prices
* Perform data preprocessing (encoding, scaling)
* Build a Linear Regression model using Scikit-learn Pipeline
* Evaluate model performance using regression metrics
* Generate meaningful insights from the data

---

## 📂 Dataset Description

The dataset contains information about houses with the following features:

### 🔹 Features:

* House Size (sqft)
* Number of Bedrooms
* Age of House (years)
* Location (categorical)
* House Type
* Condition
* Furnishing

### 🔹 Target:

* **House Price (USD)**

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🔄 Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preparation
3. Feature Engineering
4. Encoding (OneHotEncoder)
5. Feature Scaling (StandardScaler)
6. Model Building using Pipeline
7. Model Evaluation
8. Visualization (Actual vs Predicted Prices)

---

## 🤖 Model Used

* Linear Regression

---

## 📊 Results

* **R² Score:** 0.998
* **Mean Absolute Error (MAE):** ~6500
* **Mean Squared Error (MSE):** Low

The model achieved very high accuracy, indicating strong predictive performance.

---

## 📈 Key Insights

* House size has a strong positive impact on price
* Newer houses tend to have higher value
* Furnishing and condition significantly influence pricing
* Location plays a crucial role in determining house prices
* The dataset shows strong linear relationships between features and target

---

## 🏁 Conclusion

The Linear Regression model successfully predicts house prices with high accuracy. The use of a pipeline ensures a clean and reproducible workflow. However, further validation is recommended to ensure the model generalizes well on unseen data.

---

## 🚀 Future Improvements

* Apply advanced models (Random Forest, XGBoost)
* Perform cross-validation
* Feature selection and hyperparameter tuning
* Deploy using Flask or Streamlit

---

## 💡 Key Learning

Using Scikit-learn Pipelines helps prevent data leakage, improves code organization, and follows industry best practices.

---

## 🔗 Author

**Aditya Ranaware**
