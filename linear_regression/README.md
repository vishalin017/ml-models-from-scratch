# Linear Regression from Scratch (Gradient Descent)

This project implements Linear Regression from scratch using Python, NumPy, and Gradient Descent, without using any machine learning libraries like scikit-learn.

## Objective

The goal of this project is to understand the internal working of Linear Regression, including:

- Prediction function
- Cost function (Mean Squared Error)
- Gradient Descent optimization
- Model training
- Visualization of training progress
- Making predictions on new data

## Dataset Used

This project uses a simple custom dataset:

Study Hours (X):
[1, 2, 3, 4, 5]

Marks Scored (y):
[35, 50, 65, 80, 95]

This dataset represents a linear relationship between study hours and marks.

## Concepts Implemented

The following components are implemented manually:

### 1. Prediction Function

y = wX + b

### 2. Cost Function

Mean Squared Error:

Cost = (1/n) * Σ(predicted - actual)^2

### 3. Gradient Descent

Weights and bias are updated using:

dw = (2/n) * Σ(error * X) 
db = (2/n) * Σ(error)

w = w - learning_rate * dw 
b = b - learning_rate * db 

### 4. Training

The model is trained for 500 iterations using learning rate = 0.01.

### 5. Visualization

Two graphs are plotted:

• Cost vs Iteration 
• Best fit regression line 

### 6. Prediction on New Data

The model predicts marks for new study hours such as:

3.5 hours 
5 hours 

## Files

linear_regression_bootcamp.py → main implementation 
requirements.txt → dependencies 
README.md → project documentation

## How to Run

Install dependencies:

pip install -r requirements.txt

Run the program:

python linear_regression_bootcamp.py

## Output

The program will show:

• Cost decreasing during training 
• Final learned weight and bias 
• Regression line plot 
• Predicted marks 

## Purpose of this Repository

This project is part of my Machine Learning learning journey, where I am implementing ML algorithms from scratch to build strong fundamentals.

Future implementations will include:

- Logistic Regression
- KNN
- KMeans
- Neural Networks

## Author

Vishal Singh
Machine Learning Student

