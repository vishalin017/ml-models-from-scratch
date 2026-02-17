# K-Nearest Neighbours (KNN) from Scratch

This project implements the K-Nearest Neighbours (KNN) classification algorithm from scratch using Python and NumPy, without using machine learning libraries like scikit-learn for the model itself.

## Objective

The goal of this project is to understand how KNN works internally, including:

- Distance calculation
- Finding nearest neighbours
- Majority voting
- Classification
- Model evaluation
- Visualization of results

## Concepts Implemented

### 1. Distance Calculation

Euclidean distance is used to measure similarity between data points:

distance = sqrt( Σ (x1 - x2)² )

### 2. Finding K Nearest Neighbours

For a given input:

- Distance is calculated from all training points
- K closest points are selected
- Their labels are used for prediction

### 3. Majority Voting

The class with the highest frequency among neighbours becomes the prediction.

### 4. Prediction

The model predicts class labels for new unseen data based on nearest neighbours.

### 5. Visualization

Graphs are used to visualize:

- Training data
- Prediction regions
- Classification results

## Files


