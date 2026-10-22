# Data and Machine Learning - Group 11

This repository contains the practical work for the Data and Machine Learning course at Universidade do Minho, authored by Augusto Campos, Carlos Silva, Tiago Silva, and Tiago P. Silva. The project investigates the relevance of radiomic features in predicting the progression of Mild Cognitive Impairment (MCI) to Alzheimer's Disease (AD).

## Project Tasks
### Analysis and Validation:
We analyzed the DShippo (hippocampus) and DSocc (occipital lobe) datasets. Testing baseline models including Logistic Regression, Decision Trees, Lasso, and XGBoost demonstrated that the hippocampus plays a fundamental role in Alzheimer's prediction compared to the occipital lobe.   

### Kaggle Competition:
We iteratively developed and optimized machine learning models to maximize the macro F1-score on the DShippo dataset.

## Methodology & Top Results
### Data Processing: 
To handle the high dimensionality of 305 observations against 2181 features, we removed non-numeric data and applied feature selection techniques including variance thresholds, correlation filters, LASSO, Recursive Feature Elimination (RFE), and PCA.
### Model Evaluation:
We tested various algorithms including Multilayer Perceptron, Logistic Regression, XGBoost, and KNN.
### Best Performance:
Our highest private Kaggle score of 0.38075 was achieved using a K-Nearest Neighbors (KNN) model configured with Manhattan distance, combined with variance and correlation feature selection.   
