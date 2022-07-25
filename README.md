# Credit_Risk_Analysis
## Overview
The purpose of this project was to apply a variety of machine learning models to a credit card credit dataset from LendingClub, a peer-to-peer lending services company risk to predict credit risk.

Machine learning models used:
* RandomOverSampler
* SMOTE oversampling
* ClusterCentroids undersampling
* SMOTEENN over- and undersampling
* BalancedRandomForestClassifier
* EasyEnsembleClassifier

## Results

| **Oversampling** | **Smote** |
|:----------------:|:---------:|
| ![oversampling](images/oversampling.png) | ![smote](images/smote.png) |
| ![over_score](images/over_score.png) | ![smote_score](images/smote_score.png) |
| **Undersampling** | **Smoteenn** |
| ![undersampling](images/undersampling.png) | ![smoteenn](images/smoteenn.png) |
| ![under_score](images/under_score.png) | ![smoteenn_score](images/smoteenn_score.png) |
| **Random Forest** | **Adaboost** |
| ![random_forest](images/random_forest.png) | ![adaboost](images/adaboost.png) |
| ![forest_score](images/forest_score.png) | ![adaboost_score](images/adaboost_score.png) |

- Oversampling has a balanced accuracy score of **.6754**, precision of **.99**, and a recall score of **.64**
- Undersampling has a balanced accuracy score of **.5439**, precision of **.99**, and a recall score of **.40**
- Smote has a balanced accuracy score of **.6514**, precision of **.99**, and a recall score of **..69**
- Smoteenn has a balanced accuracy score of **.6550**, precision of **.99**, and a recall score of **.56**
- Random_forest has a balanced accuracy score of **.8731**, precision of **.99**, and a recall score of **.87**
- Adaboost has a balanced accuracy score of **.9424**, precision of **.99**, and a recall score of **.94**

## Summary