# Chapter 3 - Research Methodology

### Project Title: Modelling The Impact of Oil Price and Stock Market Price on Gold Price using Long Short-Term Memory (LSTM) Model.

### Prepared by: UMMI FARIHAH BINTI ABD WAHID, MCS231032, UmmiWahid

## 3.1 Introduction
This section explains the methodology and applications that will be used in the research. Before getting to the data gathering, this chapter will examine the data description. The data must first be examined in order to accomplish the research's goal. The procedure would begin with gathering and evaluating raw data from many websites, such Trading Economics', index Mundi and Malaysia Informative Bullion Rate. The information must then be calculated using a particular formula. First, the data will be checked for cointegration between all variables and the price of gold using Johansen Cointegration model and Autoregressive Distributed Lag (ARDL). Long Short-Term Memory (LSTM) model is used in this study to predict the price of gold in Malaysia. Throughout discussion of the research findings and methodology will be covered in this chapter.


## 3.2	The Framework
I.	Problem Formulation
II.	Data Collection
III.	Data Pre-processing
IV.	Modelling
V.	Performance Validation and Evaluation

The details of the research framework for this study are shown in the Figure below.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Research%20Framework%20of%20Gold%20Price%20Prediction.JPG"/>
</p>


## 3.3	Problem Formulation
The principal objective of this research is to employ modern econometric approaches to model the influence of oil and stock market prices on gold prices, thereby offering valuable information to Malaysian policymakers and investors. However, in order to guarantee accurate and trustworthy analysis, a number of issues need to be resolved.

I.	Ensuring data quality and consistency is a major issue, as the analysis is based on monthly data from January 2013 to December 2023 for gold, crude oil, palm oil, Islamic stock market, and conventional stock market prices. Addressing potential problems with data gaps, outliers, and various data formats falls under this category.
II.	It is essential to choose and use the proper econometric models, such as the Granger Causality test, the Autoregressive Distributed Lag (ARDL) model, the Johansen Cointegration test, and the Long Short-Term Memory (LSTM) model. In order to handle the complexity of time series data, these models need to be able to capture the causality and long-term relationships between the variables.

It is critical to account for the dynamic character of the variables involved, as gold, oil, and stock market indices are all influenced by a variety of external factors such as geopolitical events, economic policy, and market mood. In order to keep the models accurate and relevant throughout time, they must be updated and improved on a regular basis while taking these dynamic factors into account.

## 3.4	Data Collection
The following datasets are carefully selected to assist in achieving our objectives. The data is obtained from official website of The World Bank Group and TradingEconomics consist of Inflation Rates, Interest Rates, and commodity prices including monthly crude oil and palm oil prices. The data includes different number of observations respectively for all datasets. Some missing data are interpolated to provide a consistent result. Furthermore, this study focuses on analysing and study the trend of commodity prices movement, relationships of different macroeconomic variables, forecasting the future inflation rate and interest rate. Each data is measured in percentage (%) for inflation and interest rates while crude oil and palm oil are measured in MYR (Malaysian Ringgit) per barrel and metric tonne.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Data%20of%20Each%20Variables.JPG"/>
</p>

From the above table, the data that represents the Islamic stock market is represented by FTSE Bursa Malaysia EMAS Shariah. While the data from the FTSE Bursa Malaysia KLCI History index provides more conventional stock market information. This research chose this website and this stock market because all Malaysian businesses listed on the Bursa Malaysia Main Market and ACE Market are eligible for inclusion, subject to achieving FTSE's worldwide standards of free float, liquidity, and invest ability. Investors can conduct international analysis and comparison using the FTSE Bursa Malaysia index methodology, and the management of the index series is transparent thanks to a set of Ground Rules. Therefore, it can be said that this data is particularly suitable for usage as one of the variables, aids in achieving the study's main goal.

