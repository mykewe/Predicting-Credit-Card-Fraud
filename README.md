# Predicting-Credit-Card-Fraud

### Overview
* This project predicts which credit card transactions in the dataset are fraudulent using three classification algorithms and three synthetic balancing techniques. The three classifier algorithms we will train include:
  + Decision Tree, which uses a tree-like model of decisions to arrive at a classification prediction.
  + Naive Bayes, which uses Bayes' theorem to use probability to arrive at a classification prediction.
  + Linear Discriminant Analysis, which finds a linear combination of features that is then used to separate the classes and arrive at a classification prediction.

### Metric
Since it is highly important to correctly classify fraudulent transaction, the most important performance measure for this fraud problem is the **recall**, which measures how complete our results are indicating the model captures more of the fraudulent transactions.

### Outcome
Because the data is highly imbalanced, containing just 1% of fraudulent transaction, balancing the data set is very important, hence using the unbalanced dataset gives the highest recall score, with the decison tree algorithm performing best.


### Data set
* creditcardfraud.csv is the dataset used, which is a subset of the dataset from sourced from https://www.kaggle.com/mlg-ulb/creditcardfraud, which includes anonymized credit card transactions.

### Notebook
* Predicting Credit Card Fraud.ipynb is the jupyter nootbook containing:
 - Exploratoey Data Analysis
 - Data Balancing
 - Model Building
 - Model Evaluation

#### Inspiration 
This is a cousera project https://gb.coursera.org/projects/predicting-credit-fraud-with-r, which I have improved upon by creating reusable functions, thereby circumventing unnecessary code repetition.
