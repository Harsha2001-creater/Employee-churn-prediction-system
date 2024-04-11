
# Employee Churn Prediction System

This project aims to develop predictive models for employee departure using a dataset containing information about employees who have left the organization.

## Overview

The project involves the following steps:
1. Overview
2. Correlation Analysis
3. Data Splitting
4. Preprocessing
5. Pipeline Creation
6. Algorithms Used
7. Conclusion

## Correlation Analysis

In this step, correlation analysis is conducted to understand the relationships between different features in the dataset.

## Data Splitting

The dataset is split into training and testing sets to train and evaluate the machine learning models.

## Preprocessing

Various preprocessing techniques are applied to prepare the data for modeling, including imputation, scaling, and encoding categorical variables.

## Pipeline Creation

A machine learning pipeline is created to automate the preprocessing and modeling steps.

## Algorithms Used

The following algorithms are utilized for modeling:
- Logistic Regression
- Decision Tree
- Random Forest

## Hyperparameter Tuning

Hyperparameter tuning is performed to optimize the performance of the machine learning models.

## Conclusion

After thorough preprocessing and evaluation of various machine learning models, this project focused on developing predictive models for employee departure. Based on the F1-score for Class 1, the Decision Tree model significantly outperforms the Random Forest model, while for Class 0, there is a very slight edge for the Decision Tree. As this is imbalanced data, the best metric to choose is the F1-score. Decision Tree slightly outperforms in accuracy and F1-score on an imbalanced dataset. This analysis provides a basis for organizations to detect potential attrition risks and take proactive measures to tackle employee retention issues. This initiative aims to cultivate a supportive workplace environment and preserve valuable talent within the organization.
