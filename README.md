# TO NOTE
We are only evaluating seasonals right now because I cleaned the dataset based on season, if yall really want we can add the other types back in also \
Random State is set and standardised as 42 for train test split function

## Introduction
Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) focusing on animes from 2023 Anime Dataset on Kaggle\
https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset


## Problem Definition
Can we predict the score of an anime based on its attributes? \
Which variable(s) is/are the best in predicting the score of animes\
What model would be the best in predicting scores? 

## Parts
  1.Data Cleaning \
  2.Exploratory Analysis \
  3.Regression (+ derieve final vairable set)\
  4.Support Vector Classification \
  5.Keras Neural Networks

## Models Used
Least Square Regression\
K Nearest Neighbours \
Decision Trees\
TensorFlow Keras Neural Networks\
Support Vector Classification


## Conclusion
More variables coming together can make create better models that make more accurate predictions than using single variables alone, for this, we decided to stick to our final variable set: `Popularity`, `Members` + genres + studios\
-refer to Regression notebook for deciding the final variable set\
Comparing the results from the different models, neural networks performed the best, but this is only true after standardising the numerical data values. Otherwise least squares regression would've performed the best overall

Least Squares Regression and support vector classification have comparative results (SVC with slightly better R-squared value, but least squares regression with greater MSE)\
Decision Tree also has comparative results to Least Square Regression (before depth 7)\
K Nearest Neighbours doesn't seem to work very well, since we need a high value of k (around 30, number of neighbours) to get a decent R^2, suggesting too much generalisation



## What we learnt
- One-Hot Encoding
- TensorFlow Keras Neural Networks, Standardisation to reduce the range of values can improve performance of KNN models
- Setting up Anaconda environments
- Using Github for group projects
- Keeping a constant random state for reproducibility throughout notebooks, in train test split function
- Least Squares Regression, K Nearest Neighbours, Decision Trees


## Members
@Eyewhy - Regression, Data Cleaning\
@huegashi - SVC, KNN, EDA\
@GabrielLim01


## References
https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html \
https://machinelearningmastery.com/tutorial-first-neural-network-python-keras \
https://machinelearningmastery.com/setup-python-environment-machine-learning-deep-learning-anaconda \
https://www.tensorflow.org/api_docs/python/tf/keras/Sequential \
https://scikit-learn.org/stable/modules/model_evaluation.html \
Some references to EDA and Linear Regression exercises from lab
