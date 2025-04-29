# ElevateLabs-task4
# Logistic Regression Binary Classification - Breast Cancer Detection
# Overview
This project implements a Logistic Regression model to classify tumors as malignant or benign using the Breast Cancer Wisconsin dataset. It follows a full machine learning pipeline, including data preprocessing, model training, evaluation, and threshold tuning.

# Steps Performed
1. Dataset Selection: Used a binary classification dataset with a target variable diagnosis (M for malignant, B for benign).
2. Data Preprocessing
   -Dropped irrelevant columns (id, Unnamed: 32).
   -Encoded the target variable using LabelEncoder.
   -Performed train-test split (80% training, 20% testing).
   -Standardized features using StandardScaler.
3. Model Building: Trained a Logistic Regression model using sklearn.
4. Model Evaluation
  --Evaluated using:
    (i)Confusion Matrix
    (ii)Precision
    (iii)Recall
    (iv)ROC-AUC Score
  --Plotted the ROC Curve for visual performance analysis.
5. Threshold Tuning & Sigmoid Explanation
  --Manually tuned the classification threshold (e.g., 0.5).
  --Explained the sigmoid function, which maps outputs to probabilities:
     sigmoid(𝑧)=1/1+𝑒^−𝑧
 
# Key Results
  -Precision: 97.6%
  -Recall: 95.3%
  -ROC-AUC: High, indicating excellent classification performance

# Requirements
  -Python 3.x
  -pandas, numpy, matplotlib
  -scikit-learn
