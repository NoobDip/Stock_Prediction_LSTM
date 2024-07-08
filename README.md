# LSTM Time Series Prediction for Stock Prices

This repository contains code for predicting stock prices using LSTM (Long Short-Term Memory) networks. The model is trained on historical stock data and tested for prediction accuracy.

## Dataset

The dataset used (`NIFTY.csv`) contains daily stock prices of NIFTY. It includes columns for Date and Closing Price.

## Requirements

- Python 3.x
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Files

- `main.py`: Contains the main script to preprocess data, define and train the LSTM model, and evaluate predictions.
- `NIFTY.csv`: Dataset file containing historical stock prices.
- `readme.md`: This file, providing an overview of the project.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/NoobDip/Stock_Prediction_LSTM.git
   cd Stock_Prediction_LSTM
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```
   python main.py
   ```

## Results

After training and validation, the model's predictions are visualized against actual stock prices for both training and testing datasets.

## Notes

- Adjust hyperparameters like `lookback`, `batch_size`, `num_epochs`, and `learning_rate` in `main.py` as needed.
- Modify the model architecture (`LSTM` class in `main.py`) for experimentation or different datasets.
