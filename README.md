# Stock Price Prediction using LSTM Neural Network

This project demonstrates a **Long Short-Term Memory (LSTM)** neural network for predicting stock prices based on historical data. The model is capable of forecasting stock prices for the next 30 days given an initial date. The implementation uses **Python**, **Keras**, and **TensorFlow** for model building and training.

---

## Features

- **Data Preprocessing**:
  - Historical stock prices are scaled using Min-Max normalization.
  - Data is split into training and testing datasets for model evaluation.
  
- **Model Architecture**:
  - LSTM layers for sequential learning.
  - Dropout layers to prevent overfitting.
  - Dense layer for predicting the next price point.
  
- **Functionality**:
  - Save and load trained LSTM models for future use.
  - Predict stock prices for the next 30 days from a given date.
  - Graphical visualization of predictions, including highlighted first and last predicted prices.

---

