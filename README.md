WHO Air Quality Regression Project 
This machine learning project predicts Air Quality Index (AQI) using environmental pollutant data from six global cities. The project explores various regression models to find the most accurate and stable predictor of AQI.

📘 Overview
Dataset: 52,000+ daily air quality records (PM2.5, PM10, CO, NO₂, SO₂, O₃)

Objective: Predict AQI using supervised regression models

Best Model: Polynomial Regression

R² Score: 0.90

RMSE: ~8.5

🧠 Methods Used
Data Cleaning & Preprocessing

Feature Scaling (StandardScaler)

Dimensionality Reduction (PCA)

Regression Models:

Linear Regression

Ridge Regression

Lasso Regression

ElasticNet Regression

Polynomial Regression

Hyperparameter Tuning (GridSearchCV)

Model Evaluation:

R² Score

RMSE

5-Fold Cross-Validation

🛠 Technologies
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

📌 Key Takeaways
Polynomial Regression outperformed all other models with the highest accuracy.

PM2.5, PM10, and CO were the most significant contributors to AQI.

All models were compared for interpretability, performance, and deployment suitability.

🚀 Future Scope
Convert pipeline into a deployable API using Flask or FastAPI

Visualize predictions in a Streamlit dashboard

Apply SHAP or LIME for model explainability
