# Overview
This repository contains a dataset related to breast cancer, curated for research and analysis purposes. The dataset encompasses various attributes and features associated with breast cancer cases, aiming to facilitate exploration, modeling, and insights into this critical medical domain.

![Classify Benign and Malignant cancer](Cancer.png)
#### Dataset Description
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

#### Features
1) ID number
2) Diagnosis (0 = malignant, 1 = benign)

Ten real-valued features are computed for each cell nucleus:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)


All feature values are recoded with four significant digits.

#### Notebook
This notebook classifies malignant and benign data samples. 
Notebook content:
1. Import libraries and load the features 
2. Exploratory Data Analysis
3. Model development 
4. Select the model with highest evaluation metric
4. Hyperparameter tuning
5. Save the finalized model

#### Citation
UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

#### License
CC BY-NC-SA 4.0

#### Disclaimer
This dataset and classifier is not intended for diagnostic or clinical use. It is crucial to consult with healthcare professionals and use validated medical data for any medical-related decisions.

