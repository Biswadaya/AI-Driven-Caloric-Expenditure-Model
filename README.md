AI-Driven Caloric Expenditure Prediction System

📌 Project Overview

This project focuses on building a machine learning–based system to predict calories burned during physical activity using key physiological and activity-related parameters such as heart rate, body temperature, duration, age, and body weight.
The goal is to provide a more data-driven and accurate alternative to traditional calorie estimation formulas.

🚀 Key Features

Multiple ML Models: Trained and evaluated using

Linear Regression

Decision Tree Regressor

Random Forest Regressor

XGBoost Regressor

Performance Comparison: Models are compared using Mean Absolute Error (MAE) and R² Score.

Improved Accuracy: Ensemble models (Random Forest & XGBoost) outperform basic regression approaches.

Extensible Design: Can be extended for use in fitness tracking systems or wearable integrations.

📂 Dataset

Source: Kaggle
https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos/data

Size: ~15,000 records

Features Used:

Heart Rate

Body Temperature

Duration of Activity

Age

Weight

Height

Activity Type

Data Preprocessing

Handling missing values

Feature scaling and normalization

Feature selection for improved efficiency

🛠️ Tech Stack

Language: Python

Libraries & Tools:

NumPy

Pandas

scikit-learn

XGBoost

Matplotlib

Seaborn

🏆 Model Performance Summary

| Model             | MAE Improvement | R² Score |
| ----------------- | --------------- | -------- |
| Linear Regression | Baseline        | 0.75     |
| Decision Tree     | Moderate        | 0.81     |
| Random Forest     | High            | 0.88     |
| XGBoost           | **Best**        | **0.92** |


Note: Exact performance may vary depending on train-test split and parameter tuning.

📊 Project Workflow

Data Loading & Exploration

Data Cleaning & Feature Engineering

Model Training

Hyperparameter Tuning

Model Evaluation & Comparison

Result Visualization

🎯 Future Scope

Apply deep learning models for further accuracy improvements

Deploy the model as a REST API

Integrate with fitness or health-tracking applications

Train on a more diverse and real-time dataset


🤝 Contributions

Contributions are welcome!
Feel free to raise issues or submit pull requests to improve the project.
