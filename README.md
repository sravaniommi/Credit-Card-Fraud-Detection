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


How to Run the Project
Option 1: Google Colab
Open the .ipynb file in Google Colab and run the cells sequentially.

Option 2: Jupyter Notebook
Install the required libraries:

pip install -r requirements.txt

Then open the notebook:

jupyter notebook

Open:
credit_card_fraud_detection.ipynb
and run the cells.

Machine Learning Models
1. Logistic Regression

Logistic Regression is used as the baseline classification model.

It predicts the probability that a transaction belongs to one of the two classes:

0 → Legitimate
1 → Fraudulent
2. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions.

It is used to capture more complex relationships in the transaction data and is compared with Logistic Regression.


Conclusion

This project demonstrates how machine learning can be applied to credit card fraud detection.

Logistic Regression provides a simple baseline classification model, while Random Forest provides a more flexible ensemble-based approach.

The models are evaluated using multiple metrics to understand their ability to identify fraudulent transactions.


