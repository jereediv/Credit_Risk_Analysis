# Credit_Risk_Analysis

## Overview of the analysis:
Using a credit card dataset from LendingClub, we will use oversampling and undersampling to assess credit risk.

## Results:
Using the scikit-learn and imblearn libraries we were able to calculate the following precision and recall scores for 6 machine learning models:

- Using BalancedRandomForestClassifier from imblearn.ensemble:
	- Balanced accuracy score :  0.79 - https://github.com/jereediv/Credit_Risk_Analysis/blob/main/BalancedAccuracyScore.png?raw=true
	- Imbalanced classification report :  https://github.com/jereediv/Credit_Risk_Analysis/blob/main/ImbalancedClassificationReport.png?raw=true

- Using EasyEnsembleClassifier from imblearn:
	- Balanced accuracy score :  0.92 - https://github.com/jereediv/Credit_Risk_Analysis/blob/main/EnsBalancedAccuracyScore.png?raw=true
	- Imbalanced classification report :  https://github.com/jereediv/Credit_Risk_Analysis/blob/main/EnsImbalancedClassificationReport.png?raw=true

## Summary:
