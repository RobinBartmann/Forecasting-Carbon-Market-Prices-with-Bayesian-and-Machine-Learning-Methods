# Forecasting-Carbon-Market-Prices-with-Bayesian-and-Machine-Learning-Methods
Forecasted Carbon Market returns with LSTM models in Python and shrinkage time varying parameter models in R. 

In this repository you can find the code and the data I used for my thesis "Forecasting Carbon Market Prices with Bayesian and Machine Learning Methods". I am glad about any feedback in general and are particulary interested in improving the performance of shrinkageTVP models or the LSTM model in python. My project is rather resource heavy due to forecasting more than 100 tismes in the future (1-step ahead and 4-step ahead forecasts) but I provided an intro model in each case to not use up too much time and still be able to judge model performance.

The files I added are:

## Data
- Cleaned XTS and TS data of all time series used to run the RCode "Prediciting Carbon Market Prices_Modelling Notebook"
- Cleaned CSV sheet of all time series used to run the Jupyter Notebook "LSTM Modelling Carbon Market Prices - Final"

## Code
- Data cleaning, processing and analysis notebook performed in R - "Predicting Carbon Market Prices_Cleaning and Exploratory Analysis"
- ShrinkTVP and MLR modelling performed in R - "Predicting Carbon Market Prices_Modelling"
- LSTM modelling performed in Python -"LSTM Modelling Carbon Market Prices - Final"

Note: I used rather complex forecasting formats with rolling windows and two different forecasting horizons. My comments should explain everything in detail, but please reach out if anything is unclear. 
