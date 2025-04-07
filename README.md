# Heart-Disease-Classification-Prediction

## Project Objective

This project aims to predict whether a patient has heart disease or not using machine learning classification techniques. Early and accurate detection of heart disease can help prevent misdiagnoses, improve patient outcomes, and support healthcare professionals in decision-making.

## Problem Statement

Heart disease remains one of the leading causes of death worldwide. Detecting it at an early stage is crucial for effective treatment. However, manual diagnosis processes can be time-consuming and prone to errors due to overlapping symptoms and human limitations.
This project attempts to solve:

Potential misdiagnosis in the healthcare process.

Need for a data-driven, consistent prediction system.

The challenge of identifying key indicators of heart disease from medical data.

## Background

The dataset used in this project contains 270 records and 14 attributes, including features such as:

Age

Resting blood pressure

Cholesterol level

Chest pain type

Maximum heart rate

Fasting blood sugar

ST depression induced by exercise, and more

Given the critical nature of this condition, developing a predictive model allows medical personnel to assess patient risk levels based on historical health data.


## Project Output

A binary classification model that determines whether a patient has heart disease (1) or not (0).

A set of key features that significantly influence heart disease prediction.

Performance evaluation metrics to validate the model's reliability.


## Methodology

1. Exploratory Data Analysis (EDA):

Visualizing the relationship between variables and heart disease presence using matplotlib and seaborn.

Understanding data distribution, feature importance, and class balance.

2. Modeling with Machine Learning:

Using Naive Bayes classifier as it provides better accuracy and performance compared to other models in this context.

Comparison with other algorithms using PyCaret's auto ML features.

Evaluation using metrics like accuracy, precision, recall, F1 score, and confusion matrix.

3. Conclusion and Recommendation:

Presenting final results and suggesting how the model can support clinical decision-making.

## Tech Stack

Programming Language: Python

Libraries & Tools:

PyCaret → For quick and efficient modeling and evaluation

Matplotlib & Seaborn → For visualization and EDA

Environment: Jupyter Notebook

## Project Files

heart_disease.ipynb = Jupyter Notebook containing the entire analysis, modeling, and prediction process

logs = installation process

catboost_info (folder) = modelling process

