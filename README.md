## Overview

This repository presents a complete machine‑learning pipeline using the Adult Census Income dataset to predict whether an individual earns more than \$50 K annually.

## Dataset

* Source: [Kaggle – Income Evaluation](https://www.kaggle.com/datasets/vijayadityads/income-evaluation)
* Instances: \~48 842; Features: 14 demographic and employment variables

## Contents

* `prediction-classification.ipynb` – step‑by‑step pipeline (data loading, preprocessing, modelling, evaluation)
* `income_evaluation.xlsx` – Excel version of the dataset


This will:

* Inspect and preprocess data (encoding, scaling, splitting)
* Train five classifiers: Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting
* Evaluate models using accuracy, precision, recall, F1‑score, cross‑validation, and ROC‑AUC
* Present a performance comparison table
