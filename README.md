# Gold And Silver Prices using ARIMA in Python

## About the project

The main objective of thye project is to apply the knowlegde gained from [Econometrics: Methods and Applications](https://www.coursera.org/learn/erasmus-econometrics) 

My work during the Course can be found [here](https://github.com/SanjayShetty01/Econometrics_Methods_and_Applications)

### The Dataset

The data was pulled using [yahoofinancials](https://pypi.org/project/yahoofinancials/) package, Although not important to the project, the package also allows the user to pull down financial statements from Yahoo! Finance, So do check it out! The data pulled from yahoo! Finance are Gold and Silver future prices from [COMEX](https://www.cmegroup.com/) The data were dictionary type, which consists of both the bullion's OHLC prices from September 2016- September 2021.

### Preprocessing

The preprocessing was done using basic techniques like dropping all the rows with missing values and later only the closing price of the data was kept and all other (i.e Open, High and Low) were dropped. since we would only be predicting the closing price of the Gold and the Silver.  

