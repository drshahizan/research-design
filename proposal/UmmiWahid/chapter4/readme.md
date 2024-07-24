# Chapter 4 - Exploratory Data Analysis (EDA)

### Project Title: Modelling The Impact of Oil Price and Stock Market Price on Gold Price using Long Short-Term Memory (LSTM) and Vector Autoregression (VAR) Model.

### Prepared by: UMMI FARIHAH BINTI ABD WAHID, MCS231032, UmmiWahid

## 4.1 Introduction
## 4.1.1	Gold Price
<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/gold%20graph.JPG"/>
</p>
<p align="center">
Figure 4.1 Trend of Gold Price
</p>

Gold is a valuable metal to the economy as it is said to be the main commodity to the country. It also serves as a means of wealth storage in industrial commodities, which is crucial especially during times of political and economic disruption. The overall trend was upwards, with natural fluctuations occurring during the time period. The price of gold was at its highest from 2022 to 2023, during COVID-19 which has affected the global economy and caused people to be afraid to spend. According to (Wee Chian Koh & John Baffes, 2020), the price of gold is predicted to increase by an average of 13% in 2020 compared to 2019 due to high demand carried on by increased global hesitation and historically low real interest rates. The threat of COVID-19 is also causing investors to choose gold as a safe asset (Yau et al., 2021). Even so, as news of the discovery of COVID-19 vaccine spread, it reduced the risk of the COVID-19 threat, with economists and investors expecting the global economy to recover.

Based on the figure 4.1, the price of gold was at the lowest in 2014. The conflict between Ukraine and Russia is not showing any signs of continuing in 2014, which is causing the global economy to recover (Dan Caplinger, 2014). Besides, the manufacturing Purchasing Managers Index (PMI) assesses business conditions in the economy's manufacturing sector (Trefis Team, 2014). When the PMI is greater than 50, it indicates that business activity is expanding, while a value less than 50 indicates that business activity is contracting. In 2014, the manufacturing PMI has consistently registered values above 50 for all months. This has caused the US dollar to strengthen, boosting expectations of an increase in interest rates. Hence, as investors turn to interest-bearing assets, an increase in interest rate is likely to cause a drop in the price of gold.



## 4.1.2	Oil Price
<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/palm%20oil%20graph.JPG"/>
</p>

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/crude%20oil%20graph.JPG"/>
</p>
<p align="center">
Figure 4.2 Trend of Oil Price
</p>

Figure 4.2 shows the fluctuation through the period of 2013 until 2023 for crude oil price and palm oil price. It presents the crude palm oil price drop drastically in the year 2020. The COVID-19 pandemic in 2020 caused crude oil prices to plummet as oil demand fell sharply as a result of lockdowns and travel restrictions. Due to encompassing stay-athome orders, it moves the world toward low-cost green or clean energy that could have an impact on crude oil prices (Ayisy Yusof, 2021). According to Mead and Stiger (2015) petroleum prices rose sharply influenced by various factors and it continues to exert upward pressure in 2013. Strong economic growth in developed countries but lower interest rate like, United States and China strengthen worldly crude oil price including the Malaysian crude Oil Price. Sudden drops of crude price after 2013 is believed due to the global crisis where the supply gut is growing yet there was a sharp contraction in energy investment in the United States. This has to be one of the largest oil prices declines where the other two biggest price declines were during World War II and Supply-Driven collapse of 1986 (Stocker et. al,2018).

The next graph is palm oil price that present seasonality over the year. Based on the graph, it can be seen that the price of Palm Oil is having an average of RM 3000 per tons over the period of 2013 to 2019 before an increase from to 2020 and the following years. Being one of the biggest palm oil producers in East Asia yet not producing an efficient amount of the oil, it is believed due to the lack’s infrastructure. Across Peninsular Malaysia, land for palm oil expansion is limited which mostly has been placed with urban development (Mark, 2022). Although there are growing palm oil land in Sabah and Sarawak but the only expendable palm oil plantation areas are in Sarawak. Apart from that, the price of oil increase drastically from 2020 because of low CPO production, rising soybean oil prices, Brent Crude Oil price increases, and strong palm oil exports in key markets all contributed to the increase in CPO prices. The price became the highest compared to past year before COVID-19 pandemic hit the world (Cheryl Poo, 2022).


## 4.1.3	Stock Market Price
<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/islamic%20stock%20graph.JPG"/>
</p>

<p align="center">
  <img height="400px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/conventional%20stock%20graph.JPG"/>
</p>
<p align="center">
Figure 4.3 Trend of Stock Market Price
</p>

