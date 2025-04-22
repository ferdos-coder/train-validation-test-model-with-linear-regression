# Train-Validation-Test Model with Linear Regression

This repository demonstrates how to properly build, train, validate, and test a linear regression model using Python. It provides practical examples of splitting datasets into train, validation, and test sets, fitting linear regression models, and evaluating their performance.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Contents](#contents) 

---

## Project Overview

This project focuses on the workflow of training a linear regression model with proper data splitting into training, validation, and test sets. The key objectives are:

- Demonstrate how to split data into train, validation, and test subsets  
- Fit a linear regression model on the training data  
- Use the validation set to tune or evaluate model parameters  
- Assess the final model performance on the unseen test set  
- Provide clear and reproducible examples using Jupyter Notebooks  

This approach helps avoid overfitting and ensures reliable evaluation of the model’s predictive power.

---

## Dataset

The dataset used in this repository is `Advertising.csv`, which contains advertising data commonly used for regression tasks. It includes features such as TV, radio, and newspaper advertising budgets and a target variable representing sales.

---

## Contents

- `Advertising.csv` — Dataset file with advertising data  
- `fit_linear_model_with_train_eval_test.ipynb` — Jupyter Notebook demonstrating the full workflow of train-validation-test splitting and fitting a linear regression model  
- `grid_search.ipynb` — Jupyter Notebook showcasing hyperparameter tuning via grid search (optional, complementary)  
