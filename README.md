# Breast Cancer

## Description
This project investigates what are the main predictors of malignant breast cancer.

## Define the Problem
- What are the main predictor(s) of diagnosis of malignant breast cancer?
- Which predictive model is the most accurate?

## Data Collection
- Features of the dataset are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/
- Source of dataset: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
- Source of publication: https://www.semanticscholar.org/paper/Nuclear-feature-extraction-for-breast-tumor-Street-Wolberg/53f0fbb425bc14468eb3bf96b2e1d41ba8087f36

## Data Cleaning and Preparation
- Features transformation.
<img src="https://github.com/josefroslan/breastcancer/blob/main/Feature%20Transformation.png" alt="feature transformation"/>

## Exploratory Data Analysis (EDA)
- Most of the data distributions are skewed to the right and have outliers.
<img src="https://github.com/josefroslan/breastcancer/blob/main/distribution%20boxplot.png" alt="distribution & boxplot" width="75%"/>

- Data standardization was implemented to plot correlation heatmap.
- Area and concave points are highly correlated to the diagnosis of malignant breast cancer.
<img src="https://github.com/josefroslan/breastcancer/blob/main/correlation%20heatmap.png" alt="correlation heatmap" width="75%"/>

## Machine Learning
List of models tested for accuracy:
- Logistic Regression
- Decision Trees
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Bagging - Ensembling
- Boosting - Ensembling
- Stacking - Ensembling
  
## Conclusion
- Stacking Ensembling Method has the highest accuracy.
<img src="https://github.com/josefroslan/breastcancer/blob/main/model%20result.png" alt="model accuracy" width="25%"/>
- Hyperparameter tuning is recommended to find a better accuracy.

## Contact Information
For questions or feedback, feel free to reach out at josefroslan@gmail.com
