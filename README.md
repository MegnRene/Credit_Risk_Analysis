# Credit_Risk_Analysis

## Overview
  Credit risk is naturally an unbalanced classification problem and good loans easily outnumber risky loans. I employed different techniques to train and evaluate models with unbalanced classes. Using a credit card dataset from LendingClub I oversampled the data using RandomOverSampler and SMOTE algorithms, and undersampled the data using ClusterCentroids algorithm. Then I used a combinatorial approach of over/undersampling using the SMOTEEN algorithm. Also, I compared two machine learning models that reduced bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 

### Oversampling RandomOverSampler Model:
![image](https://user-images.githubusercontent.com/98067116/179140653-f52f5768-7aa8-408a-b258-12bcdf171868.png)

* Balanced Accuracy Score: 0.6293939430565123
* Precision score: 99%
* Recal score: 68 %

### SMOTE Oversampling Model:
![image](https://user-images.githubusercontent.com/98067116/179140759-a047250e-9230-47cf-9d1d-7df5c059446e.png)

* Balanced Accuracy Score:0.6293939430565123
* Precision score: 99%
* Recal score: 68%

### Undersampling ClusterCentroids Model:
![image](https://user-images.githubusercontent.com/98067116/179140890-923f5ac1-0d4c-492e-b24c-9a108cac9e71.png)

* Balanced Accuracy Score:0.6293939430565123
* Precision score: 99%
* Recal score: 44%

### Combination Sampling SMOTEENN Model:
![image](https://user-images.githubusercontent.com/98067116/179140971-c0d279a9-919b-4ebc-aa37-5f1e79045eb4.png)

* Balanced Accuracy Score:0.5103017191018931
* Precision score: 99%
* Recal score: 58%

### Balanced Random Forest Classifier Model:
![image](https://user-images.githubusercontent.com/98067116/179141220-0daa6711-a7b9-4d85-a6ca-b98e7e9b7a0c.png)

* Balanced Accuracy Score:0.7877672625306695
* Precision score: 99%
* Recal score: 91%

### Easy Ensemble AdaBoost Classifier Model:
![image](https://user-images.githubusercontent.com/98067116/179141372-0d55cbde-29bb-40bc-afc8-40a2d6ad6bd7.png)

* Balanced Accuracy Score:0.925427358175101
* Precision score: 99%
* Recal score: 94%

## Conclusion
  Out of the five machine learning algorithms Easy Ensemble AdaBoost Classifier Model performed the best. It has the least number of false negatives, also has the highest recall score for detecting high risk samples correctly. I would reccomend the Easy Ensemble AdaBoost algorithm for predicting credit risk. 
