# Module_11

## What is created?

A Google Colab Notebook containing the data preparation, analysis, and visualisations for all the time series data that the MercadoLibre (the most popular e-commerce site in Latin America) needs to understand. Text and comments to document the findings, and answering of the question prompts is provided.


## Provided: 

- Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
- An evaluation of how the company stock price correlates to its Google Search traffic.
- A Prophet forecast model that can predict hourly user search traffic.
- Answers to the questions in the Google Colab Notebook.
- (Optional) A plot of a forecast for the company’s future revenue.


## Steps:

- 1 - Find Unusual Patterns in Hourly Google Search Traffic
- 2 - Mine the Search Traffic Data for Seasonality
- 3 - Relate the Search Traffic to Stock Price Patterns
- 4 - Create a Time Series Model by Using Prophet
- 5 (Optional) - Forecast the Revenue by Using Time Series Models


## Findings:

### 1 - Find Unusual Patterns in Hourly Google Search Traffic

Through the creation of two seperate dataframes, one presenting the search traffic trends for 2016 to 2020, whilst the other detailing the search traffic for the month of May in 2020. Patterns in both dataframes were found through the visualisation of plots, providing evidence that the median values correlated heavily, with very little variation in the data. Therefore, dispelling the possibility that large outliers or unusual patterns exist within the Hourly Google Search Traffic Dataframe.

### 2 - Mine the Search Traffic Data for Seasonality

The visualisations presented within Step 2, supported the findings from Step 1, as the Average Search Traffic by the Week of The Year show little variance in the data, across the whole season. However, it is important to note that certain outliers in the data do exist, both the heatmap and the plot show the 19th week having a higher volume of traffic.

### 3 - Relate the Search Traffic to Stock Price Patterns

The creation of a closing price of the Mercado Stock DataFrame was created, providing the information of Mercado's yearly growth in sales. The hvplot presented a gradual growth in the sales of the company. However, market events emerged during the year of 2020 that many companies found difficult. But, after the initial shock to global financial markets, new customers and revenue increased for e-commerce platforms. Thus, with this information, plots were created in the timeframe of the shock to global the financial market was created, the time series indicate a common trend with this narrative as both plots plunged massively in sales during the initial shock. Furthermore, to accurately depict the relationship between the stock volatility and the lagged trends and the hourly stock return. In doing so, it was found that neither the lagged trends nor the hourly stock return are correlated to the stock volatility with correlation percentages of -1.5% and 6.1% respectively. Thus although the relationship between stock volatility and hourly stock return is positive, it does not hold a great percentage in correlation.

### 4 - Create a Time Series Model by Using Prophet

In Step 4 a forecasting model was prepared, fitted and created in order to find the near-term forecast for the popularity of MercadoLibre and how that popularity was distributed throughout the hour, day, week and month of the year. The forecast of MercadoLibre's popularity, was that it will continue to develop and grow as plots presented the positive increase in the future. In addition, plot components were created, in doing so, answering the question that the company is at it's peak of popularity during 12am in a day, as well as peaking in use during wednesdays. However, it is noticeable that MercadoLibre suffer negative results in popularity throughout the year, with it's lowest point (-3.5) during mid October, whilst February and June both peak at it's highest at a point of 2.5, therefore it is sensible to assume the company will continue to grow in popularity and use.

### 5 (Optional) - Forecast the Revenue by Using Time Series Models

Based on the forecast information generated within the forecasted dataframes, thus producing the sum of all values and the sales forecast for the finance division, the expected total sales next quater in it's Best Case Scenario is 8043.17, which in comparison to the Worst Case Scenario, which totalled 5796.1, a -27.937% decrease. This may present detail on the volatility of sales forecasted. However, as the Most Likely Case of forecasted sales is 6920.125, it is more possible that MercadoLibre will achieve a lesser sum then the Best Case, which is what is hoped for. However, it is sensible to assume MercadoLibre will produce profits and growth.
