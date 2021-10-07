# Credit Risk Analysis
## Overview of the Loan Prediction Risk Analysis
The purpose of this analysis is to determine predictions as to whether credit card loans will be considered good or risky based on data provided by LendingClub. The determination will be backed by various sets of algorithms and machine learning tools to help gain the most accurate predictions for this dataset. 

## Results
### Naive Random Oversampling
- Balanced Accuracy Score: 0.653
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.67; Bad - 0.63; Avg/Tot - 0.67
- Full Classification Report
<img width="714" alt="Naive_OverSampling" src="https://user-images.githubusercontent.com/85330159/136442255-826f0b87-0e8b-41ab-9ef9-0c375b8d8487.png">


### SMOTE Oversampling
- Balanced Accuracy Score: 0.651
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.66; Bad - 0.64; Avg/Tot - 0.66
- Full Classification Report
<img width="708" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/85330159/136442276-b24069df-7f18-403e-9841-5ddd36fe7511.png">


### Cluster Centroids Undersampling
- Balanced Accuracy Score: 0.529
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.45; Bad - 0.61; Avg/Tot - 0.45
- Full Classification Report
<img width="699" alt="Undersampling" src="https://user-images.githubusercontent.com/85330159/136442294-34540fed-7033-4417-bd3d-79d3868e9c4c.png">


### SMOTEENN Combination (Over and Under) Sampling
- Balanced Accuracy Score: 0.643
- Precision: Good - 1.00; Bad - 0.01; Avg/Tot - 0.99
- Recall: Good - 0.60; Bad - 0.69; Avg/Tot - 0.60
- Full Classification Report
<img width="698" alt="SMOTEENN" src="https://user-images.githubusercontent.com/85330159/136442308-cd3d60ae-7ad1-491e-9271-744d77f66845.png">


### Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.672
- Precision: Good - 1.00; Bad - 0.73; Avg/Tot - 1.00
- Recall: Good - 1.00; Bad - 0.34; Avg/Tot - 1.00
- Full Classification Report
<img width="693" alt="RF" src="https://user-images.githubusercontent.com/85330159/136442324-76e68d7f-8dd3-4a8d-a96c-052d349e5d1c.png">


### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 0.925
- Precision: Good - 1.00; Bad - 0.07; Avg/Tot - 0.99
- Recall: Good - 0.94; Bad - 0.91; Avg/Tot - 0.94
- Full Classification Report
<img width="696" alt="EE" src="https://user-images.githubusercontent.com/85330159/136442338-09fb24ab-2e56-4d6e-a3be-7f07760bc8a9.png">


## Summary 
