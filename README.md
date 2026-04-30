# Student Dropout Prediction - Machine Learning Project

## Introduction
This is a small machine learning project built for practice.  
The project aims to predict students' academic outcomes based on demographic, academic, and social-related features.

## Project Goal
The main goal is to apply a complete machine learning workflow:
- understand the dataset
- clean and preprocess the data
- perform exploratory data analysis
- train classification models
- evaluate model performance

## Dataset
Name: Predict Students' Dropout and Academic Success |
Source: UCI Machine Learning Repository |
Link:       https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success


Logistic Regression vs Random Forest
![LR vs RF](docs/images/LR_RF_comparison.png)

##Findings
The **Enrolled** class was the hardest class to predict for both models.
The class also overlaps substantially with both other classes, which makes the decision boundary less clear.

## Conclusion
Random Forest is the stronger model at the current stage because it provides slightly better overall and more balanced performance.  
However, both models still struggle with the **Enrolled** class.  
This suggests that the main challenge is not simply model choice, but the fact that the **Enrolled** class has less distinct boundaries in important feature space.
