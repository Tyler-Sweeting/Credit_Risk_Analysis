# Credit_Risk_Analysis

### Overview of the Analysis
During this module, we have been working on our skills in data preparation, statistical reasoning, and machine learning. For this challenge, we will apply machine learning to solve a real-world challenge: credit card risk.
We are given a credit card credit dataset from LendingClub, a peer-to-peer lending services company. With this dataset we will need to need to employ different techniques to train and evaluate models with unbalanced classes.
We will do this with the use of imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Results

#### Naive Random Oversampling
* Balanced Accuracy Score - 62.9%
<img width="312" alt="NRO_BAR" src="https://user-images.githubusercontent.com/118485409/230944973-805300a8-1bc4-451e-b328-b9e2862bcb30.png">

* Imbalanced Classification Report
<img width="537" alt="NRO_PRR" src="https://user-images.githubusercontent.com/118485409/230944992-2536fa72-1199-43d8-9b01-d872a65e3f5d.png">

#### SMOTE Oversampling
* Balanced Accuracy Score - 62.8%
<img width="311" alt="SMOTE_BAR" src="https://user-images.githubusercontent.com/118485409/230945013-afdcce51-a08a-4238-a827-2876b906fa09.png">

* Imbalanced Classification Report
<img width="554" alt="SMOTE_PRR" src="https://user-images.githubusercontent.com/118485409/230945026-cbba42be-e32e-4483-9f30-52f5e88ea605.png">

#### Undersampling
* Balanced Accuracy Score - 51.0%
<img width="320" alt="UNDR_BAR" src="https://user-images.githubusercontent.com/118485409/230945053-257682cf-39f8-45fc-a68a-682322ea776b.png">

* Imbalanced Classification Report
<img width="536" alt="UNDR_PRR" src="https://user-images.githubusercontent.com/118485409/230945074-b6aff0e2-c67b-455a-a0a3-7f166ab30b2d.png">

#### Combination (Over and Under) Sampling
* Balanced Accuracy Score - 62.0%
<img width="306" alt="OU_BAR" src="https://user-images.githubusercontent.com/118485409/230945097-416a26f5-9f68-4498-9f5e-034d97dc7fad.png">

* Imbalanced Classification Report
<img width="553" alt="OU_PRR" src="https://user-images.githubusercontent.com/118485409/230945109-8eb81917-63d8-412d-82c2-d57e9a592f33.png">

#### Balanced Random Forest Classifier
* Balanced Accuracy Score - 82.5%
<img width="299" alt="BRFC_BAR" src="https://user-images.githubusercontent.com/118485409/230945124-7522da43-1580-4f45-8b68-a2e9cf70fc2a.png">

* Imbalanced Classification Report
<img width="522" alt="BRFC_PRR" src="https://user-images.githubusercontent.com/118485409/230945132-3b2876de-3217-4a70-b2ef-f471607f3588.png">

#### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score - 92.6%
<img width="322" alt="EEAC_BAR" src="https://user-images.githubusercontent.com/118485409/230945139-357c11e9-bf30-4b35-a284-093d8c3de202.png">

* Imbalanced Classification Report
<img width="529" alt="EEAC_PRR" src="https://user-images.githubusercontent.com/118485409/230945155-cd227569-61c0-4d0a-8e3c-471563400b20.png">


### Summary 

From our results, it is clear that the Easy Ensemble AdaBoost Classifier is the best choice to use among all of the models tested, it scored the highest Balanced Accuracy Score with 92.6%, and was able to correctly classify more high and low risk loans than the other models tested.
Unfortunately, even though it was the best model it was still not able to accurately predict high-risk loans. Since predicting high-risk loans is an important pard of credit risk, it is unlikely that any of these models will be sufficient. 

To correect this, we would have to dig for more data that can improve the accuracy of our models to make one of them more percise and the best model to use.
