# SC1015 Data Science Project Grp5 SC14

---

## About 

Welcome to SC14 Group 5's repository! This repository contains the codebase and dataset of the Mini-Project completed for the module INTRO TO DATA SCI & ART INTELL (SC1015).

Please view the Jupyter Notebooks in the following order:
1. 

## Contributors

- @jamiiiem (Jiayun) Exploratory Data Analysis and Data Cleaning
- @kenho01 (Ken) Logistic Regression
- @jpl12345 (John) Linear Regression and XGBoost

## Problem Definition

- Can we predict the diameters of asteroids?
- Can we predict if an asteroid poses a threat?

## Models Used

1. Linear Regression - diameter prediction
2. Logistic Regression - to classify if an asteroid is a hazard
3. XGBoost - to classify if an asteroid is a hazard

## Outcomes
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

<b> We successfully answered our problem statements:
-	We were able to predict if an asteroid poses a threat with high accuracy, and only 2 features are required.
-	We were able to predict the diameters of asteroid, with good MSE.
</b> 

## Insights

From the logistic regression and XGBoost models, the top 2 most important features used to classify if an asteroid is hazardous are: ‘Absolute Magnitude’ and ‘Minimum Orbit Intersection’.
And with XGBoost, using these 2 features alone is sufficient to predict whether an asteroid is hazardous with an accuracy of >99%.

We were also able to predict the Maximum Estimated Diameter of an Asteroid using linear regression with a high coefficient of determination and low mean squared error. Being able to predict the estimated diameter of an Asteroid can be a useful tool for scientists to estimate the severity of damage in the event of an impact.

## References

[https://stats.stackexchange.com/questions/255105/why-is-the-validation-accuracy-fluctuating]
