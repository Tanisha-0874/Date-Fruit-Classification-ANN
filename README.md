# Date Fruit Classification using Artificial Neural Networks (ANN)
# Project Overview:
This project implements an Artificial Neural Network (ANN) using PyTorch to classify date fruits into seven different categories based on their physical and morphological characteristics.
The model learns patterns from 34 input features and predicts the corresponding date fruit category using a multiclass classification approach.

# Dataset:
Total observations: 898
Input features: 34
Target classes: 7
The seven date fruit categories are:
BERHI, DEGLET, DOKOL, IRAQI, ROTANA, SAFAVI, and SOGAY.

# Technologies Used:
Python
PyTorch
Pandas
NumPy
Scikit-learn

# Model Architecture:
The ANN consists of:
Input layer: 34 features
Hidden layer 1: 64 neurons with ReLU activation
Hidden layer 2: 64 neurons with ReLU activation
Output layer: 7 neurons

# Model Performance:
The model achieved a test accuracy of 95% on the 180 test samples in the recorded notebook execution.
Correct predictions: 171
Total test samples: 180
Test accuracy: 95%

# Project Workflow:
1.Dataset loading
2.Feature and target separation
3.Label encoding
4.Train-test splitting
5.Feature scaling using StandardScaler
6.Tensor conversion
7.DataLoader creation
8.ANN model construction
9.Model training using backpropagation
10.Model evaluation

