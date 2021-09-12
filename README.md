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

The results for all six machine learning algorithms are shown below with their outputs supported with images:


 | ML Model | Balanced Accuracy Score | Precision | Recall | F1 |
 | --- | --- | --- | --- | --- |
 | Naive Random Oversampling | 0.65 | 0.99 | 0.68 | 0.80 |
 | SMOTE Oversampling | 0.64 | 0.99 | 0.66 | 0.79 |
 | Cluster Centroid Undersampling | 0.53 | 0.99 | 0.45 | 0.62 | 
 | SMOTEENN Combination Sampling | 0.64 | 0.99 | 0.57 | 0.73 |
 | Balanced Random Forest Classifier | 0.79 | 0.99 | 0.91 | 0.95 |
 | Easy Ensemble AdaBoost Classifier | 0.93 | 0.99 | 0.94 | 0.97 |
 
- Naive Random Oversampling:

<img width="820" alt="Naive_Random_Oversampling" src="https://user-images.githubusercontent.com/83378141/132993649-db533526-37da-4445-a903-3b2f652d2c90.png">

- SMOTE Oversampling:

<img width="821" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/83378141/132993662-f9666b02-f651-41ee-99eb-02eec00f86cb.png">

- Cluster Centroid Undersampling: 

<img width="673" alt="ClusterCentroids_Undersampling" src="https://user-images.githubusercontent.com/83378141/132993683-7c683f94-d8d2-4889-b446-2285cf4d084b.png">

- SMOTEENN Combination Sampling: 

<img width="655" alt="SMOTEENN_Comb_Sampling" src="https://user-images.githubusercontent.com/83378141/132993709-e73069fa-125d-4992-8451-f8fdbf19378d.png">

- Balanced Random Forest Classifier: 

<img width="805" alt="Random_Forest_Classifier" src="https://user-images.githubusercontent.com/83378141/132993725-a58c2e11-381e-47c9-a66f-3297b0cd5ba2.png">

- Easy Ensemble AdaBoost Classifier:

<img width="811" alt="Easy_Ensemble_AdaBoost" src="https://user-images.githubusercontent.com/83378141/132993735-911adaa7-684f-455e-a6d2-5536ea492303.png">


## Summary

In the financial industry, precision is more valuable than sensitivity (recall) for analyzing risk and default rates on loan candidates. Nevertheless, all six algorithms had a really low precision rate for high risk individuals, that is the measurement we are trying to increase the most. The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low for finding these high risk individuals not to give loans to. On the other hand, all the models had a perfect precision for low-risk individiauls meaning that all of the low-risk customers were given loans. 

Having this in mind, precision is not telling us much information to compare the algorithms, so we should take a look at sensitivity. 

