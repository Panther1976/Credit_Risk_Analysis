# Credit_Risk_Analysis

## Overview of the Loan Prediction Risk Analysis:

The purpose of this analysis is to examine credit risk through the use of several machine learning models and then determine which model best predicts credit risk.

The following represent the models and techniques that we will be utilizing, training and evaluating:

- Oversampling (Naive Random Oversampling)
- Oversampling (SMOTE Oversampling)
- Undersampling
- Combination (Over and Under) Sampling/SMOTEEN
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

The primary measurements used to assess the performance of the various models are the accuracy score, precision and recall. 

Accuracy Score: compares the actual outcome (y) values from the test set against the model's predicted values. The accuracy score is simply the percentage of predictions that are correct. 

Precision Score: also known as positive predictive value (PPV) and is obtained by dividing the number of true positives (TP) by the number of all positives.
- Precision = TP/(TP + FP)

Recall (Sensativity): is the measurement of a models ability to predict true positives.
- Sensitivity = TP/(TP + FN)

The results for each model and their scores can be found below.

## Results:

### Oversampling (Naive Random Oversampling)

![NaiveRandomOversampling](https://user-images.githubusercontent.com/106631875/199625278-bd559b9d-96df-4022-8806-a33b6cd51837.png)

Accuracy Score: 0.64
Precision Score for high risk loans: 0.01
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.63
Recall (Sensitivity) Score for low risk loans: 0.65

### SMOTE Oversampling

![SMOTEOversampling](https://user-images.githubusercontent.com/106631875/199625306-d3b65f54-38d8-4b86-b8ae-fff1c0c5b67b.png)

Accuracy Score: 0.64
Precision Score for high risk loans: 0.01
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.63
Recall (Sensitivity) Score for low risk loans: 0.65

### Undersampling

![undersampling](https://user-images.githubusercontent.com/106631875/199625358-d1f396cd-c618-48ac-aa10-35413e185283.png)

Accuracy Score: 0.51
Precision Score for high risk loans: 0.01
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.59
Recall (Sensitivity) Score for low risk loans: 0.44

### - Combination (Over and Under) Sampling/SMOTEEN

![SMOTEEN](https://user-images.githubusercontent.com/106631875/199625397-648afa7f-2b6f-475e-b0d0-6dd595b3b31b.png)

Accuracy Score: 0.63
Precision Score for high risk loans: 0.01
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.72
Recall (Sensitivity) Score for low risk loans: 0.54

### Balanced Random Forest Classifier

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/106631875/199625431-b22dfd76-b4aa-481f-bf2d-b48b81af0e94.png)

Accuracy Score: 0.78
Precision Score for high risk loans: 0.03
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.70
Recall (Sensitivity) Score for low risk loans: 0.87

### Easy Ensemble AdaBoost Classifier

![EmsembleClassifier](https://user-images.githubusercontent.com/106631875/199625453-54da583c-e7ec-430a-b717-0c766f01485e.png)

Accuracy Score: 0.93
Precision Score for high risk loans: 0.09
Precision Score for low risk loans: 1.00
Recall (Sensitivity) Score for high risk loans: 0.92
Recall (Sensitivity) Score for low risk loans: 0.94

# Summary:

All models had similar Precision Scores, which means they are all able to successfully predict low risk loans. However their other predictive scores vary with one model standing out above the rest.  

### Recommendation

While all models had similar Precision Scores, the model with the best overall scores and ability to predict credit risk is the EasyEnsembleClassifier model and would be the recommended model for assessing credit risk. Its Recall Scores were much higher for high and low risk loans. This means that this model could more accurately predict risk than any of the other models.
 
