# Credit-Card-Default-Prediction-ML
Machine learning project predicting credit card default risk using classification models, with data preprocessing, outlier handling, and model evaluation.

## What is this project?

This project predicts whether a customer will default on their credit card payment next month.

It uses historical financial data such as bill amounts and payment history to make predictions.

## Dataset

The dataset contains customer information including:

* Credit limit (LIMIT_BAL)
* Bill amounts (BILL_AMT1, BILL_AMT2, etc.)
* Payment amounts (PAY_AMT1, PAY_AMT2, etc.)
* Payment history

Target variable:

* **def_pay** → 1 = Default, 0 = No Default

## What was done in this project?

Step-by-step:

1. Loaded and explored the dataset
2. Renamed target column for clarity
3. Removed unnecessary columns
4. Handled outliers using IQR method
5. Split data into training and testing sets
6. Scaled numerical features
7. Trained multiple classification models
8. Tuned models using GridSearch
9. Compared model performance

##  Models Used

* Logistic Regression
* Random Forest Classifier

## How models were evaluated

The models were evaluated using:

* **Accuracy Score** → overall correctness
* **Confusion Matrix** → prediction breakdown
* **Classification Report** → precision, recall, F1-score


## Visualizations

This project includes:

* Target distribution plot
* Correlation heatmap
* Confusion matrix for each model
* Model comparison chart

These help understand both data patterns and model performance.

## Cross Validation

Cross-validation was used to ensure that the model performs consistently across different data splits.

## Result

The best model is selected based on accuracy and overall performance.

## Author
Kalluru Prem
