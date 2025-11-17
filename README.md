Project Overview
This project implements a fraud detection system that can identify fraudulent credit card transactions with high accuracy. |
The system uses real transaction data from European cardholders and multiple machine learning algorithms to detect patterns indicative of fraud.

 Key Achievements
ROC-AUC Score: 0.9980 - Excellent discrimination power
Handled highly imbalanced data (0.172% fraud cases)
Compared multiple ML algorithms
Comprehensive business impact analysis
Production-ready model




Dataset
Source: Kaggle Credit Card Fraud Detection

Dataset Statistics:
Total Transactions: 284,807
Fraudulent Transactions: 492 (0.172%)
Features: 30 (28 PCA components + Time + Amount)
Time Range: September 2013 (2 days)


Technical Implementation
Algorithms Compared
 Random Forest Classifier
 Logistic Regression
 Gradient Boosting Classifier
 Decision Tree Classifier

Preprocessing Techniques
Class Balancing: RandomUnderSampler
Feature Scaling: RobustScaler
Train-Test Split: 80-20 with stratification
Cross-Validation: 5-fold
