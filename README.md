# Soil Fertility Prediction

## Overview

This project focuses on predicting soil fertility by employing machine learning models. The dataset underwent preprocessing, including standardization and outlier removal based on boxplot analysis. Four different models were trained: Logistic Regression, Random Forest Classifier, Decision Tree, and Artificial Neural Network (ANN).

## Preprocessing Steps

1. **Standardization:**
   - All features were standardized to ensure consistent scales, aiding model convergence.

2. **Outlier Removal:**
   - Identified and removed outliers using boxplots to enhance the robustness of the models.

## Models Trained

1. **Logistic Regression:**
   - A linear model used for binary classification.

2. **Random Forest Classifier:**
   - An ensemble model combining multiple decision trees to improve predictive accuracy.

3. **Decision Tree:**
   - A standalone decision tree model for classification.

4. **Artificial Neural Network (ANN):**
   - A deep learning model with multiple layers, capable of learning complex patterns.

## Evaluation Metrics

- **Accuracy Score:**
  - A measure of overall classification performance.

- **Confusion Matrix:**
  - Visual representation of model performance, depicting true positives, true negatives, false positives, and false negatives.

## Results

### Logistic Regression

- Accuracy: [83%]
- Confusion Matrix: [Confusion Matrix Image]

### Random Forest Classifier

- Accuracy: [87%]
- Confusion Matrix: [Confusion Matrix Image]

### Decision Tree

- Accuracy: [82%]
- Confusion Matrix: [Confusion Matrix Image]

### Artificial Neural Network (ANN)

- Accuracy: [35%]

## Conclusion

The performance of each model was assessed using accuracy scores and confusion matrices. This README.md provides an overview of the project, highlighting preprocessing steps, models employed, and key evaluation metrics. Detailed results for each model are available in the respective sections.
the label '2' in the target column was not being positively classified in neither of the first two algorithms, descision tree had a better result.The project aims to contribute to the field of soil fertility prediction through the application of machine learning techniques.
