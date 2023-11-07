# Churn-Predict
Churn-Predict - Customer Churn Prediction using ANN
## Overview

Churn-Predict is aimed at predicting customer churn in a telecommunications company using an Artificial Neural Network (ANN). Churn prediction is a critical task for businesses to understand and reduce customer attrition. The ANN model is built using Keras with TensorFlow backend and utilizes various data preprocessing techniques to achieve this goal.

### Data
The dataset used for this project is from a telecommunications company and contains customer information, including features like tenure, monthly charges, total charges, and customer demographics. The target variable is whether a customer churned or not (Churn: Yes/No).

### Data Preprocessing

- Handling missing values in the 'TotalCharges' column.
- Encoding categorical variables to numeric using one-hot encoding and ordinal encoding.
- Scaling numerical features using Min-Max scaling.
- Splitting the data into training and testing sets.

### Neural Network Architecture

The neural network architecture used in this project consists of:
- An input layer with 26 neurons corresponding to the 26 input features.
- A hidden layer with 20 neurons and ReLU activation.
- Another hidden layer with 15 neurons and ReLU activation.
- An output layer with a single neuron and sigmoid activation for binary classification.

### Model Training

The model is trained using the Adam optimizer and binary cross-entropy loss function. It's trained for 100 epochs on the training data.

### Model Evaluation

Model evaluation is performed on the test dataset, and the following metrics are calculated:
- Accuracy
- Confusion Matrix
- Classification Report

### Creator
Gideon Ogunbanjo

