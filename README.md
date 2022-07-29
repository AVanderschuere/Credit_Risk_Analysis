# Credit_Risk_Analysis

---

## Overview

The purpose of this analysis is to determine credit risk using Supervised Learning. This is done by using regression and classification models.

### Models Used:
-RandomOverSampler
-SMOTE
-ClusterCentroids
-SMOTEENN
-BalancedRandomForestClassifier
-EasyEnsambleClassifier

---

## Results

---
### Oversampling

The oversampling tests performed were RandomOverSampler and SMOTE.
RandomOverSampler
  - Slightly increased recall for higher-risk loans
 SMOTE
  - Slightly higher recall for low-risk loans
  
 Overall oversampling modeling resulted in low precision for high-risk loand and high precision for low-risk loans.
 
---
### Undersampling

Undersampling resulted in inferior results using ClusterCentroids.
There was roughly a 12% difference between oversampling and undersampling.
This resulted in low precision for both high and low-risk loans.

---
### Combination

The comination testing was performed using SMOTEENN.
SMOTEENN resulted in 1% less accuracy than the Oversampling models.
The precision was similar to previous models.

---
### Ensemble Classifiers

The Ensemble Classifiers used were the BalancedRandomForestClassifier and EasyEnsembleClassifier.
BalancedRandomForestClassifier
  - Resulted in a 78.8% accuracy
EasyEnsembleClassifier
  - Resulted in a 93.1% accuracy
 
Both Ensemble Classifiers resulted in significantly more accurate results.
The precision remained fairly similar as previous models with low precision for high-risk loans and high precision for low-risk loans.
 
---

## Summary

---

All of the models resulted in low precision for high-risk loans and high precision for low-risk loans. The EasyEnsembleClassifier resulted in the best accuracy at 93.1%.

Based on all of the models results, it would not be a wise business choice to use these models as they are not able to reliably predict high-risk loans.

