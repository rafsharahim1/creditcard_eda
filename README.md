# Credit Card Fraud Detection Project

This project focuses on detecting fraudulent credit card transactions through exploratory data analysis (EDA) and machine learning techniques.

## Project Overview

The objective is to analyze a dataset containing anonymized PCA features, 'Time' (seconds elapsed since the first transaction), and 'Amount' (transaction amount), and build machine learning models to identify fraudulent transactions. The dataset includes a binary target variable 'Class', where 1 indicates fraud and 0 indicates legitimate transactions.

### Features
- **PCA Features**: V1 to V28 (anonymized due to PCA transformation).
- **Non-PCA Features**: 'Time' and 'Amount'.
- **Target Variable**: 'Class' (1 for fraud, 0 for legitimate).

## Key Steps and Findings

- Conducted EDA using Python libraries like Matplotlib and Seaborn to visualize data distributions, correlations, and temporal trends.
- Implemented machine learning models including Logistic Regression and Isolation Forest for fraud detection.
- Evaluated model performance using metrics such as precision, recall, and F1-score to assess effectiveness.
- Visualized insights through various plots and charts to understand transaction patterns and anomalies.

## Conclusion

This project demonstrates effective use of data science techniques to tackle financial fraud detection challenges. By leveraging EDA and machine learning, valuable insights were gained into transaction patterns and fraudulent behavior, contributing to enhanced security measures in financial transactions.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

