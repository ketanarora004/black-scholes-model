# black-scholes-model

This repository contains a options contract pricing model 

## Files

- **LSTM.ipynb**: Jupyter notebook containing the LSTM model implementation.
- **app.py**: Streamlit application file for deploying the model.
- **keras_model.h5**: Pre-trained LSTM model saved in HDF5 format.

## Dependencies

Make sure you have the following Python libraries installed:

- Numpy (numpy): Used for numerical operations, particularly for calculations in the Black-Scholes model and for handling arrays.
- Pandas (pandas): Used for data manipulation and analysis, particularly for handling time series data and creating dataframes for option prices.
- Matplotlib (matplotlib.pyplot): Used for plotting and visualizing the comparison between theoretical and actual option prices.
- Yahoo Finance (yfinance): Used to fetch historical price data and option chain data for the S&P 500 Index (SPX).
- SciPy (scipy.stats): Specifically, the scipy.stats.norm module is used for cumulative distribution function calculations in the Black-Scholes model.







You can install them using pip:

```bash
pip install numpy pandas matplotlib 
```




## Model Training

If you want to train the LSTM model yourself, refer to `LSTM.ipynb`. It includes the data preprocessing steps, model architecture, training, and evaluation.

## Credits

- **Author**: Ketan Arora
- **Email**: a.ketan@iitg.ac.in

---
