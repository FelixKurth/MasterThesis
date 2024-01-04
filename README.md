# MasterThesis

This is the code used for the experiments in the master thesis "Confidence Intervals in Machine Learning based Time Series Forecasts with Application
to Demand Prediction"

For the experiments, several methods to construct prediction intervals are evaluated, these include:
- SARIMA
- Jackknife+ after Bootstrap (https://www.stat.uchicago.edu/~rina/jackknife+-after-bootstrap_realdata.html)
- Concrete Dropout with dense neural network and with recurrent neural network (https://github.com/yaringal/ConcreteDropout)
- Split Conformal Prediction with and without Kernel Density Estimation
- Cross Conformal Prediction (https://github.com/alexcontarino/Constructing-Prediction-Intervals-for-Neural-Networks/tree/main)
- Lower Upper Bound Estimation (https://github.com/TeaPearce/Deep_Learning_Prediction_Intervals)
- Mean Variance Estimation (https://github.com/LaurensSluyterman/Mean_Variance_Estimation)

The original time series data is confidential. However, the code works for time series data in a csv file format with two columns: a date and a demand column.

Structure:
- [Main Evaluation](auswertung.ipynb)
- [Lower Upper Bound Estimation Evaluation](HQ_Pearce_QQ_Good.ipynb)
