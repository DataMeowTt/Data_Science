# ⚡ Hourly Energy Consumption Forecasting

This project aims to **forecast hourly electricity consumption** based on the PJM (USA) power system dataset. The project uses various methods from statistical modeling to deep learning.

## 📁 Folder Structure

<pre>
ENERGY_CONSUMPTION/
├── Data_Science/
│ ├── data/ # Contains processed CSV files from PJM dataset
│ ├── Energy_consumption.ipynb # Summary of the entire analysis & visualization process
│ ├── LSTM.ipynb # Forecasting with basic LSTM
│ ├── LSTM_CONV.ipynb # Forecasting with LSTM combined with CNN
│ ├── LSTM_ATTENTION.ipynb # LSTM with Attention
│ ├── xgb_model.json # Trained and saved XGBoost model
│ └── energy.jpg
</pre>

## ✅ How to use
1. Download the dataset from Kaggle and put it in the data/ folder
2. Open the .ipynb files using Jupyter Notebook or VSCode
3. Run each cell in order to reproduce the results

## 📈 Results
- Each notebook will show **prediction plot** and **evaluation index** (RMSE, MAE…)
- Each notebook can be easily opened to rerun, modify, and experiment further
