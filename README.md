🔍 Project Overview
This project applies Exponential Smoothing State Space Models (ETS) to forecast Costco (COST) stock prices. Various ETS configurations—Simple, Additive, and Multiplicative—were tested to determine the most accurate forecasting approach.

📊 Methodology
Data: Historical stock price data for Costco.
Models: ETS variations (Simple, Additive, Multiplicative).
Evaluation Metrics:
RMSE, MAE, MAPE – Standard error metrics.
MASE, sMAPE – Scaled and symmetric error measures.

🏆 Key Findings
Double Multiplicative ETS performed best with lowest RMSE (94.54), MAE (84.81), MAPE (9.65%), MASE (2.70), and sMAPE (10.24%).
Multiplicative models better captured stock price fluctuations than additive ones.
Simple models lacked trend adjustments, leading to poor accuracy.
