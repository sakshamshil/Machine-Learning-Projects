# Fake News Prediction - Classification
Create a ML model to identify fake news by analyzing content, sources, and context, helping users discern accurate information from misleading or false content.

## Dataset Information

The training data contains 20,800 samples and 5 features. Since the size sample is large, it might take long too load all the datasets into the pandas dataframe and might throw an error if ran before loading.
```
train.csv: A full training dataset with the following attributes:

id: unique id for a news article
title: the title of a news article
author: author of the news article
text: the text of the article; could be incomplete
label: a label that marks the article as potentially unreliable
1: unreliable
0: reliable

test.csv: A testing training dataset with all the same attributes at train.csv without the label.


```
Since the file size is too large, download it directly from the kaggle link provided.

Kaggle Link - https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html](https://www.kaggle.com/c/fake-news/data?select=train.csv
                                
## Libraries Used

* numpy
* pandas
* matplotlib
* regex
* Natural Language Toolkit (nltk)
* scikit-learn

## Algorithm Used

* Logistic Regression
