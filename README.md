# Credit_Risk_Analysis

## Overview of the analysis:

In this assignment, we were tasked in finding high-risk loans from a database from LendingClub, a loan company. The data given unfortunately had very little data on high_risk loans, which happens to be the main target.In order to train the data to get a better representaion of the target needed, we had to work with imbalanced techniques to resample the data. We used six  machine learning models to fit and predict the data, to see which model worked the best to predict and has higher accuracy.

## Results:

### Random Oversampling

* The accuracy score for this model was 0.83248

![oversampling](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/oversampling.png)

* The precision for the high-risk loans were 0.03
* The recall score for the high-risk is 0.82 and the F1 is 0.06

### Smote Oversampling

* The accuracy score for this model was 0.84409

![smote](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/smote.png)

* The precision for the high-risk loans were 0.04
* The recall score for the high-risk loans is 0.82 with f1 being 0.07

### Undersampling

* The accuracy score for this model was 0.82038

![undersampling](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/undersampling.png)

* The precision for the high-risk loans were 0.02
* The recall score for the high-risk loans was 0.88 with f1 being 0.04

### Combination Sampling

* The accuracy score for this model was 0.844016

![smoteen](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/smoteen.png)

* The precision for the high-risk loans were 0.03
* The recall score for the high-risk loans was 0.83 with f1 being 0.06

### Random Forest Classifier

* The accuracy score for this model was 0.9959

![random_forest](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/random_forest.png)

* The precision for the high-risk loans were 0.88
* The recall score for the high-risk loans was 0.37 with f1 being 0.52


### Easy Ensemble Classifier 

* The accuracy score for this model was 0.942284

![easy_ensemble](https://github.com/Mparra14/Credit_Risk_Analysis/blob/main/easy_ensemble.png)

* The precision for the high-risk loans were 0.09
* The recall score for the high-risk loans was 0.92 with f1 being 0.16



## Summary:

Looking at all six machine learning models, there were two that seem to have the highest accuracy score. One of those was the Random Forest model, it had a 0.99 score for accuracy, but unfortunately it had a low score for recall, this would not be a good model. This would leave the Easy Ensemble classifier as the best machine learning model. This model had an accuracy score of 0.94 with a recall score of 0.92, making it the better model. 
