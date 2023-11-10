# Feature Engineering for CNP Prediction from EEG Data

## Introduction
This repository contains a notebook detailing a feature engineering case study focused on predicting Central Neuropathic Pain (CNP) in patients with Spinal Cord Injury (SCI) using Electroencephalogram (EEG) data. With no current treatment for CNP, accurate prediction through EEG analysis can be crucial for prevention and management.

## Authors
- Omar Jabri
- Yifan Xie
- Tomas Simutis

## Student IDs
- 2519359j
- 2509996x
- 2603015s

## Study Overview
The study analyzes EEG data from 18 patients to identify patterns correlating with the development of CNP. Feature selection methods such as filtering, wrapping, and embedded techniques are explored to refine the dataset and improve the accuracy of the classifier.

## Methods
- Data analysis with outlier detection using Z-score and data scaling using Robust Scaler.
- Classifier selection focusing on robustness to overfitting, with Stochastic Gradient Descent Classifier being the model of choice.
- Hyperparameter tuning with Grid Search to optimize the learning rate and prevent overfitting.
- Various feature engineering techniques applied, including:
  - High Correlation Filter
  - Mutual Information Filter
  - ANOVA f-Test Filter
  - Recursive Feature Elimination (RFE)
  - Ridge/Lasso Regularization

## Results
The methods were benchmarked against several performance metrics with a focus on achieving high sensitivity and AUC scores. The findings are documented in the notebook, providing insights into the efficacy of each method.

## Discussion
After thorough experimentation and analysis, an optimal feature selection method is proposed, favoring the Lasso Embedded feature reduction technique for its speed, performance, and robustness.

## How to Use
The notebook is designed to be executed sequentially. Ensure you have all dependencies installed and follow the steps outlined in the Methods section.

## Requirements
To run the notebook, you will need a Python environment with libraries such as `scikit-learn`, `pandas`, `numpy`, and others typically used in data science workflows.

## Acknowledgments
This case study was carried out as part of the educational curriculum at University of Glasgow. We thank our peers and supervisors for their guidance and support.


