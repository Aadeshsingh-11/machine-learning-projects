# 🚗 Car Price Prediction – Model Comparison
## 📌 Project Overview

This project aims to predict the selling price of used cars using various machine learning regression models.
Multiple models were implemented and compared to understand how different algorithms perform on real-world, categorical-heavy data.

## 📊 Dataset Information

Source: CarDekho (Kaggle)
Target Variable: selling_price

### Problem Type: Regression
Key Features: year, km_driven, fuel, transmission, seller_type, owner

## 🧠 Models Compared & Results

| Model                          | R² Score (approx.) | Remarks                                  |
|--------------------------------|-------------------|------------------------------------------|
| Multiple Linear Regression     | ~0.42 – 0.51      | Weak baseline, mostly linear assumptions |
| Polynomial Regression (deg=2)  | ~0.66             | Captured mild non-linearity, unstable    |
| Support Vector Regression (SVR)| ~ -0.07           | Severe underfitting, not suitable        |
| Decision Tree Regressor        | ~0.60 – 0.65      | Captured non-linearity but unstable      |
| **Random Forest Regressor**    | **~0.66**         | Best and most stable performance         |


## 📈 Key Observations

The dataset is noisy and categorical-heavy, making it difficult for linear and kernel-based models.

Polynomial Regression showed improvement over Linear Regression, indicating mild non-linear patterns.

Support Vector Regression failed to generalize and showed negative R², highlighting poor suitability.

Tree-based models handled the data better.

Random Forest Regressor performed the best by reducing variance and capturing complex relationships.

# ✅ Conclusion

Among all the models tested, Random Forest Regressor achieved the best and most stable performance.
However, overall accuracy remained moderate due to missing real-world factors such as car condition, brand value, and market demand.

This project demonstrates that:

Model selection should be based on data characteristics, not model complexity.

## 🛠 Tools & Technologies

Python
NumPy, Pandas
Scikit-learn
Matplotlib
Jupyter Notebook