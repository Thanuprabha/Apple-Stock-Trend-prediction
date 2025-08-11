# Apple-Stock-Trend-prediction
Short description:  
A stock trend prediction project for AAPL using LSTM / Attention-Transformer models. Trains on historical price + sentiment features and outputs trend predictions and percentage change.

## Project Structure
- `AT-LSTM.ipynb` — Main notebook with preprocessing, model training and evaluation.  
- `Attention_Transformer_LSTM_Model.h5` — Trained model file (not recommended to push to public repo).  
- `merged_AAPL_data.csv` — Merged dataset (price + sentiment).  
- `scaler_stock.pkl`, `scaler_sentiment.pkl` — Scalers for features.  
- `Trend_percentage.ipynb` — Notebook for computing/displaying trend percentages.  
- `requirements` — Required Python packages (pip install -r requirements).

## Features
- Preprocessing pipeline for stock prices and sentiment data.
- LSTM / Attention-Transformer hybrid model for trend prediction.
- Scalers saved for inference consistency.
- Scripts/notebooks for evaluation and trend percentage calculation.

## Requirements
```bash
python 3.8+
pip install -r requirements
