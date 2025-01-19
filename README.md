# Haematological Toxicity Prediction Model for Clinical Trial Patients
Project Overview
This project implements machine learning models to predict haematological toxicity in patients undergoing medical treatment. The analysis uses a comprehensive dataset of patient records, treatment cycles, and various clinical parameters to build predictive models.

### Features

Multiple machine learning models comparison (Decision Trees, Random Forest, XGBoost, Histogram-based Gradient Boosting, KNN)
Treatment cycle-specific predictions
Extensive data preprocessing pipeline
Performance evaluation across different metrics (ROC-AUC, Accuracy, F1-Score)

### Data Preprocessing
The preprocessing pipeline includes several key steps:

### Data Splitting
Separation of baseline and treatment data
Creation of cycle-specific datasets

### Data Cleaning
Removal of columns with >80% missing values
Outlier detection and handling using IQR method
Missing value imputation using KNN with k=3


# Models and Performance
Five different models were evaluated:

### Decision Tree
Best performance in cycle 0 (97% accuracy)
Consistent performance across later cycles (60-76% accuracy)


### Random Forest
Highest overall performance
Peak accuracy of 98.7% in cycle 0
Maintained 65-85% accuracy in later cycles


### XGBoost
Strong initial performance (98.3% accuracy in cycle 0)
Stable performance in later cycles (64-85% accuracy)


### Histogram-based Gradient Boosting
Comparable performance to XGBoost
Best accuracy of 98.3% in cycle 0
Maintained 63-85% accuracy across cycles


### KNN
Lower performance compared to tree-based models
Accuracy range of 52-95% across cycles
