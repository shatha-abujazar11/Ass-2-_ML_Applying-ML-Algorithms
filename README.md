# Machine Learning Assignment 2: Applying ML Algorithms

## Student Information

**Name:** Shatha Rasmy Abu Jazar

**Student ID:** 2320230176

## Assignment Overview

This project applies supervised and unsupervised machine learning techniques to the Customer Personality Analysis dataset. The objective is to preprocess the data, engineer meaningful features, build predictive models, evaluate their performance, and perform customer segmentation.

## Dataset

**Dataset:** Customer Personality Analysis Dataset
**File:** marketing_campaign.csv

The dataset contains customer demographics, income, spending habits, purchase history, and marketing campaign responses.

## Project Sections

### 1. Data Preprocessing

* Missing value handling using median imputation.
* Feature engineering:
  * Age
  * TotalSpending
  * TotalChildren
* Removal of unrealistic ages and zero-income records.
* Label Encoding for Education.
* One-Hot Encoding for Marital Status.

### 2. Exploratory Data Analysis (EDA)

* Income Distribution
* Age Distribution
* Correlation Heatmap
* Class Distribution Visualization

### 3. Regression

**Target Variable:** TotalSpending

Models:

* Linear Regression
* Ridge Regression (alpha=1.0)
* Decision Tree Regressor (max_depth=5)

Evaluation:

* MSE
* RMSE
* R² Score

### 4. Classification

**Target Variable:** Response

Models:

* Logistic Regression (class_weight='balanced')
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

Evaluation:

* Accuracy
* Precision
* Recall
* F1 Score
* Classification Report
* Confusion Matrix

### 5. Clustering

* StandardScaler
* K-Means Clustering
* Elbow Method
* PCA Visualization
* Cluster Profiling

## Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

## Repository Contents

* Assignment2.ipynb
* marketing_campaign.csv
* README.md

## Instructor

Ibrahim O. Kaware
