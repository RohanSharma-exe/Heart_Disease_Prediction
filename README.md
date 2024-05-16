# Heart Disease Prediction

<img align="center" alt="Coding" width="400" src="https://www.datascienceportfol.io/static/profile_pics/pr0_EC9E6B697B128A4E6459.jpg">

## Introduction

Heart disease is a leading cause of death worldwide. Early detection and prediction of heart disease can significantly improve patient outcomes. This project explores the use of machine learning algorithms to predict the presence of heart disease in patients based on their medical data.

## Table of Contents

- [Usage](#usage)
  - [Libraries Used](#libraries-used)
  - [Importing Data](#importing-data)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Building](#model-building)
- [Results](#results)
- [Conclusion](#conclusion)

## Usage

### Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Importing Data

The medical data used for prediction is imported from a CSV file named `heart_dataset.csv`.

### Exploratory Data Analysis (EDA)

Exploring the data reveals insights into the relationship between different features and the likelihood of heart disease.

### Data Preprocessing

The dataset is split into independent and dependent variables for model training and testing.

### Model Building

#### 1. Logistic Regression

- Achieved an accuracy of 86.34%
- Precision, recall, and F1-score are reported.
- AUC-ROC curve is plotted for performance evaluation.

#### 2. Support Vector Machine (SVM)

- Achieved an accuracy of 74.63%
- Precision, recall, and F1-score are reported.
- AUC-ROC curve is plotted for performance evaluation.

#### 3. Random Forest

- Achieved an accuracy of 100.00%
- Precision, recall, and F1-score are reported.
- AUC-ROC curve is plotted for performance evaluation.
- A visualization of one of the decision trees from the random forest ensemble is provided.

#### 4. Ensemble Learning

- A voting classifier is used to combine predictions from multiple models for improved performance and reliability.

## Results

- Logistic Regression: 86.34% accuracy
- SVM: 74.63% accuracy
- Random Forest: 100.00% accuracy (potentially overfitting)
- Ensemble Learning: Combined predictions from multiple models for improved accuracy and reliability.

## Conclusion

Machine learning models show promising results in predicting heart disease based on medical data. Further refinement and evaluation are needed to deploy a reliable predictive model in clinical settings.
