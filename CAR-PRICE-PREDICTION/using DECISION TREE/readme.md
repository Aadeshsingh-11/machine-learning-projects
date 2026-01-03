# Car Price Prediction – Polynomial Regression
## 📌 Problem Statement

Predict the selling price of used cars based on various features such as year, kilometers driven, fuel type, transmission, seller type, and ownership.

## 📊 Dataset

Source: CarDekho (Kaggle)
Target Variable: selling_price
Problem Type: Regression

### 🧠 Model Used

Polynomial Regression (Degree = 2)
Applied to capture potential non-linear relationships in the data.
Feature scaling and categorical encoding were performed before training.

## 📈 Results

# R² Score: ~0.35

### 🔍 Observation

Polynomial Regression showed poor and unstable performance on this dataset.
The dataset contains many categorical features and noisy real-world factors, making polynomial feature expansion ineffective.

# ✅ Conclusion

Polynomial Regression is not well-suited for this dataset.
Tree-based models are more appropriate for capturing complex patterns in car price data.