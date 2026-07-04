# Customer Churn Prediction using Deep Learning

## Project Overview
This project focuses on predicting customer churn using Deep Learning techniques. Customer churn prediction helps identify customers who are likely to leave the bank, enabling better customer retention strategies.

## Objective
The objective of this project is to build a deep learning model that predicts whether a customer will exit based on customer profile and banking behavior.

## Dataset
The dataset contains bank customer information with multiple numerical and categorical features.

### Features Used
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary

### Target Variable
- Exited  
  - 0 → Customer stays  
  - 1 → Customer leaves  

## Data Preprocessing
The following preprocessing steps were performed:
- Removing unnecessary columns (RowNumber, CustomerId, Surname)
- Encoding categorical features
- Feature scaling
- Train-test splitting

## Technologies Used
- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Jupyter Notebook / Kaggle

## Deep Learning Model
An Artificial Neural Network (ANN) was used for customer churn prediction.

### Model Architecture
- Input Layer
- Hidden Layers
- Output Layer

## Model Performance
- Accuracy: 86%

## Project Workflow
1. Data Collection  
2. Data Cleaning  
3. Data Preprocessing  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  

## Project Files
- Deeplearning-Customer Churn.ipynb → Main notebook
- README.md → Project documentation

## Conclusion
The deep learning model achieved an accuracy of 86% in predicting customer churn. This model can help banks identify customers at high risk of leaving and improve retention strategies.

## Author
Ishita Mishra
