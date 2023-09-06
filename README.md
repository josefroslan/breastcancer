# Breast Cancer Diagnosis Prediction using Machine Learning

![Breast Cancer Cells](https://cdn.example.com/breast_cancer_cells.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Collection](#data-collection)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
  - [Logistic Regression](#logistic-regression)
  - [Decision Trees](#decision-trees)
  - [K-Nearest Neighbors (KNN)](#k-nearest-neighbors-knn)
  - [Support Vector Machine (SVM)](#support-vector-machine-svm)
  - [Ensembling Techniques](#ensembling-techniques)
    - [Bagging](#bagging)
    - [Boosting](#boosting)
    - [Stacking](#stacking)
- [Conclusion](#conclusion)
- [Contributors](#contributors)

## Introduction

This project focuses on using machine learning techniques to predict the diagnosis of malignant breast cancer based on features extracted from fine needle aspirate (FNA) images of breast masses. The primary goal is to build accurate predictive models that can assist in early cancer detection.

## Problem Statement

The main objective is to identify the most significant predictors of malignant breast cancer diagnosis and determine which machine learning model provides the highest accuracy for this prediction.

## Data Collection

The dataset used for this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic). It contains features computed from digitized FNA images of breast masses. You can find a few of the sample images [here](http://www.cs.wisc.edu/~street/images/).

## Data Cleaning and Preparation

The data cleaning and preparation steps include:

- Loading the dataset and specifying column names.
- Creating new features based on the mean values of specific feature groups.
- Converting non-numerical values to numerical values.
- Standardizing the data to handle outliers and ensure consistent scales.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) involves visualizing the data distribution and investigating outliers. The project uses histograms and box plots to understand the shape of the data distribution.

## Machine Learning Models

Several machine learning models are employed to predict breast cancer diagnosis:

### Logistic Regression

Logistic regression is a simple and interpretable model used to model the probability of binary outcomes. It serves as a baseline for prediction accuracy.

### Decision Trees

Decision trees split the data into subsets based on the most significant attributes at each node. Proper tuning is required to prevent overfitting.

### K-Nearest Neighbors (KNN)

KNN classifies instances based on the majority class among their k nearest neighbors. It is effective for smaller datasets.

### Support Vector Machine (SVM)

SVM finds the optimal hyperplane that best separates the classes. It is suitable for high-dimensional data and can handle non-linearity using kernel functions.

### Ensembling Techniques

Ensemble techniques combine multiple models to improve predictive performance. Three ensemble methods are explored:

#### Bagging

Bagging creates subsets of the training data and trains multiple base models, often using decision trees. Random Forest, a specific bagging implementation, is used in this project.

#### Boosting

Boosting builds an ensemble of decision trees sequentially, with each tree focusing on instances that previous trees struggled to predict accurately. Gradient Boosting is used in this project.

#### Stacking

Stacking combines predictions from multiple base models using a meta-model (e.g., Logistic Regression). It leverages the strengths of diverse models to enhance predictive performance.

## Conclusion

The project aims to identify key predictors of malignant breast cancer and determine the most accurate machine learning model for diagnosis prediction. The results and findings of each model are discussed in detail.

## Contributors

- [Josef Roslan](https://github.com/josefroslan) - Data Scientist

Feel free to contribute, provide feedback, or report issues in this repository.
