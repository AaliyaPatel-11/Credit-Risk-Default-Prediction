# Credit Risk Default Prediction

## Overview

This project predicts the likelihood of customer loan default using machine learning techniques. The objective is to help financial institutions identify high-risk customers before approving loans.

## Dataset

Dataset: Give Me Some Credit

Records: 150,000

Target Variable:

* SeriousDlqin2yrs

  * 1 = Customer likely to default
  * 0 = Customer not likely to default

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Workflow

1. Data Understanding
2. Missing Value Handling
3. Data Cleaning
4. Feature Engineering
5. Logistic Regression
6. Random Forest Classification
7. Model Evaluation
8. Feature Importance Analysis

## Models Used

### Logistic Regression

Baseline classification model used for credit risk prediction.

### Random Forest

Ensemble learning model used to improve prediction performance.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

## Key Findings

The Random Forest model outperformed Logistic Regression and achieved better predictive performance for identifying high-risk customers.

Important predictive factors include:

* Revolving Utilization of Unsecured Lines
* Debt Ratio
* Income Per Dependent
* Age
* Monthly Income

## Conclusion

The project successfully demonstrates the application of machine learning techniques for credit risk assessment and loan default prediction.
