# Assignment 6 - Imputation via Regression

**Name:** Sasanka Marthand N
**Roll No:** CE22B079

---

## Overview

This assignment implements and compares different strategies for handling missing data on the UCI Credit Card Default dataset. The steps done are:

- Introduced Missing at Random (MAR) missing values artificially in key numeric columns
- Created 3 imputed datasets using Median imputation (Dataset A), Linear Regression imputation (Dataset B), and KNN non-linear imputation (Dataset C)
- Created Dataset D by listwise deletion (dropping rows with any missing data)
- Split all datasets into train and test sets, standardized features
- Trained Logistic Regression models on each and evaluated performance using classification reports
- Compared and analyzed the results in a summary table

---

## Libraries Used

- pandas  
- numpy  
- scikit-learn (LinearRegression, KNeighborsRegressor, KNNImputer, SimpleImputer, train_test_split, StandardScaler, LogisticRegression, classification_report)  
- matplotlib / seaborn (optional for visualization)  

---

Thank you for reading