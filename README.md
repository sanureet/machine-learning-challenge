# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Project Objective

The purpose of this homework was to build build machine leaning models and comlare them to identify the best model for classifying candidate exoplanets from the data provides by NASA.


## Methods used

1. Machine learning
2. Data Visualization

## Technologies

1. Python
2. Scikit-Learn
3. pandas, Jupyter
4. Matplotlib


## Process

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.
* Use `GridSearch` to tune model parameters.
* Tuned and compared at two different classifiers.

## Analysis

SVM model: Training Data Score = 0.83730 and testing Data Score= 0.85583
KNN model (k=19): Training Data Score= 0.83578 and testing Data Score= 0.83066

In conclution, based on the results, it is clear that both (SVM,KNN) models are good.Any of these models can be used.
- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -



© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
