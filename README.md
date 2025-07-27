# 🏡 House Price Prediction

This project implements a simple **Linear Regression model** to predict house prices based on three key features:

* **Area (in square feet)**
* **Number of Bedrooms**
* **Number of Bathrooms**

## 📌 Objective

The primary objective was to build a predictive model using only the above three features, as per the task guidelines. The model estimates housing prices using these features with the goal of capturing basic trends and relationships.

## 📊 Model and Methodology

* Data Preprocessing: Cleaned and filtered data to remove outliers.
* Feature Selection: Chosen features were limited to `Area`, `Bedrooms`, and `Bathrooms`.
* Model Used: `LinearRegression` from scikit-learn.
* Evaluation Metrics: R² Score and RMSE.

## 📈 Results

The model achieves a reasonable accuracy considering the limited number of features. However, it is a basic implementation and can be significantly improved.

> 💡 **Note:** The accuracy of the model can be enhanced by including more features that show high correlation with the target variable (`Price`). Examples include location, year built, garage size, etc. However, this task was specifically constrained to using only three features.

## 📂 Files

* `InfotechTask_1.ipynb`: Jupyter notebook containing the full implementation.

## 🧠 Future Improvements

* Feature engineering and correlation analysis to add more relevant predictors.
* Outlier treatment and normalization/scaling for robustness.
* Try regularized models like Ridge/Lasso for better generalization.
