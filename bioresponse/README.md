
# Bioresponse Prediction Project

## Project Overview

This project focuses on predicting the biological response of molecules based on their chemical structure. This task is a part of the [Kaggle Bioresponse competition](https://www.kaggle.com/competitions/bioresponse/overview), aiming to streamline drug discovery by predicting biological activities of molecules without the need for extensive laboratory testing.

## Objective

The primary objective is to build and optimize two machine learning models:
- **Logistic Regression**
- **Random Forest**

Each model undergoes hyperparameter tuning to achieve the best possible performance.

## Dataset

The dataset contains features representing the chemical composition of various molecules. The target variable indicates the biological response (`Activity`), with chemical descriptors (`D1` to `D1776`) as features.

## Key Components

1. **Data Preprocessing**: Basic data processing and normalization.
2. **Modeling**:
    - Logistic Regression
    - Random Forest
3. **Hyperparameter Tuning**:
    - Grid Search
    - Randomized Search
    - Hyperopt
    - Optuna

Each tuning method iterates up to a maximum of 50 trials to optimize model parameters.


## Files

- `ML-7_Mazur.ipynb`: Main notebook containing the code for data preprocessing, model training, evaluation, and hyperparameter tuning.

## Results

After tuning, the models are evaluated on cross-validation scores and F1 scores to determine the best configuration. Visualization libraries like `matplotlib` and `seaborn` provide insights into model performance.


