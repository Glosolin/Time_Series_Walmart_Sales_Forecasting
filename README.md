# Time_Series_Walmart_Sales_Forecasting

## Overview  
This project focuses on forecasting retail sales using **time series models**.  We analyze Walmart's hierarchical sales data to predict future weekly sales trend, by implementing  **ARIMA/SARMIMA** and **Gaussian Processes (GP)**. We also aim to evaluate the models based on their accuracy, robustness, and computational efficiency.  

## Dataset  
The dataset we use is hierarchical sales data from Walmart Daily Sales ranging from Jan 28th 2011 to Jun 18th 2016, containing sales information of products in three categories (Food, Hobby, Household) sold in three states (California, Texas, Wisconsin). For prediction, we aggregate the daily sales into weekly sales data in three categories sold in three states. 

## Methodology
We use drill-down analysis to dissect the data at a more granular level: for each category and each state, we compare ARIMA/SARMIA and GP model's performance on our test data using RMSE metric for best model selection. 


### Data Preprocessing
- Aggregate daily sales to weekly for forecasting with pandas groupby, reduing noise and making patterns more discernable
- Remove the first week of sales data as it did not represent a full week to avoid skewing the model
- Divide the dataset into training (first 267 weeks) and test (last 10 weeks) sets to evaluate the performance of our time series models

![](/images/data_overview.png)

### Model Selection
#### Why ARIMA/SARIMA?

####  Why Gaussian Processes (GP)?


## Results


## Conclusion
