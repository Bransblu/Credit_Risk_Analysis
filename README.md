# Credit Risk Analysis

## Overview

The purpose of this analysis is to utilize **imbalanced-learn** and **scikit-learn** libraries to evaluate unbalanced meodels to determine underlying credit risk. The different models will have varying levels of precision and accuracy. 

First, models will be resampled to predict credit risk. Second, SMOTEENN algorithm will be used to predict credit risk. Lastly, ensemble classifiers were used to predict credit risk. 

Tools: Python, Jupyter Notebook
Libraries: Pandas, Numpy, Pathlib, scikit-learn, imbalanced-learn

## Results

### Naive Random Oversampling

- Balanced Accuracy Score: 0.65
- High-Risk Precision: 1%
- High-Risk Recall: 63%

High-risk precision is almost 1% and recall is 66%. This is due to such a large population size vs. High-Risk.

### SMOTE 

- Balanced Accuracy Score: 0.62
- High-Risk Precision: 1%
- High-Risk Recall: 62%

Similar results to Naive Random Oversampling, High-risk precision is almost 1% and recall is 63%. This is due to such a large population size vs. High-Risk.

### ClusterCentroids 

- Balanced Accuracy Score: 0.52
- High-Risk Precision: 1%
- High-Risk Recall: 61%

High-risk precision is almost 1% and recall is 43%. 

### SMOTEENN 

- Balanced Accuracy Score: 0.64
- High-Risk Precision: 1%
- High-Risk Recall: 70%

High-risk precision of 1% and recall is 70%. 

### BalancedRandomForestClassifier

- Balanced Accuracy Score: 0.79
- High-Risk Precision: 3%
- High-Risk Recall: 70%

Different from the earlier models, the low-risk recall is 87%.

### EasyEnsembleClassifier

- Balanced Accuracy Score: 0.93
- High-Risk Precision: 9%
- High-Risk Recall: 92%

Low-risk recall is 94%, meaning a higher low-risk accuracy. 


## Summary
