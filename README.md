Rainfall Prediction Model Using LSTM
This model leverages Long Short-Term Memory (LSTM) neural networks to forecast daily rainfall based on historical weather data. By capturing temporal dependencies and non-linear relationships among features like temperature, humidity, wind speed, and cloud cover, the model predicts next-day rainfall intensity with high accuracy.
Key highlights:
- Input Features: Includes lag variables, rolling averages, and date-based seasonality indicators.
- Architecture: Three stacked LSTM layers with dropout regularization and a dense output layer.
- Preprocessing: Time-series reshaping with a 7-day look-back window; MinMax scaling for normalization.
- Performance: Achieves an R² score of 0.85, outperforming traditional models like ARIMA.
- Use Case: Supports agricultural planning, flood risk mitigation, and water resource management.
