Heart Disease Prediction Using Machine Learning
==============================================

A Comparative Study with Emphasis on Feature Selection and Model Accuracy

Authors:
- Sujan GV (sujangv94@gmail.com)
- Muskan Kumari (muskankumari1532004@gmail.com)
Chanakya University, Bengaluru, Karnataka, India

Overview:
---------
This project implements and compares various machine learning models for predicting heart disease.
We focus on enhancing model accuracy through proper feature selection and evaluation techniques.

Dataset:
--------
We use the Cleveland Heart Disease dataset from the UCI Machine Learning Repository.
It includes 1025 records with 14 clinical attributes.

Selected Features:
------------------
- cp (Chest pain type)
- thalach (Maximum heart rate achieved)
- exang (Exercise-induced angina)
- oldpeak (ST depression induced by exercise)
- slope (Slope of the ST segment)
- ca (Major vessels)
- thal (Thalassemia)
- chol (Cholesterol)
- trestbps (Resting blood pressure)
- restecg (Resting ECG)

Preprocessing:
--------------
- No missing values were found.
- StandardScaler was used to normalize numerical features.
- Feature selection was performed using SelectKBest and mutual_info_classif.

Machine Learning Models:
------------------------
Original Models:
- Artificial Neural Network (ANN)
- Decision Tree
- AdaBoost
- Support Vector Machine (SVM)

Enhanced Models:
- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)

Evaluation Metrics:
-------------------
- Accuracy
- F1 Score
- ROC AUC
- Confusion Matrix

Model Performance Summary:
--------------------------
Logistic Regression:
- Accuracy: 85%
- F1 Score: 83%
- ROC AUC: 91%

Random Forest:
- Accuracy: 99%
- F1 Score: 98%
- ROC AUC: 99%

K-Nearest Neighbors:
- Accuracy: 82%
- F1 Score: 82%
- ROC AUC: 95%

Conclusion:
-----------
Random Forest showed the best performance across all metrics. 
Feature selection significantly enhanced accuracy and interpretability.
Future enhancements may include deeper neural networks and hybrid ensemble methods.

Contact:
--------
- Sujan GV: sujangv94@gmail.com
- Muskan Kumari: muskankumari1532004@gmail.com

References:
-----------
1. Ahmad & Polat (2023), "Prediction of Heart Disease Based on Machine Learning Using Jellyfish Optimization Algorithm"
2. UCI Heart Disease Dataset: https://archive.ics.uci.edu/ml/datasets/heart+Disease
