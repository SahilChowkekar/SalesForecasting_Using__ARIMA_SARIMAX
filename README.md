# Sales Forecasting Using ARIMA and SARIMAX

This Jupyter notebook demonstrates the process of sales forecasting using ARIMA and SARIMAX models. The steps covered in the notebook include:

1. **Data Preparation**:
   - Loading and cleaning the dataset.
   - Visualizing the time series data to understand its patterns.

2. **Stationarity Check**:
   - Testing for stationarity using the Augmented Dickey-Fuller (ADF) test.
   - Applying differencing to make the data stationary.

3. **AutoCorrelation Analysis**:
   - Plotting autocorrelation and partial autocorrelation functions to determine the model parameters.

4. **Model Building**:
   - Constructing ARIMA and SARIMAX models based on the stationarity and autocorrelation analysis.

5. **Model Evaluation and Prediction**:
   - Evaluating the model performance using residual analysis.
   - Making predictions for future time points.

## Dependencies

- numpy
- pandas
- matplotlib
- statsmodels

## How to Use

1. Install the required dependencies using pip:

```bash
pip install numpy pandas matplotlib statsmodels
