# Credit_Risk_Analysis
#### *Utilized several machine learning models to predict credit risk using Python's imbalanced-learn and scikit-learn libraries*

## Supervised Machine Learning: Overview of the analysis

The objective of this project was to use machine learning models to analyze credit risk to provide a quicker and more reliable loan experience. Using these models, I was able to accurately identify good candidates for loans which could help a financial institution decrease their default rate on their loans. I was able to build and evaluate several machine learning algorithms to predict credit risk. 

## Resources
- Dataset: 
  - LoanStats_2019Q1.csv

- Software used:
  - Python
  - Jupyter Notebook
  - NumPy, scikit-learn, and imbalanced-learn libraries
  - Logistic Regression and Random Forest models
  - Ensemble and resampling techinques

## Results

The results for all six machine learning algorithms are shown below:


 | ML Model | Balanced Accuracy Score | Precision | Recall | F1 |
 | --- | --- | --- | --- | --- |
 | Naive Random Oversampling | 0.65 | 0.99 | 0.68 | 0.80 |
 | SMOTE Oversampling | 0.64 | 0.99 | 0.66 | 0.79 |
 | Cluster Centroid Undersampling | 0.53 | 0.99 | 0.45 | 0.62 | 
 | SMOTEENN Combination Sampling | 0.64 | 0.99 | 0.57 | 0.73 |
 | Balanced Random Forest Classifier | 0.79 | 0.99 | 0.91 | 0.95 |
 | Easy Ensemble AdaBoost Classifier | 0.93 | 0.99 | 0.94 | 0.97 |
 


## Summary



