#Multivariate Time Series Forecasting with LSTMs in Keras

> We will frame the supervised learning problem as predicting the pollution at the current hour (t) given the pollution measurement and weather conditions at the prior time step.

This formulation is straightforward and just for this demonstration. Some alternate formulations you could explore include:

    * Predict the pollution for the next hour based on the weather conditions and pollution over the last 24 hours.
    * Predict the pollution for the next hour as above and given the “expected” weather conditions for the next hour.
