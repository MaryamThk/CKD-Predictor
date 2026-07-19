# CKD-Predictor
# Chronic Kidney Disease Prediction using Machine Learning

This repository contains a machine learning project for analyzing and predicting Chronic Kidney Disease (CKD) using patient health data.

The project includes exploratory data analysis, statistical testing, clustering, visualization, and supervised machine learning models.

## Project Overview

Chronic Kidney Disease prediction is a binary classification problem.  
The goal is to use medical and clinical features to predict whether a patient has Chronic Kidney Disease or not.

This project was developed as an educational machine learning practice project in Google Colab.

## Main Steps

The notebook includes the following steps:

- Loading and exploring the dataset
- Data visualization using boxplots and countplots
- Comparing CKD and non-CKD groups
- Statistical testing using T-tests and Chi-square tests
- Clustering using KMeans and DBSCAN
- Dimensionality reduction and visualization using PCA
- Training supervised machine learning models
- Evaluating model performance using classification metrics

## Machine Learning Models

The following models were used in this project:

- Logistic Regression
- Random Forest
- Support Vector Machine

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve

## Dataset

The dataset file is not included in this repository.

To run the notebook, place the cleaned CKD dataset file in the same folder as the notebook.

Expected dataset file name:

```text
ckd_cleaned_data.csv
```

The dataset should contain medical features related to kidney disease, such as blood pressure, hemoglobin, serum creatinine, blood glucose, albumin, and other clinical indicators.

The target column should indicate whether each patient has CKD or not.

## Important Note

This project is for educational machine learning practice only.  
It should not be used as a medical diagnosis tool or as a substitute for professional medical advice.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

```text
CKD-Predictor/
│
├── README.md
├── Chronic_Kidney_Disease_ML_Analysis.ipynb
└── ckd_cleaned_data.csv  # not included in this repository
```

## Author

Maryam Tehranikia
