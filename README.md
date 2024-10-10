# Stock Price Prediction using LSTM

## Overview
This project aims to predict NTT’s stock price using a Long Short-Term Memory (LSTM) model. The goal is to explore stock price trends, engineer features, and validate the model’s prediction accuracy for practical use. The code builds, trains, and evaluates an LSTM-based time series model on stock price data.

## Table of Contents
- [Project Objective](#project-objective)
- [Data Overview](#data-overview)
- [Model Selection](#model-selection)
- [Evaluation Metrics](#evaluation-metrics)
- [How to Run the Code](#how-to-run-the-code)
- [Results](#results)
- [Future Work](#future-work)

## Project Objective
**Main Objective**: Build a robust stock price prediction model.  
**Focus**: Using LSTM, the model captures long-term dependencies in stock price movements and evaluates its performance using relevant metrics.

## Data Overview
-**Date:** The date of the stock data.<br>
-**Closing Price:** The price of the stock at market close.<br>
-**Opening Price:** The price of the stock at market open.<br>
-**High Price:** The highest price during the trading session.<br>
-**Low Price:** The lowest price during the trading session.<br>
-**Volume:** The number of shares traded.<br>
-**Percentage Change:** The percentage change in price compared to the previous 
trading day.

## Model Selection
- **LSTM**: A Recurrent Neural Network (RNN) that is suited for handling sequential time-series data and capturing long-term dependencies.
- **Features**: The model incorporates price data and technical indicators (MA50, RSI) to enhance predictive performance.
- **Model Configuration**:
  - 50 epochs
  - Batch size: 30
  - Dropout layer for regularization
  - Additional LSTM layers to improve accuracy

## Evaluation Metrics
The model’s performance is evaluated using:
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual stock prices.
- **R-squared (R²)**: Explains the proportion of variance captured by the model.

## How to Run the Code

### Prerequisites
Ensure Python 3.7+ and the required packages (listed in `requirements.txt`) are installed.

### Instructions

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/stock-price-prediction.git
    cd stock-price-prediction
    ```

2. **Install Required Libraries**: Install dependencies from `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare the Data**:

    - Place the stock price data (CSV format) in the project folder.
    - Ensure the dataset contains a 'Closing Price' column for predictions.

4. **Run the Code**: Execute the main script:

    ```bash
    python main.py
    ```

    This will preprocess the data, train the LSTM model, and generate predictions.

## Results
[Add a plot or image of the results here]

The model’s performance can be visualized by comparing the actual vs. predicted stock prices over the test period. The first 50 iterations of predictions are highlighted to demonstrate the model's accuracy.

## Future Work
- **Feature Expansion**: Consider adding external economic indicators (e.g., interest rates, inflation) for improved predictions.
- **Hyperparameter Tuning**: Experiment with different batch sizes, epochs, and learning rates to optimize model performance.
- **Integration with Live Data**: Implement real-time prediction using live stock data for practical trading applications.
