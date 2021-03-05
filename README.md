# Credit Risk Analysis

## Overview of the analysis
The purpose of this analysis was to create machine learning models to predict credit card risk and evaluate the performance of these models to demonstrate if they are they should be used to predict credit.


## Results

### RandomUnderSampler

<img width="665" alt="Screen Shot 2021-03-05 at 9 21 31 AM" src="https://user-images.githubusercontent.com/72036895/110143421-7bc3e680-7d94-11eb-9f94-216db0f33f9d.png">

<img width="840" alt="Screen Shot 2021-03-05 at 9 21 37 AM" src="https://user-images.githubusercontent.com/72036895/110143489-89796c00-7d94-11eb-8855-16def4b74cc1.png">


The balance accurancy score is 59% with the high risk precision at 1% with a 61% sensitivity leading to a F1 at 1%. Because the low_risk category has such a high number the precision is 100% with 57% sensitivity.

### SMOTE

<img width="444" alt="Screen Shot 2021-03-05 at 9 25 20 AM" src="https://user-images.githubusercontent.com/72036895/110143697-bcbbfb00-7d94-11eb-9f26-01dad4369de0.png">

<img width="735" alt="Screen Shot 2021-03-05 at 9 25 26 AM" src="https://user-images.githubusercontent.com/72036895/110143766-d52c1580-7d94-11eb-992f-edce1c6aff68.png">

The balance accurancy score is 65% with the high risk precision at 1% with a 64% sensitivity leading to a F1 at 2%. Because the low_risk category has such a high number the precision is 100% with 66% sensitivity.

### ClusterCentroids resampler

<img width="501" alt="Screen Shot 2021-03-05 at 9 27 04 AM" src="https://user-images.githubusercontent.com/72036895/110143892-f987f200-7d94-11eb-8c43-66d7e65a7cee.png">

<img width="764" alt="Screen Shot 2021-03-05 at 9 27 10 AM" src="https://user-images.githubusercontent.com/72036895/110143916-00af0000-7d95-11eb-8481-0edc3a9987eb.png">

The balance accurancy score is 65% with the high risk precision at 1% with a 61% sensitivity leading to a F1 at 1%. Because the low_risk category has such a high number the precision is 100% with 45% sensitivity.

### SMOTEENN

<img width="497" alt="Screen Shot 2021-03-05 at 9 27 57 AM" src="https://user-images.githubusercontent.com/72036895/110144032-1de3ce80-7d95-11eb-9bfb-c11e22cb2216.png">

<img width="768" alt="Screen Shot 2021-03-05 at 9 28 10 AM" src="https://user-images.githubusercontent.com/72036895/110144057-250adc80-7d95-11eb-9f20-f521629bcca5.png">

### BalancedRandomForestClassifier

<img width="402" alt="Screen Shot 2021-03-05 at 9 29 26 AM" src="https://user-images.githubusercontent.com/72036895/110144331-75823a00-7d95-11eb-97b1-dd1635564ea9.png">

<img width="762" alt="Screen Shot 2021-03-05 at 9 30 24 AM" src="https://user-images.githubusercontent.com/72036895/110144356-7c10b180-7d95-11eb-84a5-e34e599bdac7.png">

### EasyEnsembleClassifier

<img width="445" alt="Screen Shot 2021-03-05 at 9 32 19 AM" src="https://user-images.githubusercontent.com/72036895/110144569-b7ab7b80-7d95-11eb-9897-d3b120d4e201.png">

<img width="740" alt="Screen Shot 2021-03-05 at 9 32 26 AM" src="https://user-images.githubusercontent.com/72036895/110144602-c09c4d00-7d95-11eb-9a91-7424202abf6b.png">


## Summary
