# Logistic_Regression

## 📌 Overview
This repository contains small projects demonstrating the use of *Logistic Regression* for classification problems:
1. *Predicting Insurance Purchase* – Predicting whether a person will buy insurance with 100% accuracy on a small dataset.
2. *Predicting Employee Attrition* – Determining whether an employee will leave the company using categorical data (dummy variables).

## 📖 About Logistic Regression
Logistic Regression is a *supervised classification algorithm* used when the target variable is categorical (e.g., Yes/No, 0/1).  
It estimates the probability that a given input belongs to a certain class using the *sigmoid function*:

\[
P(Y=1) = \frac{1}{1 + e^{-(b_0 + b_1x_1 + b_2x_2 + ... + b_nx_n)}}
\]

Where:
- \( P(Y=1) \) is the probability of the positive class  
- \( x_1, x_2, ..., x_n \) are input features  
- \( b_0, b_1, ..., b_n \) are coefficients  

The output probability is then converted into a class label based on a threshold (commonly 0.5).

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Predicting Insurance Purchase
- *Goal*: Predict whether a customer will buy insurance.
- *Process*:
  - Load and clean dataset
  - Train Logistic Regression model
  - Evaluate accuracy
- *Accuracy*: 100% (small dataset)

### 2️⃣ Predicting Employee Attrition with Dummy Variables
- *Goal*: Predict whether an employee will leave the company using categorical features such as department and salary level.
- *Process*:
  - Convert categorical variables to dummy variables
  - Train Logistic Regression model
  - Evaluate accuracy
- *Accuracy*: [76.2]
