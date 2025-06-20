Predicting Beijing's Air Quality with LSTM

Air pollution in Beijing poses serious health risks. This project forecasts hourly PM₂.₅
concentrations using LSTM networks, aiming for an RMSE < 4000 on the Kaggle private
leaderboard. My approach combined thorough EDA, feature engineering, systematic
experimentation (15 runs), and an ensemble of top models.

1. Feature engineering (lags, rolling means) and cyclic encodings were critical.
2. Regularization (dropout, early stopping) prevented overfitting.
3. Ensembles of diverse architectures improved robustness.
