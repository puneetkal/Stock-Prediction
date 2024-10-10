# Stock Price Prediction using LSTM

## Introduction
This project aims to predict stock prices using a Long Short-Term Memory (LSTM) model based on historical data from NTT’s stock. Stock price prediction plays a crucial role in guiding investment strategies and managing financial risks.

## Importance
- **Guides investment strategies**: Helps investors make informed decisions.
- **Aids in risk management**: Allows for better understanding of market trends.

## Challenges
- **High volatility**: Stock prices can change rapidly, making predictions difficult.
- **Complex market trends**: Markets are influenced by numerous factors, complicating the prediction process.

## Objective
The objective of this project is to build an LSTM model for NTT’s stock data and validate its accuracy for practical usage.

## Model Selection

### Overview of Time Series Models
We explored various models, but the LSTM, an advanced Recurrent Neural Network (RNN), was chosen due to its ability to capture long-term dependencies in time series data.

### Why LSTM?
LSTM excels in time series forecasting because it can remember patterns over long sequences, unlike traditional RNNs, which suffer from vanishing gradient problems.

## Model Training
- **Epochs**: 50
- **Batch Size**: 30

## Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures the average squared difference between actual and predicted values.
- **R-squared (R²)**: Indicates the proportion of variance in the target that the model explains.

## Result Analysis
*(Image Placeholder)*

## Hypotheses

### Hypothesis 1:
Increasing the dropout rate will reduce overfitting, improving the model's ability to generalize to unseen data.

### Hypothesis 2:
Adding more LSTM layers will improve model performance by capturing more complex patterns in the stock data.

## Limitations of the Current Model
- **Overfitting**: The model may perform well on training data but struggle with unseen data due to overfitting.
- **Lack of External Features**: The model only uses historical stock prices, without considering external factors like market news or economic indicators.

## Repository
The code for the model is available in the `main.py` file, with necessary dependencies listed in `requirements.txt`. To run the model, follow the instructions below:

### How to Run
1. Clone the repository: 
    ```bash
    git clone https://github.com/yourusername/stock-price-prediction.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the model:
    ```bash
    python main.py
    ```

---
