# Breast-Cancer-Classification

This notebook will look into various Python-based machine learning and data science libaries in attempt to build a machine learning model capable of predicting whether or not a tumor is malignantor benign based on their medical attributes.

We're going to take the following approach:
1. Problem Definition
2. Data 
3. Evaluation
4. Features 
5. Modelling 
6. Experimentation

## 1. Problem Definition

In a statement, 
> Given clinical parameters about a patients tumor, can we predict whether a patient's tumor is malignant or benign?

## 2. Data 

The original data came from the UCI Machine Learning Repository. 
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

There is also a version of the data available on Kaggle.
https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

## 3. Evaluation

> If we can reach 95% accuracy at predicting whether or not a patient't tumor is malignant or benign then we will pursure the project.

## 4. Features

Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

* a) radius (mean of distances from center to points on the perimeter)
* b) texture (standard deviation of gray-scale values)
* c) perimeter
* d) area
* e) smoothness (local variation in radius lengths)
* f) compactness (perimeter^2 / area - 1.0)
* g) concavity (severity of concave portions of the contour)
* h) concave points (number of concave portions of the contour)
* i) symmetry
* j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

* All feature values are recoded with four significant digits.

* Missing attribute values: none

* Class distribution: 357 benign, 212 malignant
