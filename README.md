# MIPP-Medical-Insurance-Price-Predictor-
 In this project, we are going to develop various machine learning models for medical insurance price  prediction on a dataset and we will compare their accuracy(R-squared score). The project is built using Python and several popular libraries for data analysis and machine learning. It includes data preprocessing, feature selection, model training, and hyperparameter tuning to achieve optimal performance.

 
Project Overview
The goal of this project is to help insurance companies, customers, and policymakers better understand and predict the high costs associated with medical insurance. By leveraging machine learning algorithms, we aim to provide accurate insurance price predictions based on various personal and health-related factors.

Dataset
The dataset used for this project is sourced from Kaggle. It includes 25,000 records and 23 independent variables (features) with 1 dependent variable (target). The target variable is the insurance cost, which is continuous and ranges from 2,468 to 67,870.

Features
Features: 22 attributes (8 categorical, 12 numeric)
Target variable: insurance_cost
Data preprocessing steps:
Handling missing values
Outlier detection and removal
Data scaling
Feature encoding for categorical variables


Models Used
The following machine learning models were implemented and compared based on their performance:
Linear Regression
Support Vector Regression (SVR)
Decision Tree Regressor
K-Nearest Neighbors (KNN)
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
Neural Network Regressor

Results
Model performance was measured using the R-squared score on training and testing datasets. Cross-validation was also conducted to ensure model generalization. The highest accuracy on testing data was achieved using Gradient Boosting and XGBoost with hyperparameter tuning.

![Result](https://github.com/user-attachments/assets/07b9c585-92a4-41de-8a75-cd0483129710)

