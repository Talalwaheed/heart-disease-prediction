# Heart Disease Prediction

A machine learning project that predicts whether a patient is at risk of heart disease 
based on clinical health data. The project covers the full pipeline from data analysis 
to model deployment through an interactive web application.

## Overview

Heart disease remains one of the leading causes of death worldwide. Early detection 
can make a significant difference in patient outcomes. This project trains and compares 
three classification models on a dataset of 303 patient records, then deploys the best 
performing model through a real-time Gradio interface where users can enter health 
details and receive an instant risk assessment.

## What This Project Does

- Loads and preprocesses a heart disease dataset with 13 clinical features
- Performs exploratory analysis including a correlation heatmap and target distribution
- Scales features using StandardScaler for model stability
- Trains and evaluates three machine learning classifiers
- Conducts feature importance analysis to identify the most critical health indicators
- Deploys the best model through an interactive Gradio web interface

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 85.2% | 87.1% | 84.4% | 85.7% |
| Decision Tree | 85.2% | 92.6% | 78.1% | 84.7% |
| Random Forest | 83.6% | 84.4% | 84.4% | 84.4% |

Logistic Regression delivered the best overall balance of precision and recall and 
was selected as the final deployed model.

## Input Features

The model takes the following patient details as input:

- Age, Sex, Chest Pain Type
- Resting Blood Pressure, Serum Cholesterol
- Fasting Blood Sugar, Resting ECG Results
- Maximum Heart Rate, Exercise Induced Angina
- ST Depression, Slope of ST Segment
- Number of Major Vessels, Thalassemia Type

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
- Gradio (interactive web interface)
- Google Colab

## Dataset

The project uses the Cleveland Heart Disease dataset containing 303 patient records 
with 13 clinical attributes and a binary target indicating the presence or absence 
of heart disease.

## Author

M. Talal Bin Waheed
