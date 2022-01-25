# Stock Price Predictions

[Link to Report](/Stock%20Predictions/Report%20-%20Predicting%20Security%20Prices.pdf)

Class: [STATS 202](https://stats-202.github.io/) - Data Mining and Analysis

Code (in R): [Google Colab](https://colab.research.google.com/drive/10Ze50f7lqaIhnqwnDOKastTpuRbXjEO7?usp=sharing)

We were tasked with making a 9 day forecast at the 5-second granularity for 9 anonymized stock tickers. After exploring baseline and ARIMA models, we ultimately structured the problem as a **direct forecasting problem** and used the [forecast-ml package](https://github.com/nredell/forecastML) to train and make predictions. Note that we did not actually learn how to do time series analysis for this class, so we had to convert the problem into a structure we were familiar with.
