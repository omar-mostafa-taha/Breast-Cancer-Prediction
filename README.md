# Breast-Cancer-Prediction
## Project Overview:
Breast cancer is one of the most common types of cancer that affects women worldwide. Early detection of breast cancer is crucial for increasing the chances of successful treatment. In this project, we aim to develop a machine learning model that can accurately predict whether a breast mass is benign or malignant.

## Data:
The dataset used in this project was obtained from the University of Wisconsin Hospitals, which consists of 569 breast mass samples with 30 features. The features include various characteristics of the mass such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

## Approach:
We first performed exploratory data analysis to understand the data and its distributions. Then, we applied feature selection techniques to identify the most important features that contribute to the prediction. We then built two machine learning models: one with feature selection and the other without. We evaluated the models using F1 score, which is a common metric used for binary classification problems.

## Results:
The model with feature selection achieved a F1 score of 0.96 on the training set and 0.99 on the test set. The model without feature selection achieved a F1 score of 0.98 on the training set and 0.98 on the test set. The results show that both models perform well in predicting the type of breast mass, but the model without feature selection has a slightly higher F1 score.

## Conclusion:
In conclusion, this project demonstrates the effectiveness of machine learning algorithms in predicting the type of breast mass. Early detection of breast cancer is critical, and this model can potentially aid medical professionals in making accurate diagnoses.
