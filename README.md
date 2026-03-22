# 📈 Market Regime-Based Trading Strategy using Econophysics, HMM, and LSTM

## Overview
This project builds a trading strategy by combining econophysics, Hidden Markov Model (HMM), and LSTM.

The idea is to treat financial markets as a complex system, not just price data. By capturing patterns like volatility, randomness, and regime changes, this project explores whether combining market structure and deep learning can improve trading performance.

---

## Methodology

- **Feature Engineering (Econophysics)**  
  Extract features such as return and volatility to represent market dynamics.

- **Market Regime Detection (HMM)**  
  Identify hidden market conditions like bullish, bearish, and high volatility.

- **Prediction Model (LSTM)**  
  Use deep learning to predict price movement from time series data.

- **Trading Strategy**  
  Combine prediction and regime information to generate trading signals.

- **Backtesting**  
  Evaluate performance using Sharpe Ratio, Maximum Drawdown, and comparison with Buy & Hold.

---

## Results

- LSTM produces positive but still limited performance  
- HMM works well for detecting regimes but not as a direct trading signal  
- Strategy performance depends heavily on decision rules and risk management  

---

## Key Insight

A model can be accurate in prediction, but that does not guarantee a profitable trading strategy.

---

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, hmmlearn, TensorFlow/Keras, Matplotlib

---

## How to Run

1. Clone this repository  
2. Open the notebook  
3. Run all cells  

---

## Author

Al Gibran Raya Aliefio Santoso
