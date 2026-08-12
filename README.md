# Credit-Card-Fraud-Detection

##  Project Overview

Credit card fraud detection is a machine learning classification problem where the goal is to identify whether a credit card transaction is legitimate or fraudulent.

In this project, machine learning models are trained to classify transactions into two categories:

- `0` → Legitimate Transaction
- `1` → Fraudulent Transaction

The dataset is highly imbalanced because legitimate transactions are much more common than fraudulent transactions. To address this problem, under-sampling is used to create a balanced dataset for model training.

Two machine learning models are implemented and compared:

1. Logistic Regression
2. Random Forest Classifier


## Objectives

The main objectives of this project are:

- Analyze the credit card transaction dataset
- Understand the distribution of legitimate and fraudulent transactions
- Check for missing values
- Handle the class imbalance problem
- Split the data into training and testing sets
- Train a Logistic Regression model
- Train a Random Forest model
- Evaluate both models
- Compare their performance using different evaluation metrics


## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## Dataset 

The project uses a credit card transaction dataset containing transactions classified as legitimate or fraudulent.

The target column is:

```text
Class


