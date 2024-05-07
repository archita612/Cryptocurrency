# Stock Price Prediction with LSTM
<h2>Overview</h2>
<ul>
  <li>This project utilizes Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data. LSTM networks are well-suited for time series forecasting tasks due to their ability to capture long-term dependencies in sequential data.</li>
</ul>

<h2>Key Features</h2>
<ul>
  <li><strong>Data Preparation:</strong> The dataset consists of historical stock prices along with relevant features such as volume, price changes, and moving averages.</li>
  <li><strong>Model Architecture:</strong> The LSTM model is designed with multiple layers and dropout regularization to prevent overfitting.</li>
  <li><strong>Regularization Techniques:</strong> L1/L2 regularization is applied to the model to enhance robustness and prevent excessive complexity.</li>
  <li><strong>Learning Rate Scheduling:</strong> Learning rate scheduling is implemented to optimize model training by adjusting the learning rate over time.</li>
  <li><strong>Evaluation Metrics:</strong> The model performance is evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²) to assess prediction accuracy and generalization.</li>
</ul>

    Evaluation: The model's performance is evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score on both training and test datasets.

Results

The LSTM model demonstrates strong performance in accurately predicting stock prices, achieving significant improvements in prediction accuracy while effectively mitigating overfitting.
