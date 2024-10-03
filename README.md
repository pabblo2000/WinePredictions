# Wine Classification Projects

## Overview

This repository contains two main projects:

1. **GradeClassifier**: A project focused on predicting the quality of wines using various physicochemical properties and applying different preprocessing techniques, exploratory data analysis (EDA), and machine learning models.
2. **ColorClassifier**: This project predicts the color of the wine (red or white) based on the wine's properties.

## Projects

### GradeClassifier
The GradeClassifier project is dedicated to predicting the quality of wines based on various features such as acidity, alcohol content, pH, etc. The workflow includes the following steps:

- **Exploratory Data Analysis (EDA)**: A thorough analysis to understand feature distributions, correlations between variables, and their relation to the target variable (quality).
  
- **Preprocessing**:
  - **Normalization**: Scaling all features using MinMaxScaler.
  - **Box-Cox Transformation**: Applied to ensure a more normal distribution for certain features.
  - **Feature Encoding**: Transforming categorical features where necessary.

- **Models Used**:
  - **Logistic Regression** (Multinomial)
  - **ElasticNet Regression** (Penalized Regression)
  - **Support Vector Machine (SVM)**
  - **Random Forest**
  - **Gradient Boosting** (Optional depending on performance comparison)
  - **XGBoost** (for performance tuning)
  - **Neural Network** (2 hidden layers)

- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix: Used to visualize and evaluate model performance.

### ColorClassifier
The ColorClassifier project predicts whether a wine is red or white based on its physicochemical properties. This project is simpler and focuses on color classification using basic machine learning techniques.

## Conclusion

The GradeClassifier project is the main focus of this repository, providing a detailed analysis and comparison of different machine learning models for wine quality prediction. The ColorClassifier, though simpler, showcases basic classification methods for predicting wine color based on its properties.
