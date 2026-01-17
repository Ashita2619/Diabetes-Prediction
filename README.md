# Diabetes-Prediction based on Multiple Diagnostic and Lifestyle Features

Final Group Project – 02-620: Machine Learning for Scientist, Carnegie Mellon University

# Project Objective

Diabetes is one of the most prevalent chronic diseases worldwide. The objective of this project was to develop and evaluate machine learning models to predict diabetes status using diagnostic and lifestyle-related features collected through large-scale public health surveys.

# Data description

The dataset was obtained from Kaggle and is derived from the 2015 CDC Behavioral Risk Factor Surveillance System (BRFSS). It contains 253,680 survey responses and 21 input features.

The target variable, Diabetes_012, is a three-class outcome:

0: No diabetes

1: Prediabetes

2: Diabetes

The dataset exhibits class imbalance, with significantly fewer observations in the prediabetes and diabetes classes compared to the non-diabetic class.

# Methods

To address class imbalance, Synthetic Minority Over-sampling Technique (SMOTE) was applied to the training data.

The following supervised learning models were trained and evaluated:

-> K-Nearest Neighbors (KNN)

-> Multiclass Logistic Regression

-> Random Forest

Model performance was assessed both before and after SMOTE using confusion matrices and standard classification metrics.

# Results

Confusion matrices were generated to compare model performance prior to and following class balancing.

<img width="614" height="441" alt="image" src="https://github.com/user-attachments/assets/2e69729b-235d-4190-818b-598cb39f6e4b" />

Across all evaluation metrics, the Random Forest model consistently outperformed Multiclass Logistic Regression and KNN, demonstrating improved classification performance on the imbalanced diabetes prediction task.

# Key Takeaways

-> Class imbalance significantly affects predictive performance in health survey data

-> SMOTE improved model sensitivity for minority classes

-> Random Forest provided the strongest overall performance for multiclass diabetes prediction

