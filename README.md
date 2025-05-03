# 🧠 Demand Forecasting using Deep Learning

This project implements a deep learning-based demand forecasting model using a **Feedforward Neural Network (FNN)**. It aims to accurately predict future weekly demand for retail items based on historical sales data.

## 📌 Project Overview

- **Goal**: Forecast weekly demand based on time series retail data
- **Approach**: Build and train a Feedforward Neural Network (FNN) using TensorFlow and Keras
- **Dataset**: ~33,000 rows of historical weekly sales records for various items and stores

## 🔧 Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn

## 📈 Model Architecture

- **Input Layer**: Encoded categorical variables + numerical features
- **Hidden Layers**: 3 Dense layers with ReLU activation
- **Regularization**: Dropout layers to prevent overfitting
- **Optimizer**: Adam
- **Loss Function**: Mean Squared Error
- **Callbacks**: EarlyStopping based on validation loss

## 🧪 Results

Performance on the **validation set**:

- **R² Score**: 0.9409
- **Mean Squared Error (MSE)**: 29,228,688
- **Mean Absolute Error (MAE)**: 1,979.94

These metrics demonstrate strong model accuracy and generalization capability.


