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
  <img height="600px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Research%20Framework%20of%20Gold%20Price%20Prediction.JPG"/>
</p>


## 3.3	Problem Formulation
The principal objective of this research is to employ modern econometric approaches to model the influence of oil and stock market prices on gold prices, thereby offering valuable information to Malaysian policymakers and investors. However, in order to guarantee accurate and trustworthy analysis, a number of issues need to be resolved.

I.	Ensuring data quality and consistency is a major issue, as the analysis is based on monthly data from January 2013 to December 2023 for gold, crude oil, palm oil, Islamic stock market, and conventional stock market prices. Addressing potential problems with data gaps, outliers, and various data formats falls under this category.
II.	It is essential to choose and use the proper econometric models, such as the Granger Causality test, the Autoregressive Distributed Lag (ARDL) model, the Johansen Cointegration test, and the Long Short-Term Memory (LSTM) model. In order to handle the complexity of time series data, these models need to be able to capture the causality and long-term relationships between the variables.

It is critical to account for the dynamic character of the variables involved, as gold, oil, and stock market indices are all influenced by a variety of external factors such as geopolitical events, economic policy, and market mood. In order to keep the models accurate and relevant throughout time, they must be updated and improved on a regular basis while taking these dynamic factors into account.

## 3.4	Data Collection
The following datasets are carefully selected to assist in achieving our objectives. The data is obtained from official website of The World Bank Group and TradingEconomics consist of Inflation Rates, Interest Rates, and commodity prices including monthly crude oil and palm oil prices. The data includes different number of observations respectively for all datasets. Some missing data are interpolated to provide a consistent result. Furthermore, this study focuses on analysing and study the trend of commodity prices movement, relationships of different macroeconomic variables, forecasting the future inflation rate and interest rate. Each data is measured in percentage (%) for inflation and interest rates while crude oil and palm oil are measured in MYR (Malaysian Ringgit) per barrel and metric tonne.

<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Data%20of%20Each%20Variables.JPG"/>
</p>

From the table 3.1, the data that represents the Islamic stock market is represented by FTSE Bursa Malaysia EMAS Shariah. While the data from the FTSE Bursa Malaysia KLCI History index provides more conventional stock market information. This research chose this website and this stock market because all Malaysian businesses listed on the Bursa Malaysia Main Market and ACE Market are eligible for inclusion, subject to achieving FTSE's worldwide standards of free float, liquidity, and invest ability. Investors can conduct international analysis and comparison using the FTSE Bursa Malaysia index methodology, and the management of the index series is transparent thanks to a set of Ground Rules. Therefore, it can be said that this data is particularly suitable for usage as one of the variables, aids in achieving the study's main goal.

Every item of data used in this study is secondary data. To be more specific, the data we collected did not match because the data on crude oil prices and palm oil prices is collected monthly rather than daily like other data. In order to synchronize the data with one another and get an accurate result, all data were evaluated and converted into monthly. It is expressed in monetary terms, specifically as Malaysian Ringgit (RM). In order to forecast the gold prices, this study chose to use 10 years period of data, from January 2013 to December 2023. This is because prior study has found that 10 years of data is sufficient to produce accurate forecasts.

<p align="center">
  <img height="500px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.2%20Gold%20Price%2C%20Crude%20Oil%20Price%2C%20Palm%20Oil%20Price%2C%20FTSE%20Bursa%20Malaysia%20EMAS%20Shariah%20and%20FTSE%20Bursa%20Malaysia%20KLCI%20Histor.JPG"/>
</p>
<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.2%20Gold%20Price%2C%20Crude%20Oil%20Price%2C%20Palm%20Oil%20Price%2C%20FTSE%20Bursa%20Malaysia%20EMAS%20Shariah%20and%20FTSE%20Bursa%20Malaysia%20KLCI%20Histor%202.JPG"/>
</p>


## 3.5	Data Pre-processing
It is necessary to complete preliminary analysis prior to moving on to further pre-processing. A data merging procedure is necessary to bring all of the raw data into one data frame once we have a firm grasp of the features provided in the dataset. Several data wrangling and data transformation procedures will be used on the dataset in an effort to further unify the disorganised raw data. Table 3.3 below lists every detail of the data pre-processing that was used.

