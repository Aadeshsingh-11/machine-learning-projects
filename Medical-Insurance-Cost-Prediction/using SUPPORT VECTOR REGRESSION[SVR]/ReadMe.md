Medical Insurance Cost Prediction

Problem:
Predict medical insurance charges based on personal data.

Dataset:
Kaggle – Medical Insurance Dataset

Models Used:
- Polynomial Regression

📈 Result

R² Score: ≈ 0.17

🔍 Observation

SVR showed low performance (R² ≈ 0.17), indicating underfitting and poor suitability for this dataset.

This suggests that SVR struggles with this dataset due to its largely linear nature and the presence of multiple categorical features.

✅ Conclusion

Support Vector Regression was not an effective model for predicting medical insurance costs in this case. Simpler linear models and tree-based models are more suitable for this dataset.