# Credit Risk Analysis
## Overview of the Loan Prediction Risk Analysis
The purpose of this analysis is to determine predictions as to whether credit card loans will be considered good or risky based on data provided by LendingClub. The determination will be backed by various sets of algorithms and machine learning tools to help gain the most accurate predictions for this dataset. 

## Results
### Naive Random Oversampling
- Balanced Accuracy Score: 0.653
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.67; Bad - 0.63; Avg/Tot - 0.67

### SMOTE Oversampling
- Balanced Accuracy Score: 0.651
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.66; Bad - 0.64; Avg/Tot - 0.66

### Cluster Centroids Undersampling
- Balanced Accuracy Score: 0.529
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.45; Bad - 0.61; Avg/Tot - 0.45

### SMOTEENN Combination (Over and Under) Sampling
- Balanced Accuracy Score: 0.643
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.60; Bad - 0.69; Avg/Tot - 0.60

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.672
- Precision: Good - 1.00; Bad - 0.73; Avg/Tot - 1.00
- Recall: Good - 1.00; Bad - 0.34; Avg/Tot - 1.00

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.925
- Precision: Good - 1.00; Bad - 0.07; Avg/Tot - 0.99
- Recall: Good - 0.94; Bad - 0.91; Avg/Tot - 0.94

## Summary 
