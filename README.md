# Heart Disease Prediction Model

This repository contains a machine learning project focused on predicting the risk of heart disease based on patient health metrics. The project implements various classification algorithms to identify patterns and risk factors associated with heart disease.

## 📋 Project Overview

Heart disease remains a leading cause of mortality worldwide. Early detection and accurate prediction of heart disease risk can significantly improve patient outcomes through timely intervention. This project leverages machine learning techniques to develop a predictive model that can assist healthcare professionals in identifying at-risk patients.

## 🔍 Dataset Description

The project utilizes two primary datasets:

### 1. Heart Disease Dataset (`dataset.csv`)
This dataset contains clinical and physiological parameters from 303 patients, with the following features:

- **age**: Age of the patient in years
- **sex**: Gender (1 = male, 0 = female)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol (mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0-2)
- **ca**: Number of major vessels colored by fluoroscopy (0-4)
- **thal**: Thalassemia type (0-3)
- **target**: Presence of heart disease (1 = present, 0 = absent)

### 2. Oxygen Saturation Dataset
This dataset contains oxygen saturation (SpO2) levels for patients, with values ranging between 96.5% and 97.5%. Oxygen saturation is an important vital sign that measures the percentage of hemoglobin binding sites in the bloodstream occupied by oxygen.

Sample values: 98.5, 98.5, 98.5, 97.5, 97.5, 97.0, 96.5, 96.5, 97.1, 97.5...

## 🛠️ Methodology

The project follows a comprehensive machine learning pipeline:

1. **Data Preprocessing**:
   - Handling missing values and outliers
   - Feature selection using correlation analysis
   - Normalization with MinMaxScaler
   - Addressing class imbalance with SMOTE (Synthetic Minority Over-sampling Technique)

2. **Model Implementation**:
   - Random Forest Classifier with hyperparameter tuning
   - K-Nearest Neighbors (KNN) classifier
   - Model evaluation using classification reports, confusion matrices, and Matthews correlation coefficient

## 📊 Results

Our Random Forest model achieved high classification accuracy with optimized hyperparameters. Detailed performance metrics and visualizations are included in the analysis.

## 🎥 Project Presentation

For a comprehensive overview of our methodology and findings, check out our project presentation:
[Click Here](https://mujmanipal-my.sharepoint.com/:v:/g/personal/karan_209301417_muj_manipal_edu/ESEmgrISzFJDtkLeja-sN14BwAjY7sHPUlyfB1OHlHzakw?e=RpHibq).

## 👨‍💻 Contributors

This project was developed as part of the CS3203 Data Science and Machine Learning course (Semester 6) by:
- Aatmaj Amol Salunke
- Karan Gupta
- Piyush Goyal
- Rakesh Lanka

## 🔮 Future Work

- Integration of additional physiological parameters
- Deployment as a web application for clinical use
- Time-series analysis of patient data for dynamic risk assessment
