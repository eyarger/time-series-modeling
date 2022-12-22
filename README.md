[eric-yarger.com](http://www.eric-yarger.com)

# time-series-modeling
### Time Series Modeling with ARIMA
### Using JupyterLab, Python, and a myriad of functions and tools

### Abstract
Time series analysis is a statistical tool used to analyze past data within a certain timeframe with the
goal of better forecasting the future. The Executive Team of our organization is interested in a time series on
revenue from the first two years of operation, to be used to look for patterns in our dataset. Any insights or
patterns discovered in the data have the potential to help our organization better control and manage
readmission rates. The question for this analysis is:

### 'Using Time Series Analysis, can a model be creatd that can be used to predict future revenues, which can be used by our company to better address readmission rates?'

### Process
1.  The data .csv file is loaded into a JupyterNotebook.
2.  Exploratory Data Analysis.
3.  Data Visualizations.
4.  Data Cleaning.
5.  Time Step Formatting.
6.  Stationarity Analysis
7.  Differencing of the time series.
8.  Seasonality Analysis.
9.  ACF.
10. PACF.
11. Spectral Density Analysis.
12. Create Train/Test Datasets.
13. ARIMA using pmdarima's Auto-arima.
14. Visualizing Results.
15. Accuracy Metrics.

### Table of Contents
1.  License --- GNU Affero General Public License v3.0. 

### Tools Used
1.  Python
2.  JupyterLab
3.  matplotlib.pyplot
4.  numpy
5.  scipy
6.  statsmodels.tsa.statttools.adfuller
7.  statsmodels
8.  datetime
9.  platform
10. statsmodels.graphics.tsaplots.plot_pacf
11. scipy.signal
12. pmdarmia.model_selection.train_test_split
13. pmdarima.arima.StepwiseContext
14. pmdarima.arima.auto_arima
15. sklearn.metrics.mean_squared_error
16. math.sqrt
