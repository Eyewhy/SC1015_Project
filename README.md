# TO NOTE
We are only evaluating seasonals right now because I cleaned the dataset based on season, if yall really want we can add the other types back in also \
Random State is set and standardised as 42 \
also pls rmb to remove the extra models lying arnd befre submitting

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
  3.Regression \
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
Comparing the results from the different models, neural networks performed the best, but this is only true after standardising the numerical data values. Otherwise, ordinary linear regression would've performed the best

## What we learnt
- One-Hot Encoding
- TensorFlow Keras Neural Networks, Standardisation to reduce the range of values can improve performance of KNN models
- Setting up Anaconda environments
- Using Github for group projects
- Keeping a constant random state for reproducibility
- Least Squares Regression, K Nearest Neighbours, Decision Trees


## Members
@Eyewhy\
@huegashi\
@GabrielLim01


## References
