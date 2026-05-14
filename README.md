# Customer Churn Prediction using Machine Learning

## Overview

This project focuses on predicting customer churn using machine learning techniques on the Telco Customer Churn dataset. The objective was to analyze customer-related features and build predictive models capable of identifying customers who are likely to discontinue a service.

The project was implemented using Python in Google Colab and includes the complete machine learning workflow, from data preprocessing to model evaluation.

This repository contains machine learning models developed to predict customer churn using the Telco Customer Churn dataset. Multiple classification algorithms including Logistic Regression, Random Forest, and XGBoost were implemented and evaluated using ROC-AUC metrics.

## Dataset

Dataset used: Telco_Customer_Churn.csv

The dataset contains customer demographic information, account details, and service usage patterns, which are used to predict whether a customer will churn.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Machine Learning Models Used

The following machine learning models were implemented and evaluated:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

Class balancing techniques were applied to address dataset imbalance and improve model performance in both Logistic Regression and Random Forest Classifier.

## Project Workflow

### 1. Data Preprocessing

* Generated new features from existing customer attributes to improve model performance
* Encoded categorical variables
* Performed class balancing to address dataset imbalance
* Performed feature preparation and scaling where necessary

### 2. Model Training

The dataset was divided into training and testing sets, and multiple machine learning models were trained and compared.

### 3. Model Evaluation

Models were evaluated using classification metrics, with particular focus on ROC-AUC score, precision and recall for measuring prediction performance.

## Results

### Best Model Performance

* **ROC-AUC Score:** `0.8643511857318829`

Among the tested models, XGBoost demonstrated strong predictive performance for customer churn classification.

## Repository Contents

01_Logistic_Regression.ipynb
02_Random_Forest.ipynb
03_XGBoost.ipynb
README.md
Telco_Customer_Churn.csv
requirements.txt

## How to Run the Project

1. Clone the repository
2. Install the required libraries
3. Open the notebook using Google Colab or Jupyter Notebook
4. Run the notebook cells sequentially


## Author

Anna Bastin
