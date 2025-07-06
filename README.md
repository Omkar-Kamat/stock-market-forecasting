
# Stock Market Forecasting

Stock Market Forecasting using different Machine Learning and Deep Learning Concepts.
    

## SBIN_v1

This Model version uses daily stock market data from 2014-01-01 to 2025-07-05 for training a Neural Network Model.
This Model uses LSTM (Long Short-Term Memory) for pattern and trend recognition.  


This model aims to predict next day close price based on previous bars close prices and volume.

### Features of NN

- Sequential Model
- Input shape (100,2)
- 50 units LSTM Layer
- 1 Dense Layer with 25 units and 1 Dense Output layer with 1 units



## Running the File

Run the file on Google colab(Linux based platform).
    
## Run Locally
```bash
git clone --filter=blob:none --no-checkout https://github.com/Omkar-Kamat/stock-market-forecasting.git
cd stock-market-forecasting
git sparse-checkout init --cone
git sparse-checkout set SBIN_v1
git checkout

```
## SBIN_v2

This Model version uses daily stock market data from 2014-01-01 to 2025-07-05 for training a Neural Network Model.
This Model uses LSTM (Long Short-Term Memory) for pattern and trend recognition.  


This model aims to predict next day close price based on previous bars close prices and volume.

### Features of NN

- Sequential Model
- Input shape (100,2)
- 100 units LSTM Layer
- 1 Dense Layer with 25 units and 1 Dense Output layer with 1 units



## Running the File

Run the file on Google colab(Linux based platform).
    
## Run Locally
```bash
git clone --filter=blob:none --no-checkout https://github.com/Omkar-Kamat/stock-market-forecasting.git
cd stock-market-forecasting
git sparse-checkout init --cone
git sparse-checkout set SBIN_v2
git checkout

```

