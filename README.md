# Forecasting Crude Oil Prices

This project aims to forecast the Brent crude oil price using LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) models. We utilize data from the Federal Reserve Economic Data (FRED) database, spanning from 1987 to 2024. Our goal is to develop a model capable of accurately predicting future oil prices based on historical data.

# Data Source

The crude oil price data used in this project is obtained from the Federal Reserve Economic Data (FRED) using the FRED API. The dataset provides historical daily price information for Brent crude oil.

# Model Architecture

- LSTM model with 2 LSTM layers and 1 dense output layer
- GRU model with 2 GRU layers and 1 dense output layer
- Mean squared error loss, Adam optimizer
- Early stopping to prevent overfitting

# Requirements

To run the code in this repository, you will need the following packages:

- `fredapi`
- `matplotlib`
- `seaborn`
- `numpy`
- `pandas`
- `sklearn`
- `tensorflow`
- `keras`

These can be installed via pip:

```python
pip install fredapi matplotlib seaborn numpy pandas sklearn tensorflow keras
```

## Contributing

Contributions, issues, and feature requests are welcome.

## License

See `LICENSE` for more information.
