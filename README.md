# Implementaion of Neural additive model
## Overview
This repository contains code for creating, training, and interpreting a Neural Additive Model (NAM) on the Housing dataset. The NAM is designed to capture complex relationships between input features and the target variable, which is house prices in this case.

## Requirements
* TensorFlow v2
* Matplotlib
* NumPy
Make sure to have these dependencies installed before running the code.

## Dataset
The code is configured to work with various datasets such as Housing, BreastCancer, Recidivism, Fico, Mimic2, and Credit. You can specify the dataset by setting the dataset_name variable.

## Outputs
The code calculates metrics such as RMSE (Root Mean Squared Error) or AUROC (Area Under the Receiver Operating Characteristic curve) based on the dataset type (regression or classification).
### Feature Label Mappings:
Feature label mappings and column names are provided for better interpretation.

### Categorical Feature Names:
Categorical feature names are specified based on the dataset.

### Mean Feature Importance:
The mean feature importance is calculated, and a bar chart is generated to visualize the overall importance of each feature.

### Plotting Helper Functions:
Several helper functions are provided for plotting histograms and visualizing feature contributions.

### Results
The code outputs visualizations and metrics to interpret the NAM model's performance on the Housing dataset
