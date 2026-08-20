# Credit Risk Prediction Using Machine Learning

## Project Overview

This project uses machine learning techniques to predict whether a customer is likely to default on their credit payment.

The project uses a credit risk dataset containing 23 input variables and a target variable representing payment default.

## Objective

The main objective of this project is to:

- Analyze customer credit-related data
- Identify patterns associated with credit default
- Build machine learning classification models
- Evaluate and compare model performance
- Predict the probability of credit default

## Dataset

The dataset contains 30,000 customer records and 23 predictor variables.

The target variable is:

- `0` — No default
- `1` — Default

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Models

Two classification models were developed:

1. Logistic Regression
2. Decision Tree Classifier

## Data Processing

The following steps were performed:

1. Loaded the Excel dataset
2. Checked the dataset structure
3. Removed the unnecessary index column
4. Checked for missing values
5. Cleaned the target variable
6. Separated input and target variables
7. Split the dataset into training and testing sets
8. Applied feature scaling

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## Project Results

The performance of Logistic Regression and Decision Tree models was compared using accuracy and ROC-AUC.

The model with the better performance was selected as the final model for credit default prediction.

## Feature Importance

Feature importance was analyzed using the Decision Tree model to identify the variables that contributed most to the prediction of credit default.

## Conclusion

This project demonstrates how machine learning can be applied to credit risk prediction. The developed models can help identify customers who may have a higher probability of default, supporting better credit-risk assessment and decision-making.

## Project Files

- `Credit_Risk_Prediction.ipynb` — Complete Google Colab notebook containing the analysis, machine learning models, evaluation and predictions.
