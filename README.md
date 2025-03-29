# Heart Disease Prediction System 🩺💖
## Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection and diagnosis can significantly improve treatment outcomes. This project leverages Machine Learning (ML) techniques to predict the likelihood of heart disease based on a set of medical parameters.

The system includes Logistic Regression and K-Nearest Neighbors (KNN) models for classification, evaluates their accuracy, and determines the best K-value for KNN. Additionally, a user-friendly GUI built with Tkinter allows users to input health parameters and receive real-time predictions.

## Features 🚀
✅ Machine Learning Models: Implements Logistic Regression and KNN for heart disease classification.

✅ Model Evaluation: Evaluates training and testing accuracy to compare model performance.

✅ Best K-value Selection: Finds the optimal K-value for KNN using accuracy trends.

✅ Data Preprocessing: Cleans and processes medical data for better model accuracy.

✅ Interactive GUI: Allows users to enter medical details and get instant predictions.

✅ Model Persistence: Saves the trained model using joblib for future use

## Technologies Used 🛠️

Programming Language: Python

Machine Learning Libraries: scikit-learn, pandas, numpy

Data Visualization: matplotlib, seaborn

GUI Development: Tkinter

Model Deployment: Joblib

## Dataset -Description

The dataset is sourced from the Kaggle Public Health Dataset. It contains patient health records with various medical parameters such as:

Age

Gender

Chest Pain Type

Blood Pressure

Cholesterol Levels

Fasting Blood Sugar

Resting ECG Results

Maximum Heart Rate Achieved

Exercise-Induced Angina

Oldpeak (ST Depression)

Slope of Peak Exercise ST Segment

Number of Major Vessels Colored by Fluoroscopy

Thalassemia

The target variable (0 = No Heart Disease, 1 = Heart Disease) helps classify whether a patient is likely to have heart disease.

## Model Training & Accuracy Results 📈

The dataset is split into training (80%) and testing (20%) data. After training, the accuracy of both Logistic Regression and KNN is evaluated.
Additionally, the KNN algorithm is optimized by selecting the best K-value using an accuracy plot. The final trained model is saved as model_joblib_heart for later use.
