# ANN-Churn-Modeling
Churn Modeling using Artificial Neural Networks (ANN)

## 📁 Project Overview

This project aims to predict customer churn using an Artificial Neural Network (ANN). Customer churn refers to when customers stop using a product or service, and predicting it accurately can help businesses retain valuable customers, optimize marketing strategies, and improve overall profitability.

## 📊 Problem Statement

Given customer data, our objective is to predict whether a customer is likely to churn or not. This is a binary classification problem where 1 indicates a churn and 0 indicates retention.

## 🔧 Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow, Keras, imblearn

Modeling: Artificial Neural Network (ANN)

Deployment: Streamlit

## 📁 Dataset

The dataset contains the following features:

RowNumber: Index of the customer in the dataset

CustomerId: Unique identifier for each customer

Surname: Last name of the customer

CreditScore: Credit score of the customer

Geography: Country of the customer

Gender: Male or Female

Age: Age of the customer

Tenure: Number of years the customer has been with the company

Balance: Account balance

NumOfProducts: Number of products held by the customer

HasCrCard: Whether the customer has a credit card (1 = Yes, 0 = No)

IsActiveMember: Whether the customer is an active member (1 = Yes, 0 = No)

EstimatedSalary: Estimated salary of the customer

Exited: Target variable (1 = Churn, 0 = Retained)

## ⚙️ Project Workflow

### Data Preprocessing:

Handling missing values

Encoding categorical variables

Feature scaling

### Exploratory Data Analysis (EDA):

Analyzing correlations

Visualizing distributions

### Model Building:

Designing an ANN architecture

Compiling the model (Optimizer: Adam, Loss: Binary Cross-Entropy)

Training and validation

### Model Evaluation:

Accuracy, Precision, Recall, F1-Score

Confusion Matrix

### Deployment:

Streamlit web application for user interaction

## 🚀 Getting Started

### Step 1: Clone the Repository

git clone <repository-url>
cd Churn_modeling

### Step 2: Create a Virtual Environment and Install Dependencies

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

### Step 3: Run the Streamlit App

streamlit run app.py

## 🔍 Results

Model Accuracy: 86%

Precision: 71% (for churn class)

Recall: 52% (for churn class)

F1-Score: 60% (for churn class)

## 📌 Future Improvements

Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.

Experimenting with advanced neural network architectures.

Deployment using cloud platforms like AWS or Azure.

