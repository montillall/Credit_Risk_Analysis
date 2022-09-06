# Credit_Risk_Analysis

## Overview 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, it is necessary to employ different techniques to train and evaluate models with unbalanced classes. In order to do this analysis, it has been requested to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the analysis will include oversampling the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate the performance of these models to recommend on whether they should be used to predict credit risk.

## Results
The results of the 6 machine learning models are described as follows:

### Naive Random Ovesampling

![](Resources/Naive_Random_Oversampling.png)

* Balanced Accuracy Score: 62.4%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 57% and for low risk loans at 67%  

### SMOTE Oversampling

![](Resources/SMOTE_Oversampling.png)

* Balanced Accuracy Score: 65%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 64% and for low risk loans at 65%

### Undersampling

![](Resources/Undersampling.png)

* Balanced Accuracy Score: 65%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 61% and for low risk loans at 45%


### Combination (Over and Under) Sampling

![](Resources/Combination_(Over_and_Under)_Sampling.png)

* Balanced Accuracy Score: 64%
* Precision: for high risk loans, the precision is low at 1% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 70% and for low risk loans at 57%


### Balanced Random Forest Classifier

![](Resources/BalancedRandomForestClass.png)

* Balanced Accuracy Score: 79%
* Precision: for high risk loans, the precision is low at 4% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 67% and for low risk loans at 91%


### Easy Ensemble AdaBoost Classifier

![](Resources/EasyEnsembleClass.png)

* Balanced Accuracy Score: 93%
* Precision: for high risk loans, the precision is low at 7% and high for low risk loans at 100%
* Recall: for high risk loans, the recall is 91% and for low risk loans at 94%
















