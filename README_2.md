# Overview
This repository contains a dataset related to breast cancer, curated for research and analysis purposes. The dataset encompasses various attributes and features associated with breast cancer cases, aiming to facilitate exploration, modeling, and insights into this critical medical domain.

#### Dataset Description
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

#### Features
1) ID number
2) Diagnosis (M = malignant, B = benign)
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

#### Notebook
This notebook classifies malignant and benign data samples. After exploratory data ana;ysis, all the classifers are compared.
Classifer with highest accuracy was saved and used for validation.

#### Citation
UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

#### License
CC BY-NC-SA 4.0

#### Disclaimer
This dataset and classifier is not intended for diagnostic or clinical use. It is crucial to consult with healthcare professionals and use validated medical data for any medical-related decisions.

