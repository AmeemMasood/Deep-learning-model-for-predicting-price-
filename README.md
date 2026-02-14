💎 Diamond Price Prediction Using Neural Networks
📌 Project Overview

This project implements a deep learning regression model to predict diamond prices using a three-layer neural network built with PyTorch. The model is trained and evaluated in Google Colab for easy execution and GPU support.

The goal is to learn the relationship between diamond characteristics and their market price.


📊 Dataset
This project uses the Diamonds Dataset from Kaggle.
🔹 Dataset Features
The dataset contains information about diamonds such as:
carat,
cut,
color,
clarity,
depth,
table,
x, y, z (dimensions)

🎯 Target Variable
price (continuous value)
Dataset link:
https://www.kaggle.com/datasets/natedir/diamonds/data


🧠 Model Architecture
The model is a three-layer neural network regressor designed for continuous value prediction.
🔹 Key Differences from Classification
Output layer produces one continuous value,
No Softmax activation,
Uses MSE loss instead of Cross-Entropy,


⚙️ Technologies Used
PyTorch,
Google Colab,
Pandas,
NumPy,
Matplotlib,
Scikit-learn,


📈 Model Evaluation
In addition to MSE loss, the model is evaluated using:
📊 Evaluation Metrics
Metric	  | Description
MAE	      | Mean Absolute Error
RMSE	    | Root Mean Squared Error
R² Score	| Variance explained
These metrics help measure both accuracy and reliability.



📉 Visualization
🔹 Training & Validation Loss
Loss curves are plotted to monitor learning progress
Helps detect overfitting or underfitting
🔹 Predicted vs Actual Prices
A scatter plot is used to compare predictions and true prices.
Interpretation:
Diagonal line → Perfect predictions,
Above line → Underestimation,
Below line → Overestimation,
This visualization shows how well the model fits real data.


Key Features
✔️ Neural network regression model
✔️ Google Colab implementation
✔️ Automatic data preprocessing
✔️ Multiple evaluation metrics
✔️ Performance visualizations
✔️ Clean end-to-end pipeline
