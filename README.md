# Walmart-Sale-Dataset-Analysis
Analysing the Walmart Dataset
# Objectives:
## 1 Importing the Libraries
The various Librabries was used for this analysis:
pandas, matplotlib, numpy, and seaborn Library

## 2 Loading of Dataset
The Dataset for this Analysis was gotten from kaggle, below is the Link to the dataset:
https://www.kaggle.com/datasets/yasserh/walmart-dataset

## 3 Dataset Information (Description)
### Description:
One of the leading retail stores in the US, Walmart, would like to predict the sales and demand accurately. There are certain events and holidays which impact sales on each day. There are sales data available for 45 stores of Walmart. The business is facing a challenge due to unforeseen demands and runs out of stock some times, due to the inappropriate machine learning algorithm. An ideal ML algorithm will predict demand accurately and ingest factors like economic conditions including CPI, Unemployment Index, etc.

Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of all, which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data. Historical sales data for 45 Walmart stores located in different regions are available.

### About the features
Add Suggestion This is the historical data that covers sales from 2010-02-05 to 2012-11-01, in the file Walmart_Store_sales. Within this file you will find the following fields:\

* Store - the store number: 
* Date - the week of sales: 
* Weekly_Sales - sales for the given store
* Holiday_Flag - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
* Temperature - Temperature on the day of sale
* Fuel_Price - Cost of fuel in the region
* CPI – Prevailing consumer price index (its the sum of price changes over a period of time for a particular commodity)
* Unemployment - Prevailing unemployment rate
* Holiday Events
1. Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
2. Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
3. Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
4. Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

### 4 Data Information and Insights - Exploratory Data Analysis
Below are the general insights gotten from the Analysis 
  1. The dataset contains 6435 rows and 8 columns
  2. The Unemployment and Temperature columns might contain some outliers
  3. The dataset contains 2 categorical columns and 5 numeric columns and 1 object (date)
  4. We have 45 walmat stores
  5. The dataset has no null value
  6. The dataset does not have any duplicates
  7. Almost all of the dataset are float64 numbers, just two int64 and one object which is the date
  8. year 2010, 2011 and 2012 has total sales count of 2160, 2340 and 1935 respectively
  9. year 2010 has the Highest weekly_sales of 1,059,670 USD in the dataset
  10. December has the highest Average Weekly_sales of 1,281,864 USD across the dataset
  11. store 20 has the Highest Average Weekly_Sales of 2,107,677 USD
  12. store 14 has the highest Average sales of 2,197,130 USD  in the year 2010 across the dataset
  13. store 33 has the list Average sales of 2,491,892 USD in 2011
  14. it was observered that over 25 stores made their highest sales in year 2010
  15. It was observed that During the Holiday sales, on an average, the stores made the best sales than normal days, Holidays sales is 1,122,888 USD while non Holidays sales is 1,041,256 USD
  16. We also observed that the Thanksgiving Holidays has the hightest sales of 1,471,273 USD on an average, that is to say that the walmat stores makes alot of sales during the Thanksgiving holiday period
  17. From the analysis, we can ascertain that even though the Thanksgiving Holiday has the highest sales, but the Labour Day and Super Bowl Holiday has the highest sales count of 135 each.
  18. There is no correlation between the Temperature, Fuel Price and the Weekly Sales the Temperation and the Weekly_Sales has -0.064 correlation value, while the Fuel Price and the Weekly Sales has 0.0095 correlation value, which is insignificant
  19. From the analysis, we can conclude that cost of fuel and Temperature has no effect on the Weekly Sales value, no correlation
  20. so we can say that the unemployment rate in a particular region can affect the weekly sales in a particular store even though its significance is not much i.e -0.11 correlation value which is a very week negative correlation
  21. From the analysis, we noticed that there is an upward trend in the CPI value, i.e to say at weekly interval and increase in Month and Year, the price of commodities increase in the various stores
  22. Extending No. 21 insight, it was finally observed that despite the upward trend in the CPI values, it has little or no linear relationship on the weekly sales, even thou we are having a clustered chart where certain value of CPI has a particular sales but very week linear relationship or no relationship.

### 5 Visualization:
#### The year that has the highest Average sales on the sales day
![1717434978190](image/Readme/1717434978190.png)

#### Stores year weekly_sales

#### Comapring the Sales in Holidays and non-Holidays

#### Highest Average weekly_sales on Holidays

#### Does the Temperature and fuel cost has any effect on the week sales

#### What is the relationship between the prevailing unemployment rate and the weekly sales

#### Checking if the CPI on the store increases or decreases by time across the dataset and among the different stores

#### Checking if the Relationship between the CPI and the Weekly Sales