<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%203.3%20Data%20Pre-processing%20Methods.JPG"/>
</p>


## 3.5.1	Preliminary Analysis
Preliminary analysis is an important step in any data analysis since it helps you become acquainted with the data collection, understand its structure, format, and the sorts of variables it contains. Early investigation can identify problems that must be fixed for reliable analysis, such as missing values, outliers, or contradictions. The function ".info()" is used to retrieve the data information and gives a brief description of the dataframe. It displays every attribute information from the exported dataset, including the datatype, count of rows, and count of null counts. Figure 3.2 displays the gold price dataset information. The command "gold.info()" searches the dataframe "gold" for missing (NaN) values. The result indicates that all values are present. The dataset comprises 132 entries, suggesting that it is a medium-sized dataset. The dataframe comprises two columns: date and price, with datetime64[ns] and float64 as their respective datatypes.

<p align="center">
  <img height="200px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/gold.info().JPG"/>
</p>
<p align="center">
 Figure 3.2 Data Information of Gold Price Dataset
</p>

Figure 3.3 displays the palm oil price dataset information. The command "palm_oil.info()" searches the dataframe "palm oil" for missing (NaN) values. The result indicates that all values are present. The dataset comprises 132 entries, suggesting that it is a medium-sized dataset. The dataframe comprises two columns: date and price, with datetime64[ns] and int64 as their respective datatypes.

<p align="center">
  <img height="200px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/palm%20oil.info().JPG"/>
</p>
<p align="center">
Figure 3.3 Data Information of Palm Oil Price Dataset
</p>

The dataset information for crude oil prices is shown in Figure 3.4 The dataframe "crude oil" is searched for missing (NaN) values using the command "crude_oil.info()". According to the outcome, every value is present. Given that there are 132 entries in the dataset, it appears to be of medium size. The date and price columns in the dataframe have the datatypes datetime64[ns] and int64, respectively.

<p align="center">
  <img height="200px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/crude.info().JPG"/>
</p>
<p align="center">
Figure 3.4 Data Information of Crude Oil Price Dataset
</p>

The information on the Islamic stock market price dataset is shown in Figure 3.5 The dataframe "Islamic Stock Market" is searched for missing (NaN) values using the command "islamic_stock.info()". According to the outcome, every value is present. Given that there are 132 entries in the dataset, it appears to be of medium size. Six columns make up the dataframe: date, price, open, high, low, and change percentage. Each column contains the datatype for each item.

<p align="center">
  <img height="200px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/islamic%20stock.info().JPG"/>
</p>
<p align="center">
Figure 3.5 Data Information of Islamic Stock Market Price Dataset
</p>

The traditional stock market price dataset information is shown in Figure 3.6. The dataframe "conventional stock market" is searched for missing (NaN) values using the command "conventional_stock.info()". According to the outcome, every value is present. Given that there are 132 entries in the dataset, it appears to be of medium size. The dataframe has six columns: date, open, high, low, close, adj close, and volume. The datatypes for each column are objects and float64.

<p align="center">
  <img height="200px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/conventional%20stock.info().JPG"/>
</p>
<p align="center">
Figure 3.6 Data Information of Conventional Stock Market Price Dataset
</p>


## 3.5.2	Data Cleaning
In order to identify missing values and eliminate rows and columns with no values, data cleaning is done in this part. Figure 3.7 shows that while all datasets are free of missing values, some of the columns are not relevant to our research. It is therefore necessary to eliminate the following columns: 'Open', 'High', 'Low', 'Change %' from the Islamic stock market price dataset; and 'Open', 'High', 'Low', 'Close', 'Volume' from the conventional stock market price dataset. The process of removing these columns is depicted in Figure 3.8. The Islamic stock market price dataset now consists solely of date and price columns, whereas the traditional stock market price dataset only includes date and adj close columns.

<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/duplicate.JPG"/>
</p>
<p align="center">
Figure 3.7 Data Cleaning for All Datasets
</p>

<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/drop%20column%20islamic.JPG"/>
</p>
<p align="center">
Figure 3.8 Drop Unnecessary Column
</p>