Lastly, the figure 4.3 shows the graph of stock market for both conventional and Islamic stock market price shows the fluctuation from 2013 to 2021 but was at the lowest during 2020. It slowed down because investors were afraid to invest due to the worst economic downturn crisis. Financial system crises, such as the current pandemic, information about Islamic investment systems has piqued the curiosity of investors who view the returns of stocks as uncertain (Nomran & Haron, 2021).

As they are traded on the same market in Bursa Malaysia yet have distinct results, this also suggests that there are important performance concerns to be investigated among the indices. In order to help investors, fund managers, and other market players in making decisions about their investments and finances, it is necessary to study the information on the integration between these two graphs. Additionally, this stock market integration will make it possible to gather some crucial data, allowing decision-makers to create efficient market strategies and suitable regulations to guarantee Malaysia's financial markets remain strong and stable. Information about this integration is also crucial because it will increase domestic investment and savings, which will increase productivity and accelerate economic growth (Bank for International Settlements. Monetary and Economic Department, 2005). It will also lower capital costs in an integrated market because it will share risk with domestic and international economic activities (Tai, 2007).


## 4.2	Descriptive Analysis
<p align="center">
  <img height="300px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Table%204.1%20Descriptive%20Analysis.JPG"/>
</p>

The table above provides a complete descriptive analysis of several financial parameters over a 10-year period, with a focus on Palm Oil Price (MYR), Crude Oil Price (MYR), Islamic Stock Market Price (MYR), Conventional Stock Market Price (MYR), and Gold Price (MYR). Statistical metrics including count, mean, standard deviation (std), minimum (min), 25th percentile (25%), median (50%), 75th percentile (75%), and maximum (max) values are displayed for each distinct financial indication that is represented by a column. This data gives information about the central tendency, dispersion, and overall distribution of several financial variables.

With an average price of 2956.55 and a standard deviation of 985.30, the palm oil price (MYR) exhibits significant price volatility. A broad range of values is suggested by the fact that the smallest recorded price is 1929.00, while the maximum is substantially higher at 7104.00. Comparably, the value of the Crude Oil Price (MYR) exhibits a mean of 278.57 and a standard deviation of 89.12, with values varying between 91.64 and 546.13. These numbers demonstrate how several market and geopolitical events impact the price of commodities.

Both the Islamic and Conventional stock market indices, as well as the gold price (MYR), exhibit unique patterns. The range of values for the Islamic Stock Market Price (MYR) is 10008.03 to 13658.05. Its mean is 12168.67 and its standard deviation is 845.34. Compared to the Islamic index, the Conventional Stock Market Price (MYR) exhibits much lower volatility, with a mean of 1649.53 and a standard deviation of 137.10. Besides that, the gold price (MYR), which reflects its status as a safe-haven asset during times of economic instability, ranges from 3928.61 to 9494.30, with a mean of 6018.09 and a standard deviation of 1565.96. Throughout the observed period, these statistics offer a comprehensive insight of the behaviour and trends within key financial variables.


## 4.3	Initial Insights
<p align="center">
  <img height="500px" src="https://github.com/drshahizan/research-design/blob/main/proposal/UmmiWahid/images/Correlation%20Heatmap.JPG"/>
</p>
<p align="center">
Figure 4.4 Correlation Heatmap Analysis
</p>

The relationships between five financial metrics, which are price of gold (MYR), price of palm oil (MYR), price of crude oil (MYR), price of the Islamic stock market, and price of the conventional stock market—are visually represented by the correlation heatmap that is provided. Blue denotes negative correlations and red denotes positive correlations, and the colour gradient between them shows the intensity and direction of the relationships. The colour’s intensity represents the correlation coefficient's value; greater correlations are shown by darker hues.

The correlation value of 0.71 between Gold Price (MYR) and Palm Oil Price (MYR) indicates a significant positive relationship, which is clearly visible from the heatmap. This means that the price of gold tends to rise along with the price of palm oil. On the other hand, there is a substantial negative correlation (-0.87) between the price of gold and the price of conventional stocks, suggesting that gold prices tend to decline in tandem with increases in the price of conventional stocks. Further evidence of an unfavourable association between gold prices and stock market indices comes from the moderately negative correlation (-0.54) between the price of gold (MYR) and the price of Islamic stocks.

Furthermore, relationships between various financial variables are displayed in the heatmap. For example, the moderate positive correlation (0.38) between the price of palm oil (MYR) and the price of crude oil (MYR) indicates that both commodities frequently move in the same direction, albeit not very substantially. Given that they are stock market indices, it is not surprising that the prices of the Islamic and Conventional stock markets have a strong positive association. Therefore, Investors and policymakers can make more educated decisions about investments and policies by using this heatmap, which offers insightful information about the relationships between various financial parameters. 

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
