# Credit Card Fraud Detection using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Fraud detection is important in financial systems to prevent financial losses and protect customers.

The model is trained to classify transactions as **fraudulent or genuine** based on transaction features.

## Dataset
The dataset used in this project is the **Credit Card Fraud Detection Dataset** containing transactions made by European cardholders.

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Genuine Transactions: 284,315

Due to the highly **imbalanced dataset**, special attention is required during model training.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Preprocessing
- Loaded dataset using Pandas
- Checked data structure and missing values
- Normalized transaction amount
- Removed unnecessary features

### 2. Exploratory Data Analysis
- Visualized class distribution
- Analyzed feature distributions

### 3. Model Training
A **Logistic Regression model** was used to classify transactions.

### 4. Model Evaluation
The model was evaluated using:

- Precision
- Recall
- F1-score
- Confusion Matrix

## Results
The model successfully identifies fraudulent transactions with good performance metrics.

## Future Improvements
- Deploy the model using Flask or Streamlit

## Author
Vanshika Malik
