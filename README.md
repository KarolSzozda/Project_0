# **Data analysis based on smog in Krakow**

In January 2017, southern Poland experienced record high air pollution. Due to the availability of data from that year, we decided to create a model predicting the estimated concentration of PM10 dust based on data from 56 sensors located in different parts of Krakow. We took into account the correlation of dust concentration in relation to atmospheric conditions such as air temperature, humidity, pressure and wind speed.

The following steps were performed:

1.   Alaysis features
2.   Selection features
3.   Data preparation
4.   Model Training
    *   Dummy Model
    *   Decision Tree Model
    *   Polynomial Regression
    *   Random Forest
5.   Evaluation and selection the best model

---

Additional information:

*   PM1 is not calibrated and therefore may be greater than PM2.5
*   PM2.5 may be greater than PM10 within the limits of measurement error
*   For the first two months, humidity and temperature were not calibrated and therefore may show inaccurate values

The project uses data from kaagle: https://www.kaggle.com/datasets/datascienceairly/air-quality-data-from-extensive-network-of-sensors
