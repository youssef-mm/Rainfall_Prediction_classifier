# 📘 Final Project - Rainfall Prediction Classifier

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.2-orange)](https://scikit-learn.org/)

## 📝 Overview
This project aims to build a robust machine learning model to predict whether it will rain the next day using historical weather data. Accurate rainfall prediction is crucial for agriculture, water resource management, and disaster preparedness.

## 🎯 Objectives
- Collect and explore historical weather data.
- Clean and preprocess the dataset.
- Implement and evaluate multiple machine learning models.
- Optimize the model for higher accuracy and better generalization.

## 📊 Dataset
The dataset contains weather-related features including:
- Date and location
- Maximum, minimum, and average temperatures
- Humidity levels
- Wind speed and direction
- Atmospheric pressure
- Rainfall amount

**Target variable:** `RainTomorrow` (Yes/No)

## 🛠️ Tools & Libraries
- Python
- Pandas & NumPy (data manipulation)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (machine learning models)
- Jupyter Notebook (interactive analysis)

## 🔍 Methodology
1. **Data Collection:** Using publicly available weather datasets.
2. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
3. **Exploratory Data Analysis (EDA):** Identifying patterns and relationships between features and the target variable.
4. **Model Development:** Implementing and comparing classifiers such as:
   - Logistic Regression
   - Decision Trees
   - Random Forest
5. **Evaluation:** Measuring performance using metrics:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - ROC-AUC Curve
6. **Hyperparameter Tuning:** Optimizing model performance using Grid Search and Random Search.

## 📈 Results
- Multiple classifiers were implemented to predict rainfall with varying accuracy.
- Key features affecting rainfall prediction were identified.
- Model performance was improved using feature engineering and hyperparameter optimization.

## 🔮 Future Work
- Explore advanced models such as XGBoost and neural networks.
- Incorporate additional weather features (e.g., seasonal trends).
- Deploy the model as a web application for real-time rainfall predictions.

## 🙏 Acknowledgements
- This project is part of the IBM Data Science certification program.
- Weather data was sourced from public weather repositories.

## 📄 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
