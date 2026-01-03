# Medical Insurance Cost Prediction – Model Comparison
## 📌 Project Overview

This project focuses on predicting medical insurance charges using multiple machine learning regression models.
The objective is to compare different algorithms and analyze their performance on the same dataset.

## 📊 Dataset Information

Source: Kaggle – Medical Insurance Dataset
Target Variable: charges
Features: age, sex, BMI, children, smoker status, region
Problem Type: Regression

## 🧠 Models Compared & Results
Model	R² Score (approx.)	Remarks
Multiple Linear Regression	~0.70	Strong baseline, mostly linear data
Polynomial Regression (deg=2)	~0.70	No significant improvement
Support Vector Regression (SVR)	~0.17	Underperformed, not suitable
Decision Tree Regressor	~0.68	Captured non-linearity, unstable
Random Forest Regressor	~0.86	Best performance, well-generalized

## Final model ranking (For this Dataset)

1️⃣ Random Forest → ⭐⭐⭐⭐⭐ (0.85+)
2️⃣ Linear / Multiple Regression → ⭐⭐⭐⭐ (~0.7)
3️⃣ Decision Tree → ⭐⭐⭐ (~0.68)
4️⃣ SVR → ⭐ (weak)

## ✅ Conclusion

Among all the models tested, Random Forest Regressor achieved the highest R² score and demonstrated the best generalization performance.
This highlights the importance of selecting models based on data characteristics, not just model complexity.

## 🛠 Tools & Technologies

Python
NumPy, Pandas
Scikit-learn
Matplotlib
Jupyter Notebook