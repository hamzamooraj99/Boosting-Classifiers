# Boosting Classifiers
This repository contains two implementations of Boosting algorithms for a classification task.

## The Dataset
The dataset is information about patients to identify if the patient has a malignant or benign tumour.

## XGBoost
One of the boosting classifiers used is XGBoost.  
- XGBoost had a very high accuracy of 97.8% on the test set.
- A more accurate measure of the accuracy is after the k-Fold Cross-Validation. This presented an accuracy of 96.71% and a Standard Deviation of 2.28%

## CatBoost
The second boosting classifier used is the newer CatBoost.
- CatBoost had almost the same accuracy as the XGBoost classifier with an accuracy of 97.81%. Just 0.01% more accurate than XGBoost.
- After k-Fold Cross-Validation, CatBoost had an accuracy of 97.26% and a Standard Deviation of 2.03%
- CatBoost seemed to perform better on this dataset than XGBoost.

