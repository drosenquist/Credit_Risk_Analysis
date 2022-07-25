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
| <img width="709" alt="oversampling" src="https://user-images.githubusercontent.com/101379969/180678614-c0d029cb-c5fa-497e-81e0-5e9f519bf090.png"> | <img width="705" alt="smote" src="https://user-images.githubusercontent.com/101379969/180678693-21bdb9cc-f6a0-46ae-b5d7-69e41125a0e6.png"> |
| <img width="444" alt="over_score" src="https://user-images.githubusercontent.com/101379969/180678707-06a9848e-736b-417d-a867-f396b95e1af6.png"> | <img width="356" alt="smote_score" src="https://user-images.githubusercontent.com/101379969/180678738-7a2da1d3-adbe-4b31-8e3d-4a773562e0ec.png"> |
| **Undersampling** | **Smoteenn** |
| <img width="710" alt="undersampling" src="https://user-images.githubusercontent.com/101379969/180678794-9264841e-657e-4be9-9922-21a8a9703e2a.png"> | <img width="712" alt="smoteenn" src="https://user-images.githubusercontent.com/101379969/180678823-2fb08f43-cce3-4a88-9eff-782700a88174.png"> |
| <img width="445" alt="under_score" src="https://user-images.githubusercontent.com/101379969/180678855-adf8870a-a1e2-4381-bad4-06a851e87563.png"> | <img width="446" alt="smoteenn_score" src="https://user-images.githubusercontent.com/101379969/180678869-5b63f011-16bb-4423-958e-20bfaa768036.png"> |
| **Random Forest** | **Adaboost** |
| <img width="459" alt="random_forest" src="https://user-images.githubusercontent.com/101379969/180678942-550d91dc-39c0-4d61-8607-87adbbc1e091.png"> | <img width="466" alt="adaboost" src="https://user-images.githubusercontent.com/101379969/180678563-f447d164-8aac-4ad6-aff1-e617d9d825ee.png"> |
| <img width="715" alt="forest_score" src="https://user-images.githubusercontent.com/101379969/180678970-25789be5-4b7f-4962-a6ed-3089736e05f4.png"> | <img width="421" alt="adaboost_score" src="https://user-images.githubusercontent.com/101379969/180678548-ef2b8c01-1865-4786-9530-a61bb448359e.png"> |

- Oversampling has a balanced accuracy score of **.6754**, precision of **.99**, and a recall score of **.64**
- Undersampling has a balanced accuracy score of **.5439**, precision of **.99**, and a recall score of **.40**
- Smote has a balanced accuracy score of **.6514**, precision of **.99**, and a recall score of **..69**
- Smoteenn has a balanced accuracy score of **.6550**, precision of **.99**, and a recall score of **.56**
- Random_forest has a balanced accuracy score of **.8731**, precision of **.99**, and a recall score of **.87**
- Adaboost has a balanced accuracy score of **.9424**, precision of **.99**, and a recall score of **.94**

## Summary
The models had difficulty accurately classifying and predicting high-risk credit risk but were better at accurately classifying low-risk credit. A recommendation would be to use the Adaboost model as it has the highest accuracy, precision, and recall score out of the 6 models use in this project.
