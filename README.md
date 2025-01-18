
Our project predicts Amazon stock prices (2010–2024) using an LSTM neural network. Historical 'Close' prices are scaled with MinMaxScaler and a 60-day window predicts the next day's price. With dropout regularization and Adam optimizer, predictions are inverse-transformed, and actual vs predicted prices are visualized to assess performance.