Every item of data used in this study is secondary data. To be more specific, the data we collected did not match because the data on crude oil prices and palm oil prices is collected monthly rather than daily like other data. In order to synchronize the data with one another and get an accurate result, all data were evaluated and converted into monthly. It is expressed in monetary terms, specifically as Malaysian Ringgit (RM). In order to forecast the gold prices, this study chose to use 10 years period of data, from January 2013 to December 2023. This is because prior study has found that 10 years of data is sufficient to produce accurate forecasts.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.2%20Gold%20Price%2C%20Crude%20Oil%20Price%2C%20Palm%20Oil%20Price%2C%20FTSE%20Bursa%20Malaysia%20EMAS%20Shariah%20and%20FTSE%20Bursa%20Malaysia%20KLCI%20Histor.JPG"/>
</p>
<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.2%20Gold%20Price%2C%20Crude%20Oil%20Price%2C%20Palm%20Oil%20Price%2C%20FTSE%20Bursa%20Malaysia%20EMAS%20Shariah%20and%20FTSE%20Bursa%20Malaysia%20KLCI%20Histor%202.JPG"/>
</p>


## 3.5	Data Pre-processing
It is necessary to complete preliminary analysis prior to moving on to further pre-processing. A data merging procedure is necessary to bring all of the raw data into one data frame once we have a firm grasp of the features provided in the dataset. Several data wrangling and data transformation procedures will be used on the dataset in an effort to further unify the disorganised raw data. Table 3.5 below lists every detail of the data pre-processing that was used.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.3%20Data%20Pre-processing%20Methods.JPG"/>
</p>


## 3.5.1	Preliminary Analysis
Preliminary analysis is an important step in any data analysis since it helps you become acquainted with the data collection, understand its structure, format, and the sorts of variables it contains. Early investigation can identify problems that must be fixed for reliable analysis, such as missing values, outliers, or contradictions. The function ".info()" is used to retrieve the data information and gives a brief description of the dataframe. It displays every attribute information from the exported dataset, including the datatype, count of rows, and count of null counts. Figure 3.5.1 displays the gold price dataset information. The command "gold.info()" searches the dataframe "gold" for missing (NaN) values. The result indicates that all values are present. The dataset comprises 132 entries, suggesting that it is a medium-sized dataset. The dataframe comprises two columns: date and price, with datetime64[ns] and float64 as their respective datatypes.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/gold.info().JPG"/>
</p>
<p align="center">
 Figure 3.2 Data Information of Gold Price Dataset
</p>

Figure 3.5.1.2 displays the palm oil price dataset information. The command "palm_oil.info()" searches the dataframe "palm oil" for missing (NaN) values. The result indicates that all values are present. The dataset comprises 132 entries, suggesting that it is a medium-sized dataset. The dataframe comprises two columns: date and price, with datetime64[ns] and int64 as their respective datatypes.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/palm%20oil.info().JPG"/>
</p>
<p align="center">
Figure 3.3 Data Information of Palm Oil Price Dataset
</p>

The dataset information for crude oil prices is shown in Figure 3.5.1.3 The dataframe "crude oil" is searched for missing (NaN) values using the command "crude_oil.info()". According to the outcome, every value is present. Given that there are 132 entries in the dataset, it appears to be of medium size. The date and price columns in the dataframe have the datatypes datetime64[ns] and int64, respectively.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/crude.info().JPG"/>
</p>
<p align="center">
Figure 3.4 Data Information of Crude Oil Price Dataset
</p>

The information on the Islamic stock market price dataset is shown in Figure 3.5.1.4 The dataframe "Islamic Stock Market" is searched for missing (NaN) values using the command "islamic_stock.info()". According to the outcome, every value is present. Given that there are 132 entries in the dataset, it appears to be of medium size. Six columns make up the dataframe: date, price, open, high, low, and change percentage. Each column contains the datatype for each item.

<p align="center">
  <img height="400px" src="Figure 3.5 Data Information of Islamic Stock Market Price Dataset"/>
</p>
<p align="center">

</p>

## 3.5.2	Data Cleaning

## 3.5.3	Data Concatenation

## 3.6	Data Modelling



## References



## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/BDM/issues) for any improvements, suggestions or errors in the content.



[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)]
