# Credit Risk Analysis


## Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

imbalanced-learn
scikit-learn
RandomOverSampler
SMOTE algorithms
ClusterCentroids algorithm
SMOTEENN algorithm
BalancedRandomForestClassifier (bias reduction model)
EasyEnsembleClassifier (bias reduction model)


## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

Naive Random Oversampling
! [Pic 1](https://github.com/fouadZiaa/Credit_Risk_Analysis/blob/5ea19c95083f096c624c980a9764db242e156dfc/Images/Pic%201.png)

Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67
SMOTE Oversampling
Pic 2

Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .62/.64
Undersampling
Pic 3

Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .63/.40
Combination Under-Over Sampling
Pic 4

Balanced Accuracy: 0.5173713090878325
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .70/.57
Balanced Random Forest Classifier
Pic 5

Balanced Accuracy: 0.7877672625306695
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .67/.91
Easy Ensemble AdaBoost Classifier
Pic 6

Balanced Accuracy: 0.925427358175101
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .91/.94
Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
