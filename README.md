# Credit Risk Analysis

## Overview 

### Objective

Use the credit card credit dataset from LendingClub, a peer-to-peer lending services company, and apply machine learning to assess credit card risk. 

### Method 

Use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling:

- Oversampling: RandomOverSampler and SMOTE algorithms 

- Undersampling: ClusterCentroids algorithm 

- Combinatorial approach of over- and undersampling: SMOTEENN algorithm 

- Reducing bias: BalancedRandomForestClassifier and EasyEnsembleClassifier 

## Code

- credit_risk_resampling.ipynb [file](credit_risk_resampling.ipynb)

- credit_risk_ensemble.ipynb [file](credit_risk_ensemble.ipynb)


## Deliverables

- Deliverable 1: Use Resampling Models to Predict Credit Risk
 
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

- Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

## Results

Random Over Sampler

![RandomOverSampler](https://user-images.githubusercontent.com/98564776/170832669-802d8eae-7726-45d2-9b05-3ebed5cc272e.PNG)

SMOTE Oversampling

![SMOTEOversampling](https://user-images.githubusercontent.com/98564776/170832684-c4f6ec40-d080-4660-8f7c-b474cccdb77b.PNG)

Cluster Centroids

![ClusterCentroids](https://user-images.githubusercontent.com/98564776/170832703-7b3a5664-a824-4999-947f-1344a0709944.PNG)

Combination Over and Under

![CombinationOver_and_Under](https://user-images.githubusercontent.com/98564776/170832715-555246aa-92f3-4c74-b0a5-bf3d12b35cae.PNG)

Balanced Random Forest Classifier

![BalancedRandomForestClassifier](https://user-images.githubusercontent.com/98564776/170832734-49a9c943-319c-4ad3-a63f-b6dcb9472b6e.PNG)

Easy Ensemble Classifier 

![EasyEnsembleClassifier ](https://user-images.githubusercontent.com/98564776/170832761-13830074-c363-4eac-838c-df1370914cd9.PNG)


## Summary: 

With over 93% balanced accuarcy, the Easy Ensemble Classifier is the best method to use to assess the credit risk.
