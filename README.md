# Diabetes Prediction Model

This repository contains the code and dataset for a machine learning project aimed at predicting the onset of diabetes using patient health data.

## Project Overview

Diabetes is a chronic medical condition that affects millions of people worldwide. Early detection can significantly improve the prognosis. This project applies various machine learning techniques to predict the likelihood of an individual developing diabetes based on health metrics.

## Data Source

The dataset was sourced from Kaggle and has been preprocessed and balanced to ensure model accuracy and reliability. It includes features such as age, BMI, blood glucose levels, and other health-related metrics.

## Models

Several machine learning models have been trained and evaluated, including:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest
- Gradient Boosting

## Preprocessing Steps

- Handling of missing values to maintain data integrity.
- Encoding of categorical variables using OneHotEncoder.
- Feature scaling with StandardScaler to normalize distributions of numerical features.
- Application of SMOTE and RandomUnderSampler to address class imbalance in the dataset.

## Model Evaluation

Model performance was assessed using accuracy, precision, recall, F1-score, and the Receiver Operating Characteristic (ROC) curve.
