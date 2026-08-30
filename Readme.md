# Customer Churn Prediction using ANN

## Overview

This project uses an Artificial Neural Network (ANN) to predict whether a customer is likely to leave a bank based on their demographic and banking information.

## Dataset

The project uses the Churn Modelling dataset, which contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

The target variable is **Exited**, where:
- `0` → Customer stayed
- `1` → Customer exited

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib

## Model

An Artificial Neural Network was built using TensorFlow/Keras.

The basic architecture consists of:

- Input layer
- Hidden layer with 3 neurons and sigmoid activation
- Output layer with 1 neuron and sigmoid activation

## Model Training

The model was trained using:

- Loss function: Binary Cross-Entropy
- Optimizer: Adam
- Validation split: 20%

## Evaluation

The trained model was evaluated on the test dataset using classification accuracy.

## Files

- `10_customer_churn_prediction.ipynb` — Jupyter Notebook containing the complete implementation
- `Churn_Modelling.csv` — Dataset used for the project
- `README.md` — Project documentation