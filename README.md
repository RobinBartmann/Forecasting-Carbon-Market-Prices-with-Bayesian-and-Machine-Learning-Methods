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

##  Thesis
- I upload the thesis abstract here to show my research results. The entire thesis with a comprehensive carbon market introduction and detailed forecasting procedures are available on request to robin.bartmann@gmail.com. 
- Abstract: 
As answer to the current climate crisis, “Becoming carbon neutral in 2030 / 2040 / 2050” can be read in the news from companies and governments alike. Efficient compliance (and voluntary) carbon markets with targeted facilitation are central to achieving carbon neutrality. 
To support this, the thesis used recent Bayesian and Machine Learning methods to investigate improved forecast accuracy and interpretability. The returns carbon price series of the entire Phase 3 of the EU ETS (2013-2020) was forecasted with commodity prices, an economic activity index and temperature as price drivers to perform a one-step (weekly) and four-step (monthly) ahead forecast. 
The results show an improvement in directional and level accuracy of both the Bayesian methods and the Machine Learning (LSTM) model, when compared with a baseline multiple linear regression (MLR) model. The Bayesian methods were split into a time-varying parameter model with shrinkage (shrinkTVP) and the same model including a stochastic volatility process (shrinkTVPwithSV). The shrinkTVPwithSV model outperformed the shrinkTVP model in the weekly forecast, indicating the advantage of including stochastic volatility modelling in future forecasting efforts. 
The recommendations are (i) including the LSTM model and stochastic volatility processes in future forecasting efforts and (ii) using the shrinkTVP model to interpret the time-varying relevance of price drivers. The policy implication for ETS administration is to use the increased forecasting accuracy and interpretability to make necessary adjustments to over- or undersupply of emissions allowances and with this increase the effectiveness of the ETS to reduce CO2 emissions. 
