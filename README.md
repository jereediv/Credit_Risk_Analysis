# Credit_Risk_Analysis

## Overview of the analysis:
Using a credit card dataset from LendingClub, we will use oversampling and undersampling to assess credit risk.

## Results:
Using the scikit-learn and imblearn libraries we were able to calculate the following precision and recall scores for 6 machine learning models:

- Using BalancedRandomForestClassifier from imblearn.ensemble:
	- Balanced accuracy score :  77% - https://github.com/jereediv/Credit_Risk_Analysis/blob/main/BalancedAccuracyScore.png?raw=true
	- Imbalanced classification report :  https://github.com/jereediv/Credit_Risk_Analysis/blob/main/ImbalancedClassificationReport.png?raw=true
	- Precision :  99%
	- Recall :  88%

- Using EasyEnsembleClassifier from imblearn:
	- Balanced accuracy score :  92% - https://github.com/jereediv/Credit_Risk_Analysis/blob/main/EnsBalancedAccuracyScore.png?raw=true
	- Imbalanced classification report :  https://github.com/jereediv/Credit_Risk_Analysis/blob/main/EnsImbalancedClassificationReport.png?raw=true
	- Precision :  99%
	- Recall :  94%

## Summary:
Looking at the results, it's apparent that the EasyEnsemble produced the best model. This conclussion is based on the high accuracy score and similar precision and recall scores.