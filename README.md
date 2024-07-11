# Credit Card Fraud Detection Project (Task-1) 

This project implements machine learning models to detect fraudulent credit card transactions.

## Overview

The project uses a dataset of credit card transactions and applies various data analysis and machine learning techniques to identify potentially fraudulent activity. Key components include:

- Data loading and exploration
- Visualization of transaction patterns 
- Sampling to handle class imbalance
- Model training using Isolation Forest and Local Outlier Factor
- Evaluation of model performance

## Data

The dataset contains credit card transactions with the following features:
- Time: Seconds elapsed between transactions
- V1-V28: Principal components from PCA transformation (anonymized features)
- Amount: Transaction amount
- Class: 1 for fraudulent transactions, 0 for normal

## Key Findings

- The dataset is highly imbalanced, with only 492 fraudulent transactions out of 284,807 total
- Isolation Forest achieved 99.74% accuracy 
- Local Outlier Factor achieved 99.66% accuracy
- Both models showed high precision in detecting normal transactions, but lower recall for fraudulent ones

## Usage

The main analysis is contained in a Jupyter notebook. To run:

1. Install required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
2. Run the Jupyter notebook

## Future Work

- Try other anomaly detection algorithms
- Experiment with different sampling techniques
- Incorporate additional features if available
- Deploy model as a real-time fraud detection system

## Author

Shubham Chaurasia
