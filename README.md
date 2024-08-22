# Heart_Disease_MLOps_Azure_Databricks
Heart Disease Prediction with ML Models on Azure Databricks

## Overview
This project develops a machine learning model to classify heart disease using Azure Databricks. The objective is to build a predictive model that identifies the presence of heart disease based on various clinical features. 

## Dataset
The dataset 'heart_disease.csv', downloaded from [Kaggle](https://www.kaggle.com/datasets/krishujeniya/heart-diseae?resource=download), is stored in Azure Data Lake Storage in Delta format for efficient access and analysis. It includes medical data for heart disease prediction with attributes such as: Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), Fasting Blood Sugar (fbs), Resting Electrocardiographic Results (restecg), Maximum Heart Rate Achieved (thalach), Exercise-Induced Angina (exang), ST Depression Induced by Exercise Relative to Rest (oldpeak), Slope of Peak Exercise ST Segment (slope), Number of Major Vessels (ca), Thalassemia (thal), Target (presence of heart disease).

## Project Files
**0 - EDA:** Exploratory Data Analysis notebook for initial data exploration.

**1 - HealthData_RFmodel1:** Random Forest model training (without hyperparameter tuning) and evaluation.

**2 - HealthData_RFmodel2:** Random Forest model training (with hyperparameter tuning) and evaluation.

**3 - HealthData_XGBmodel1:** XGBoost model training (without hyperparameter tuning) and evaluation.

**4 - HealthData_XGBmodel2:** XGBoost model training (with hyperparameter tuning) and evaluation.

**5 - Batch Inference:** Code for batch inference using the trained model in production.

**6 - requirements.txt:** Python packages required for the project. Use "pip install -r requirements.txt" to install dependencies.
    

