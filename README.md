# Breast Cancer

## Description
This project investigates what are the main predictors of malignant breast cancer.

## Define the Problem
- What are the main predictor(s) of diagnosis of malignant breast cancer? Which machine learning model has the highest accuracy of prediction?

## Data Collection
- Features of the dataset are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/
- Source of dataset: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- Source of publication: https://www.semanticscholar.org/paper/Nuclear-feature-extraction-for-breast-tumor-Street-Wolberg/53f0fbb425bc14468eb3bf96b2e1d41ba8087f36

## Data Cleaning and Preparation
- New features created after calculating the mean values of 3 old features.
- The `Diagnosis` non-numerical values converted to numerical values to investigate correlation with other features and as target data for machine learning models.

## Exploratory Data Analysis (EDA)
- Most of the data distributions are skewed to the right and have outliers.
- Data standardization can handle outliers but do not produced normalized data with the exact same scale.
- Area and concave points are highly correlated to the diagnosis of malignant breast cancer.
- Insert images of distribution, boxplot and correlation heatmap.

## Machine Learning
- Logistic Regression, Decision Trees, K-Nearest Neighbors (KNN), Support Vector Machine (SVM) and Ensembling Technique were used to find the mode with highest accuracy.

## Conclusion
- Stacking Ensembling Method has the highest accuracy.
- Hyperparameter tuning is recommended to find a better accuracy.

## Contact Information
For questions or feedback, feel free to reach out at josefroslan@gmail.com
