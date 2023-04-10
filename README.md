# Credit_Risk_Analysis

### Overview of the Analysis
During this module, we have been working on our skills in data preparation, statistical reasoning, and machine learning. For this challenge, we will apply machine learning to solve a real-world challenge: credit card risk.
We are given a credit card credit dataset from LendingClub, a peer-to-peer lending services company. With this dataset we will need to need to employ different techniques to train and evaluate models with unbalanced classes.
We will do this with the use of imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Results

#### Naive Random Oversampling
* Balanced Accuracy Score

* Imbalanced Classification Report

#### SMOTE Oversampling
* Balanced Accuracy Score

* Imbalanced Classification Report

#### Undersampling
* Balanced Accuracy Score

* Imbalanced Classification Report

#### Combination (Over and Under) Sampling
* Balanced Accuracy Score

* Imbalanced Classification Report

#### Balanced Random Forest Classifier
* Balanced Accuracy Score

* Imbalanced Classification Report

#### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score

* Imbalanced Classification Report


### Summary 

From our results, it si clear that the Easy Ensemble AdaBoost Classifier is the best choice to use among all of the models tested. It's accuracy was the highest out of all the tests, and was able to correctly classify more high and low risk loans than the other models tested.
Unfortunately, even though it was the best model it was still not able to accurately predict high-risk loans. Since predicting high-risk loans is an important pard of credit risk, it is unlikely that any of these models will be sufficient. 

To correect this, we would have to dig for more data that can improve the accuracy of our models to make one of them more percise and the best model to use.