## Credit Card Fraud Detection Using Gaussian Mixture Models
This project aims to detect fraudulent transactions in a credit card dataset using Gaussian Mixture Models (GMM). The dataset used in this project contains anonymized credit card transactions labeled as fraudulent or legitimate.

# Project Overview
Credit card fraud is a significant issue for financial institutions and consumers. Detecting fraudulent transactions quickly and accurately is crucial for minimizing economic losses and protecting consumers. In this project, we employ a machine learning approach using Gaussian Mixture Models to identify fraudulent transactions.

# Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset, which includes the following features:

- Time: The time elapsed between this transaction and the first transaction in the dataset.
- V1 to V28: The result of a PCA transformation to protect sensitive information about the customers.
- Amount: The transaction amount.
- Class: The label for the transaction, where 0 indicates a legitimate transaction and 1 indicates a fraudulent transaction.

You can download this dataset from here
- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud 

## Project Structure
- Data Preparation: The dataset is split into training, validation, and test sets. Features are selected based on their importance.
- Model Training: A GMM is trained on the subset of the training data where the target label is 0 (assumed to be normal data points).
- Model Evaluation: The trained model is evaluated on the validation set to optimize classification thresholds and on the test set to report final performance metrics.

## Model Used 
Gaussian Mixture Model (GMM)

## Dependencies
- Python 3.6+
- numpy
- pandas
- scikit-learn

## Conclusion
This project demonstrates using Gaussian Mixture Models to detect credit card fraud. The results highlight the importance of feature selection and model evaluation using appropriate metrics. By leveraging unsupervised learning techniques, we can effectively identify fraudulent transactions, contributing to enhanced financial security.
