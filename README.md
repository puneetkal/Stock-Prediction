# Stock Price Prediction Model using LSTM

## [Introduction](#introduction)
In this project, we build a time series prediction model using NTT’s stock price data. The goal is to perform exploratory data analysis (EDA), preprocess the data, build a prediction model, and evaluate its accuracy for practical use in stock price forecasting.

## [Task Overview](#task-overview)
In this task, we focus on creating a stock price prediction model using LSTM. The steps include:
1. **EDA**: Understanding the data trends, detecting seasonality and anomalies.
2. **Data Preprocessing**: Handling missing values, scaling, and creating relevant features.
3. **Model Selection**: Choosing the LSTM model to capture long-term dependencies in the data.
4. **Model Training**: Training the LSTM model with defined hyperparameters.
5. **Model Evaluation**: Validating the model’s accuracy using relevant metrics.

## [Work Guidelines](#work-guidelines)
- **Duration**: 1 week
- **Work Time**: 12 to 20 hours

### Expected Timeline:
- **2 hours**: Understanding the data and performing EDA.
- **2 hours**: Data preprocessing and feature engineering.
- **1 hour**: Model selection and training.
- **1 hour**: Model evaluation and result analysis.
- **4 to 8 hours**: Considering improvements and retraining the model.
- **2 to 6 hours**: Summarizing results and preparing presentation materials.

## [Task Content](#task-content)

### [1. Understanding the Data and EDA](#eda)
**Overview**: Using NTT’s stock price data to check basic statistics, detect trends and seasonality in the time series, and identify anomalies.  
**Goal**: Extract challenges for the prediction model.

### [2. Data Preprocessing and Feature Engineering](#preprocessing)
**Overview**: Handle missing values, normalize the data, and create new features (such as moving averages and RSI).  
**Goal**: Prepare the dataset to improve the model's accuracy.

### [3. Model Selection and Training](#model-selection)
**Overview**: Select an appropriate model (e.g., LSTM) for time series prediction.  
**Goal**: Build a model that maximizes prediction accuracy.

### [4. Model Evaluation and Result Analysis](#evaluation)
**Overview**: Validate the model using metrics such as Mean Squared Error (MSE) and R-squared (R²).  
**Goal**: Objectively evaluate the effectiveness of the model.

### [5. Considering Improvements and Retraining the Model](#improvements)
**Overview**: Test hypotheses to improve the model’s accuracy, such as adding more LSTM layers or adjusting dropout rates.  
**Goal**: Refine the model for better results.

### [6. Summarizing Results and Presentation](#presentation)
**Overview**: Prepare slides summarizing the model-building process, results, and validation of hypotheses.

## [How to Run the Code](#run-the-code)
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/stock-price-prediction.git
    cd stock-price-prediction
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Code**:
    ```bash
    python main.py
    ```

## [Evaluation Metrics](#evaluation-metrics)
- **Mean Squared Error (MSE)**: Measures the average squared difference between the actual and predicted stock prices.
- **R-squared (R²)**: Explains how well the actual stock price variance is captured by the model.

## [Hypotheses and Results](#hypotheses)
- **Hypothesis 1**: Increasing the dropout rate will reduce overfitting.
- **Hypothesis 2**: Adding more LSTM layers will improve model performance.

## [Limitations](#limitations)
1. **Overfitting**: The model might perform well on training data but struggle on unseen data due to overfitting.
2. **Lack of External Features**: Incorporating economic factors or market sentiment could further improve prediction accuracy.

## [Future Work](#future-work)
- Explore hyperparameter tuning for better performance.
- Integrate live stock data for real-time predictions.
