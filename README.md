Overview

This project demonstrates how supervised and unsupervised machine learning techniques can be combined to analyze behavioural data, predict outcomes, classify risk, and detect anomalies.
The system models normal behavioural patterns, identifies deviations, and segments users into meaningful groups.

Objectives

Predict expected behavioural outcomes (Regression)
Classify observations into risk categories (Classification)
Detect abnormal behaviour using deviation scoring
Discover hidden behavioural segments (Clustering)

Techniques Used

*Supervised Learning
KNN Regressor – Behaviour prediction
Logistic Regression – Risk classification

*Unsupervised Learning
KMeans Clustering – Behavioural segmentation

*Evaluation Metrics
R² Score
Mean Squared Error (MSE)
Accuracy
Precision, Recall, F1-score

Workflow

Data loading and preprocessing
Encoding categorical variables
Feature scaling (Standardization)
Train–test split
Model training and comparison
Anomaly score calculation
Cluster-based behavioural segmentation

Key Results

KNN Regression achieved moderate predictive performance (R² ≈ 0.41)
Logistic Regression achieved ~71% classification accuracy
Anomaly detection identified high-deviation behavioural cases
KMeans revealed 5 distinct behavioural segments

Key Concepts Covered

Supervised vs Unsupervised Learning
Feature Scaling
Overfitting and Model Comparison
Probability-based Risk Scoring
Data Leakage Awareness

Applications
*This framework can be extended to:

Financial risk modeling
Fraud detection
Customer behaviour analytics
Anomaly detection systems

Tech Stack

Python
Pandas
Scikit-learn
NumPy
Matplotlib
