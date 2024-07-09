# Gaussian Mixture Model for Anomaly Detection and Performance Evaluation
## Overview
This project implements an anomaly detection system using a Gaussian Mixture Model (GMM) to identify unusual data points in a dataset. The system is evaluated using various performance metrics such as Area Under the Curve (AUC), Precision, Recall, and F1 Score on both validation and test datasets. The primary goal is to distinguish between normal and anomalous data points effectively.

## Project Structure
- Data Preparation: The dataset is split into training, validation, and test sets. Features are selected based on their importance.
- Model Training: A GMM is trained on the subset of the training data where the target label is 0 (assumed to be normal data points).
- Model Evaluation: The trained model is evaluated on the validation set to optimize classification thresholds and on the test set to report final performance metrics.

## Dependencies
- Python 3.6+
- numpy
- pandas
- scikit-learn

## Conclusion
This project provides a framework for anomaly detection using Gaussian Mixture Models, emphasizing the importance of robust performance evaluation using multiple metrics. By following the steps outlined, you can adapt this approach to various datasets and applications.
