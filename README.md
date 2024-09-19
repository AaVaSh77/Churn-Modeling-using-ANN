# Customer Churn Prediction Using Artificial Neural Network (ANN)

This project demonstrates the use of an Artificial Neural Network (ANN) to predict customer churn using the `Churn_Modelling.csv` dataset.

## Dataset

The dataset `Churn_Modelling.csv` contains information about customers of a bank, including:

- **RowNumber**: The row number.
- **CustomerId**: The unique ID of the customer.
- **Surname**: The surname of the customer.
- **CreditScore**: The credit score of the customer.
- **Geography**: The country of the customer.
- **Gender**: The gender of the customer.
- **Age**: The age of the customer.
- **Tenure**: The number of years the customer has been with the bank.
- **Balance**: The balance of the customer.
- **NumOfProducts**: The number of products the customer has with the bank.
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary**: The estimated salary of the customer.
- **Exited**: Whether the customer has left the bank (1 = Yes, 0 = No).

## Implementation Steps

### 1. Data Preprocessing
- Importing libraries and dataset.
- Encoding categorical variables.
- Splitting the dataset into the training set and test set.
- Feature scaling.

### 2. Building the ANN
- Initializing the ANN.
- Adding input layer and first hidden layer.
- Adding second hidden layer.
- Adding the output layer.
- Compiling the ANN.

### 3. Training the ANN
- Training the ANN on the training set.

### 4. Making Predictions and Evaluating the Model
- Predicting the test set results.
- Making the Confusion Matrix.
- Evaluating the model performance.
