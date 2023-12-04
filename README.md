# TIME-SERIES-FORECASTING-OF-BRENT-CRUDE-OIL-PRICE-USING-REGRESSION-AND-LSTM
This study focuses on utilizing a regression model and Long Short-Term Memory (LSTM) to forecast the Brent oil stock price over the past two decades, commencing from 1988. In the case of the regression model, the research explores the delineation of independent variables employed to forecast the Brent oil price. Subsequently, these variables are incorporated into a regression model to anticipate future Brent oil prices.

In the LSTM approach, the historical Brent oil prices serve as input to construct a matrix, with the LSTM recognizing these values as actual prices along with the associated look-back (lag). The LSTM undergoes learning with this newly formed dataset, enabling it to predict future Brent oil prices.

## Predicting-The-Brent-Oil-Price-Using-Linear-Regression-Model
A line chart depicting the trends in the changes in brent oil stock price for the last 20 years (from 1988 to 2022) is shown below. The stock price reached its peak in 2008 and dropped significantly afterwards. It however recovered progressively after the major drop.

![](https://github.com/2-88/Time-Series-Forecasting-of-Brent-Crude-Oil-Price-Using-Regression-and-LSTM/blob/main/Picture11.png).

### Feature Engineering for the Linear Regression Model
The process was begun by installing the necessary libraries needed to implement the Linear regression model and uploading the data set.
Linear regression model requires the specification of the dependent variable and the explanatory variable (s). To build these explanatory variables which are the moving averages for the past three (MA3) and nine days (MA9) to predict brent oil prices using a linear regression model, it will require some feature engineering.  Feature engineering was used to carve the MA3 and the MA9 as the explanatory variable out of the actual brent oil prices recorded in the stock market. The actual brent oil price is the dependent variable in this case. 
Rolling Window feature engineering method was used to create the two explanatory variables as shown in the algorithm below:

![](https://github.com/2-88/Time-Series-Forecasting-of-Brent-Crude-Oil-Price-Using-Regression-and-LSTM/blob/main/Picture12.png).

Result: Five rows of the resulting output of the Rolling Window feature engineering is displayed as follows:

![]().

