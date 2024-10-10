<body>
    <h1>Stock Price Prediction using LSTM</h1>

    <h2>Introduction</h2>
    <p>This project aims to predict stock prices using a Long Short-Term Memory (LSTM) model based on historical data from NTT’s stock. Stock price prediction plays a crucial role in guiding investment strategies and managing financial risks.</p>

    <h2>Importance</h2>
    <ul>
        <li><strong>Guides investment strategies</strong>: Helps investors make informed decisions.</li>
        <li><strong>Aids in risk management</strong>: Allows for better understanding of market trends.</li>
    </ul>

    <h2>Challenges</h2>
    <ul>
        <li><strong>High volatility</strong>: Stock prices can change rapidly, making predictions difficult.</li>
        <li><strong>Complex market trends</strong>: Markets are influenced by numerous factors, complicating the prediction process.</li>
    </ul>

    <h2>Objective</h2>
    <p>To build an LSTM model for NTT’s stock data and validate its accuracy for practical usage.</p>

    <h2>Model Selection</h2>
    <h3>Overview of Time Series Models</h3>
    <p>We explored various models, but the LSTM, an advanced Recurrent Neural Network (RNN), was chosen due to its ability to capture long-term dependencies in time series data.</p>

    <h3>Why LSTM?</h3>
    <p>LSTM excels in time series forecasting because it can remember patterns over long sequences, unlike traditional RNNs, which suffer from vanishing gradient problems.</p>

    <h2>Model Training</h2>
    <ul>
        <li><strong>Epochs</strong>: 50</li>
        <li><strong>Batch Size</strong>: 30</li>
    </ul>

    <h2>Evaluation Metrics</h2>
    <ul>
        <li><strong>Mean Squared Error (MSE)</strong>: Measures the average squared difference between actual and predicted values.</li>
        <li><strong>R-squared (R²)</strong>: Indicates the proportion of variance in the target that the model explains.</li>
    </ul>

    <h2>Result Analysis</h2>
    <p><em>(Image Placeholder)</em></p>

    <h2>Hypotheses</h2>
    <h3>Hypothesis 1</h3>
    <p>Increasing the dropout rate will reduce overfitting, improving the model's ability to generalize to unseen data.</p>

    <h3>Hypothesis 2</h3>
    <p>Adding more LSTM layers will improve model performance by capturing more complex patterns in the stock data.</p>

    <h2>Limitations of the Current Model</h2>
    <ul>
        <li><strong>Overfitting</strong>: The model may perform well on training data but struggle with unseen data due to overfitting.</li>
        <li><strong>Lack of External Features</strong>: The model only uses historical stock prices, without considering external factors like market news or economic indicators.</li>
    </ul>

    <h2>Repository</h2>
    <p>The code for the model is available in the <code>main.py</code> file, with necessary dependencies listed in <code>requirements.txt</code>. To run the model, follow the instructions in this repository.</p>
</body>
