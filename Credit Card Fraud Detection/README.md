# Credit Card Fraud Detection - Classification

Develop an ML model for credit card fraud detection by analyzing transaction data, helping to identify and prevent fraudulent activities effectively.

## Dataset Information

It contains 15936 data records, 31 columns (including target). The dataset is highly unbalanced, the positive class (frauds) account for 0.46% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation.
```
Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
```
(File too big to include in the directory)

Kaggle Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Libraries Used

* numpy
* pandas
* scikit-learn

## Algorithm Used

* Logistic Regression
