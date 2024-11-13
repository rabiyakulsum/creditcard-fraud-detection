# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning. A logistic regression model is used to classify transactions as either fraudulent or legitimate. The model's accuracy is evaluated on both training and testing datasets.

## Project Overview

Credit card fraud detection is a critical challenge in financial services. This project uses machine learning to analyze credit card transaction data and predict the likelihood of fraud. By training a logistic regression model, we aim to build a robust classifier that can differentiate between fraudulent and legitimate transactions.

## Dataset

The dataset contains the following columns:

- **Class**: Binary label where `1` indicates fraud and `0` indicates a legitimate transaction.
- **Amount**: Transaction amount.
- **Time**: Time elapsed between this transaction and the first transaction in the dataset.
- **V1 to V28**: Anonymized features derived from PCA transformation of the original transaction details.

## Project Structure

- `notebooks/`: Jupyter notebooks containing the model development and analysis.
- `data/`: Folder for the dataset 

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook


