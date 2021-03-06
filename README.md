# Credit_Risk_Analysis

## Overview of the Analysis
The scope of this project is to use Python and Jupyter to build and deploy several machine learning models to help us predict and assess credit risk.  We want to help to employ different techniques to train and evaluate models with with unbalanced classes.  We will oversample data provided by LendingClub.

## Results

### SMOTE Oversampling


![image](https://user-images.githubusercontent.com/98061420/172035584-44fd657e-66ff-4eee-b010-435b877eabc3.png)


The balanced accuracy score is 65%



### SMOTEENN

![image](https://user-images.githubusercontent.com/98061420/172035638-dd30fdf8-788a-41d0-9879-1d02bdc92bcb.png)

Balanced Accuracy score is 63%


### Undersampling
![image](https://user-images.githubusercontent.com/98061420/172035591-d032f14d-37a3-408c-9748-badd9aad982c.png)

The balanced accuracy score is 65%


### Random Forest Classifier 

![image](https://user-images.githubusercontent.com/98061420/172035599-fa0b1c45-9ef4-40da-8987-a9f1d6b53463.png)


The balanced accuracy score is 78%

### Easy Ensemble Classifier

![image](https://user-images.githubusercontent.com/98061420/172035614-d2d7f3d7-6efd-4e68-8213-efd5feeab858.png)

The balanced accuracy score is 93%

## Summary
. 
The Easy Ensemble Classifier has an accuracy score of 93%.  The precision score is very low for all of the models, which can lead to showing high risk across all models and would start to create issues with any methodology the bank starts to implement.