## 3.5.3	Data Concatenation
A method for combining data from related datasets into a single, cohesive dataset in data analysis is called data concatenation. Since our data is gathered gradually in batches, it is crucial to this research that we combine all datasets from January 2013 to December 2023. This enables us to combine all of the datasets into one for analysis. An example of how we concatenate data across all datasets is shown in Figure 3.9.

<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/concat().JPG"/>
</p>
<p align="center"> 
Figure 3.9 Data Concatenation on Merge Dataset
</p>

## 3.6	Data Modelling
The primary aim of this research is to model the impact of oil price and stock market price on gold price using advanced econometric techniques. The process begins with the collection of time series data, encompassing historical records of gold price, crude oil price, palm oil price, Islamic stock market price, and conventional stock market price, measured over monthly intervals from January 2013 to December 2021. This data must then undergo a series of pre-processing steps to ensure its suitability for modeling. Pre-processing includes handling missing values, converting data types, and ensuring the data is stationary—a requirement for many time series models. Stationarity is achieved through techniques like differencing to remove trends and seasonal structures. Figure 3.10 will show the framework of how VAR model methodology for forecasting gold price.

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Figure%203.10%20LSTM%20Model%20for%20Gold%20Price%20Forecasting%20Methodology.JPG"/>
</p>

Once the data is prepared, it is divided into training and testing datasets. This division is essential for validating the model's effectiveness at making forecasts. For this research, the Johansen Cointegration test is employed to determine the long-term equilibrium relationships between the variables. Additionally, the Granger Causality test is used to identify the directional influences between the time series.

The Autoregressive Distributed Lag (ARDL) model is then applied, which is suitable for analyzing the dynamic relationships between the variables over both the short and long term. The ARDL model parameters—lag orders of autoregressive (AR) and moving average (MA) components—are meticulously selected using criteria like the Akaike Information Criterion (AIC) and the Bayesian Information Criterion (BIC). This step is crucial as it lays the foundation for how well the model will understand and predict the time series data's behavior.

The model fitting is the next phase, where the ARDL model, armed with the optimal parameters, is trained on the historical data. Upon training, the model's accuracy is evaluated using metrics such as the Root Mean Squared Error (RMSE) and the Mean Absolute Percentage Error (MAPE), which provide quantitative measures of the model's predictive performance. Additionally, the Long Short-Term memory (LSTM) model is employed for forecasting future values of the time series. These forecasts can be particularly valuable for planning and decision-making processes in the financial sector.

Lastly, the model's predictions are visualized against actual data for a comparative analysis, providing an intuitive and clear assessment of its forecasting capabilities. The visualizations include time series plots and scatter plots that compare predicted and actual values, helping to identify the model's strengths and areas for improvement.

