# Breast Cancer Classification - Classification

Develop a ML model for breast cancer classification by analyzing medical data, assisting in the accurate diagnosis of benign and malignant breast tumors.

## Dataset Information

It contains 569 data records, 33 columns (including target).

```
Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.
Missing attribute values: none
Class distribution: 357 benign, 212 malignant
```

CSV file included in the directory as "data..csv"

Kaggle  Link : https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29




## Libraries Used

* numpy
* pandas
* sklearn


## Algorithm Used

* Logistic Regression
