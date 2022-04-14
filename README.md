# SC1015 SC14 Group 5 Data Science Project

## Table of Contents
  * [About](#about)
  * [Contributors](#contributors)
  * [Problem Definition](#problem-definition)
  * [Models Used](#models-used)
  * [Outcome](#outcome)
  * [New methods and experience learnt](#new-methods-and-experience-learnt)
  * [Insights](#insights)
  * [References](#references)



---

## About 

Welcome to SC14 Group 5's repository! This repository contains the codebase and dataset of the Mini-Project completed in fufilment of the module INTRO TO DATA SCI & ART INTELL (SC1015).

This project explores a dataset from NASA's NeoWs (Near Earth Object Web Service) on asteroids. 

Please download the [dataset nasa.csv](../main/nasa.csv) and view the notebooks in the following order:
1. [EDA & Data Cleaning](../main/sc14_team5_EDA_final.ipynb)
2. [Linear Regression](../main/sc14_team5_linreg_final.ipynb)
3. [Logistic Regression](../main/sc14_team5_logreg_final.ipynb)
4. [XGBoost](../main/sc14_team5_xgboost_final.ipynb)


---
## Contributors

- @jamiiiem (Jiayun) Exploratory Data Analysis and Data Cleaning
- @kenho01 (Ken) Logistic Regression
- @jpl12345 (John) Linear Regression and XGBoost

---
## Problem Definition

- Can we predict the diameters of asteroids?
- Can we predict if an asteroid poses a threat?

---
## Models Used

1. Linear Regression - diameter prediction
2. Logistic Regression - to classify if an asteroid is a hazard
3. XGBoost - to classify if an asteroid is a hazard

---
## Outcome

<b> We successfully answered our problem statements:
-	We were able to predict if an asteroid poses a threat with high accuracy, and only 2 features are required.
-	We were able to predict the diameters of asteroid, with good MSE.
</b> 

---
## New methods and experience learnt

We have learned how to use new models, which include:
-	Logistic Regression
-	XGBoost

We have also learned new methods, such as:
-	Scaling
-	Skewness Correction
-	Class Balancing
-	Cross Validation

We have also used a new evaluation metric:
-	ROC-AUC

We have learnt that:
1.	Skewness correction does not always improve the performance of the model, but it can sometimes.
2.	How to select features to simplify models.
3.	The importance of data cleaning. We have dropped more than half of the original features as they were redundant. 


---
## Insights

From the logistic regression and XGBoost models, the top 2 most important features used to classify if an asteroid is hazardous are: ‘Absolute Magnitude’ and ‘Minimum Orbit Intersection’.
And with XGBoost, using these 2 features alone is sufficient to predict whether an asteroid is hazardous with an accuracy of >99%.

We were also able to predict the Maximum Estimated Diameter of an Asteroid using linear regression with a high coefficient of determination and low mean squared error. Being able to predict the estimated diameter of an Asteroid can be a useful tool for scientists to estimate the severity of damage in the event of an impact.


---
## References
- https://www.kaggle.com/shrutimehta/nasa-asteroids-classification
- https://www.kaggle.com/ke2207/classification-example-using-log-reg-svm-rfc/notebook
- https://www.kaggle.com/ke2207/classification-example-using-log-reg-svm-rfc/notebook
- https://medium.com/analytics-vidhya/asteroid-diameter-prediction-using-machine-learning-3e81eb14dd7a
- https://analyticsindiamag.com/7-types-classification-algorithms/
- https://xgboost.readthedocs.io/en/stable/tutorials/model.html
- https://www.kaggle.com/jav1d98/getting-99-68-accuracy-with-xgbclassifier-model
- https://www.ibm.com/support/pages/transforming-variable-normality-parametric-statistics
- https://datascience.stackexchange.com/questions/54908/data-normalization-before-or-after-train-test-split
- https://stats.stackexchange.com/questions/255105/why-is-the-validation-accuracy-fluctuating