## References
1. Abbas, G., Bhowmik, R., Koju, L., & Wang, S. (2017). Cointegration and causality relationship between stock market, money market and foreign exchange market in Pakistan. Journal of Systems Science and Information, 5(1), 1-20. https://doi.org/10.21078/jssi-2017-001-20
2. Abdallah, W., Goergen, M., & O’Sullivan, N. (2015). Endogeneity: How failure to correct for it can cause wrong inferences and some remedies. British Journal of Management, 26(4), 791-804. https://doi.org/10.1111/1467-8551.12113
3. Ahmad, Z. (2019). Analyzing causation of dynamic oil and gold prices in Malaysia. Journal of Global Business and Social Entrepreneurship (GBSE), 5(15). www.gbse.com.my
4. Ali, M., Tursoy, T., Samour, A., Moyo, D., & Konneh, A. (2022). Testing the impact of the gold price, oil price, and renewable energy on carbon emissions in South Africa: Novel evidence from bootstrap ARDL and NARDL approaches. Resources Policy, 79. https://doi.org/10.1016/j.resourpol.2022.102984
5. Asila Jalil. (2022, January 1). Demand for gold bars increase 30pc this year, says Habib Jewels. New Straits Times.
6. Aydin, A. D., & Cavdar, S. C. (2015). Comparison of prediction performances of artificial neural network (ANN) and vector autoregressive (VAR) models by using the macroeconomic variables of gold prices, Borsa Istanbul (BIST) 100 index and US Dollar-Turkish Lira (USD/TRY) exchange rates. Procedia Economics and Finance, 30, 3-14. https://doi.org/10.1016/s2212-5671(15)01249-6
7. Ayisy Yusof. (2021, February 1). Oil price faces Covid-19 threat. New Straits Times.
8. Azreen, N., Razak, A., Khamis, A., Asrul, M., & Abdullah, A. (2017). ARIMA and VAR modeling to forecast Malaysian economic growth. Journal of Science and Technology, 9(3).
9. Bahloul, S., & Khemakhem, I. (2021). Dynamic return and volatility connectedness between commodities and Islamic stock market indices. Resources Policy, 71. https://doi.org/10.1016/j.resourpol.2021.101993
10. Bank for International Settlements. Monetary and Economic Department. (2005). Globalisation and monetary policy in emerging markets. Bank for International Settlements.
11. Basiron, Y. (2009, March 1). Trends and potentials of Malaysia’s plantation sector. In A presentation by Tan Sri Datuk Dr Yusof Basiron at the Perdana Leadership Foundation Seminar.
12. Bernama. (2023, January 1). Public gold: Malaysian gold market to move south in 2023, bucking international trend. Borneo Post.
13. Bildirici, M. E., & Turkmen, C. (2015). Nonlinear causality between oil and precious metals. Resources Policy, 46, 202-211. https://doi.org/10.1016/j.resourpol.2015.09.002
14. Bildirici, M., & Türkmen, C. (2015). The chaotic relationship between oil return, gold, silver and copper returns in Turkey: Non-linear ARDL and augmented non-linear Granger causality. Procedia - Social and Behavioral Sciences, 210, 397-407. https://doi.org/10.1016/j.sbspro.2015.11.387
15. Boubaker, H., Cunado, J., Gil-Alana, L. A., & Gupta, R. (2020). Global crises and gold as a safe haven: Evidence from over seven and a half centuries of data. Physica A: Statistical Mechanics and Its Applications. https://www.measuringworth.com/datasets/gold/
16. Bromberg, M. (2023). Why gold matters: Everything you need to know. Investopedia. https://www.investopedia.com/articles/economics/09/why-gold-matters.asp
17. Capie, F., Mills, T. C., & Wood, G. (2005). Gold as a hedge against the dollar. Journal of International Financial Markets, Institutions and Money, 15(4), 343-352.
18. Caplinger, D. (2014, January 1). Price of gold in 2014: Why it’s gone nowhere. The Motley Fool.
19. Chai, J., Zhao, C., Hu, Y., & Zhang, Z. G. (2021). Structural analysis and forecast of gold price returns. Journal of Management Science and Engineering, 6(2), 135-145. https://doi.org/10.1016/j.jmse.2021.02.011
20. Chikri, H., & Hamiche, M. (2020). The impact of the oil and gold price shock on Islamic and conventional stock market indices: Evidence from the DCC-GARCH model. PJAEE, 17(6).
21. Chkili, W. (2022). The links between gold, oil prices and Islamic stock markets in a regime switching environment. Eurasian Economic Review, 12(1), 169-186. https://doi.org/10.1007/s40822-022-00202-y
22. Christiano, L. J. (2012). Christopher A. Sims and vector autoregressions. Scandinavian Journal of Economics, 114(4), 1082-1104. https://doi.org/10.1111/j.1467-9442.2012.01737.x
23. Fritzer, F., Moser, G., & Scharler, J. (2002). Forecasting Austrian HICP and its components using VAR and ARIMA models. http://hdl.handle.net/10419/264665
24. Gao, X., Huang, S., Sun, X., Hao, X., & An, F. (2018). Modelling cointegration and Granger causality network to detect long-term equilibrium and diffusion paths in the financial system. Royal Society Open Science, 5(3). https://doi.org/10.1098/rsos.172092
25. Garside, M. (2023). Gold production ranked by major countries 2022. Statista.
26. Go, Y. H., & Lim, W. Y. (2017). The relationship of crude palm oil spot-futures under inflationary expectation in gold market. Capital Markets Review.
27. Guglielmo, M., Caporale, J., Hunter, F., & Menla, A. (2013). On the linkages between stock prices and exchange rates: Evidence from the banking crisis of 2007-2010. http://www.diw.de/discussionpapers
28. Gumis, S. (2020). Malaysia: Investment in the gold mining sector in Malaysia. SKRINE.
29. Hammad, W., Hamdan, A., Al-Ameer, M., & Ismail, A. (2018). The relationship of gold price with the stock market: The case of Frankfurt stock exchange. International Journal of Energy Economics and Policy, 8(5), 357-371. http://www.econjournals.com
30. Hatemi-J, A., & Hacker, R. S. (2008). Optimal lag-length choice in stable and unstable VAR models under situations of homoscedasticity and ARCH. Journal of Applied Science.
31. Hayati, N., & Rahman, A. (2011). A time series analysis of the relationship between total area planted, palm oil price and production of Malaysian palm oil. World Applied Sciences Journal. https://www.researchgate.net/publication/295460953
32. Hidalgo, F. D., & Sekhon, J. S. (2009). Causality. In International Encyclopedia of Political Science.
33. Ibrahim, S. N., Hasan, R., & Nor, A. M. (2018). Does gold price lead or lag Islamic stock market and strategy commodity price? A study from Malaysia. International Journal of Business, Economics and Management, 5(6), 146-163. https://doi.org/10.18488/journal.62.2018.56.146.163
34. Jabeur, S. B., Mefteh-Wali, S., & Viviani, J. L. (2021). Forecasting gold price with the XGBoost algorithm and SHAP interaction values. Annals of Operations Research. https://doi.org/10.1007/s10479-021-04187-w
35. Jain, A., & Biswal, P. C. (2016). Dynamic linkages among oil price, gold price, exchange rate, and stock market in India. Resources Policy, 49, 179-185. https://doi.org/10.1016/j.resourpol.2016.06.001
36. Jena, S., et al. (2022). A comprehensive review on deep learning models for financial time series forecasting. Journal of Computational Finance and Data Science, 10(3), 215-233.
37. Karia, A. A., & Bujang, I. (2011). Progress accuracy of CPO price prediction: Evidence from ARMA family and artificial neural network approach. International Research Journal of Finance and Economics. http://www.eurojournals.com/finance.htm
38. Khan, Md. S., & Khan, U. (2020). Comparison of forecasting performance with VAR vs. ARIMA models using economic variables of Bangladesh. Asian Journal of Probability and Statistics, 33-47. https://doi.org/10.9734/ajpas/2020/v10i230243
39. Koh, W. C., & Baffes, J. (2020). Gold shines bright throughout the COVID-19 crisis. World Bank.
40. Kristjanpoller, W., Fadic, A., & Minutolo, M. (2021). Forecasting volatility of gold price using an LSTM model with news sentiment analysis. Expert Systems with Applications, 163, 113829.
41. Mani. (2019). Gold price vs stock market: Gold and equity have an inverse relationship. Get Money Rich.
42. Maxwell, T. (2022). Why you should buy gold during inflation. CBS News.
43. Mukhuti, S., & Bhunia, A. (2013). Is it true that Indian gold price influenced by Indian stock market reaction? E3 Journal of Business Management and Economics, 4(8), 181-186. http://www.e3journals.org
44. Nomran, N. M., & Haron, R. (2021). The impact of COVID-19 pandemic on Islamic versus conventional stock markets: International evidence from financial markets. Future Business Journal, 7(1). https://doi.org/10.1186/s43093-021-00078-5
45. Nordin, N., Nordin, S., & Ismail, R. (2014). The impact of commodity prices, interest rate and exchange rate on stock market performance: An empirical analysis from Malaysia. Malaysian Management Journal, 18.
46. Othman, N., & Masih, M. (2018). Granger-causality between palm oil, gold and stocks (Islamic and conventional): Malaysian evidence based on ARDL approach. Munich Personal RePEc Archive.
47. Pesaran, M. H., Shin, Y., & Smith, R. J. (2001). Bound testing approaches to the analysis of long run relationships. Journal of Applied Econometrics, 16(3), 289-326.
48. Phaladisailoed, T., & Naruetharadhol, P. (2019). Machine learning models comparison for gold price prediction. Procedia Computer Science, 156, 287-295.
49. Rahman, H. A. A., Azizi, M. F. R., Saruand, M. F., & Shafie, N. A. (2022). Forecasting of Malaysia gold price with exponential smoothing. Journal of Science and Technology.
50. Rajab, K., Kamalov, F., & Cherukuri, A. K. (2022). Forecasting COVID-19: Vector autoregression-based model. Arabian Journal for Science and Engineering, 47(6), 6851-6860. https://doi.org/10.1007/s13369-021-06526-2
51. Roberts, M. R., & Whited, T. M. (2013). Endogeneity in empirical corporate finance. In Handbook of the Economics of Finance (Vol. 2, Issue PA, pp. 493-572). Elsevier B.V. https://doi.org/10.1016/B978-0-44-453594-8.00007-0
52. Sørensen, B. E. (2019). Cointegration. In Economics 266.
53. Statista Research Department. (2022). Palm oil consumption in Malaysia from 2011/2012 to 2020/2021. Statista. https://www.statista.com/statistics/489441/palm-oil-consumption-malaysia/
54. Stevans, L. K. (2012). Time series review. SSRN Electronic Journal. https://doi.org/10.2139/ssrn.1767999
55. Stoklasová, R. (2018). Short-term and long-term relationships between gold prices and oil prices.
56. Syahri, A., & Robiyanto, R. (2020). The correlation of gold, exchange rate, and stock market on COVID-19 pandemic period. Jurnal Keuangan dan Perbankan, 24(3). https://doi.org/10.26905/jkdp.v24i3.4621
57. Taha Abdullah, L. (2022). Forecasting time series using vector autoregressive model. International Journal of Nonlinear Analysis and Applications, 13, 2008-6822. https://doi.org/10.22075/ijnaa.2022.5521
58. Tai, C.-S. (2007). Market integration and contagion: Evidence from Asian emerging stock and foreign exchange markets. Emerging Markets Review.
59. Thakolsri, S. (2021). Modeling the relationships among gold price, oil price, foreign exchange, and the stock market index in Thailand. Investment Management and Financial Innovations, 18(2), 261-272. https://doi.org/10.21511/imfi.18(2).2021.21
60. Trefis Team. (2014). Reasons for the recent decline in gold prices. Forbes.
61. Tursoy, T., & Faisal, F. (2018). The impact of gold and crude oil prices on stock market in Turkey: Empirical evidences from ARDL bounds test and combined cointegration. Resources Policy, 55, 49-54. https://doi.org/10.1016/j.resourpol.2017.10.014
62. Vveinhardt, J., Streimikiene, D., & Raheem Ahmed, R. (2018). Asymmetric influence of oil and gold prices on Baltic and South Asian stock markets: Evidence from Johansen cointegration and ARDL approach. SALU-Commerce & Economics Review, 4(1). https://www.researchgate.net/publication/322900068
63. Wang, M. L., Po, W. C., & Yang, H. T. (2010). Relationships among oil price, gold price, exchange rate and international stock markets. International Research Journal of Finance and Economics, 47, 1450-2887.
64. Wen, F., Yang, X., Gong, X., & Lai, K. K. (2017). Multi-scale volatility feature analysis and prediction of gold price. International Journal of Information Technology and Decision Making, 16(1), 205-223. https://doi.org/10.1142/S0219622016500504
65. Yahya, M., Muhammad, F., Razak, A. A., Gan, P.-T., Hussin, M., Tha, G. P., & Marwan, N. (2013). The link between gold price, oil price and Islamic stock market: Experience from Malaysia. International Journal of Business and Social Science, 4(2), 161-182. https://www.researchgate.net/publication/306536880
66. Yau, D. L. I., Ching, C. P., Hwang, J. Y. T., Sin, K. Y., & Janang, S. K. Y. (2021). Does the factors affecting gold price change during COVID-19 period in Malaysia? International Journal of Academic Research in Business and Social Sciences, 11(9). https://doi.org/10.6007/ijarbss/v11-i9/10761
67. Yun, Y. X. (2020). Gold prices drop in wake of vaccine development. The Star.
68. Zaidi, A., Shah, A., Karim, N., Roman, M., Azlan, M., Zaidi, S., Karim, Z. A., & Zaidon, N. A. (2021). External and internal shocks and the movement of palm oil price: SVAR evidence from Malaysia. Economies. https://doi.org/10.3390/economies
69. Zach. (2021). How to perform a Granger-causality test in R. Statistics Globe. https://www.statology.org/granger-causality-test-r/


## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/BDM/issues) for any improvements, suggestions or errors in the content.



[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)]
