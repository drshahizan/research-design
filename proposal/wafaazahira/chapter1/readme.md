# PROJECT PROPOSAL
# Analyzing GDP and Unemployment Trends in Malaysia: A Time Series Approach

## Abstract


## Chapter 1: Introduction
### 1.1 Introduction
In Malaysia, it is important to understand the labour market conditions and economic performance since both of these impact policy decisions and economic planning. To assess the state and trends of a country’s economy, two key economic indicators like Gross Domestic Product (GDP) and unemployment rate are used. A nation’s GDP, which calculates the total value of goods and and services produced during a given period is a measure of the nation’s economic activity whereas unemployment rate provides a measure of both social and economic welfare as it shows the percentage of people who are seeking employment but are unable to find any.

Malaysia is among the economies that have experienced changes in its economic attributes over the last few decades because it has shifted from agriculture to manufacturing and services. However, unemployment is something that can still be observed as a problem that hinders economic stabilisation and social prosperity. With reference to this gap, there is a need to establish a conceptual framework that explains the relationship between economic growth, defined by GDP, and the unemployment experience. This research will help offer such an understanding given that it will involve using a rich set of datasets and sophisticated analytical tools.

Evaluating trends in GDP and unemployment must be the core of analysis. The decompositions of these indicators can be unique and valuable sources of information to policymakers, economists, and others in development planning. Analysing the correlation between the economic growth and the unemployment levels allows determining the potential strategies that can maximise the economic growth rates and, at the same time, minimise the unemployment numbers. In order to facilitate these kinds of efforts, this research uses descriptive statistics and a time series approach to extract the patterns, associations, and trends.

### 1.2 Problem Background
Malaysia has registered remarkable progress in the aspect of economic development, which features a process of industrialization, urbanisation, and globalisation. Nevertheless, the country has not been fully relieved from social issues with unemployment. This is important simply because one needs to understand the relationship between GDP and unemployment to assess the efficiency of economic policies in order to identify the directions that should be addressed. This leaves many people with those highest unemployment rates, which poses several problems in the society including poverty, crime, and decreased social cohesiveness.

Employment has long been perceived in association to economic growth with many people viewing economic growth as the single most important stimulant to employment. Thus, the correlation between GDP and unemployment is not so direct and depends on many factors such as changes in technology, legislation in the sphere of employment, the economic situation in the country and in the world. In Malaysia, the labour market has experienced significant changes in the employment status and employer’s type, transforming from agriculture-oriented employment to industrial and service employment. These changes have implications as to fluctuations in unemployment and the position of the economic environment concerned.

However, concerning GDP and unemployment, there is still a lack of more comprehensive and detailed research that would include other datasets and would use more complex and sophisticated analysis. This paper includes the following contributions: Previous research has offered useful findings; however, they rarely offer enough qualitative and quantitative detail to investigate the relationships between GDP and unemployment in Malaysia. This research intends to address this gap by integrating different data sources; therefore, coming up with better analytical tools for these economic indicators.

### 1.3 Problem Statement
Although the body of literature on Malaysia’s general economic profile is already extensive, there are relatively few studies that offer an analysis of GDP with different aspects of unemployment, total, youth, and duration-based. The following research questions guide this study:
More specifically, they include aspects on the dynamics of GDP and unemployment rates, and other patterns that may exist.
What were the actual trends in the states’ employment rates, the cycles and fluctuations that characterised the average rates, and the regular fluctuations that occurred due to factors such as the changing season?

Is it possible to predict future employment rates from the analysis of statistics for real GDP and other factors?
To answer these questions, a detailed going-concern analysis should be made employing descriptive statistics and time series analysis to capture the dynamics of Malaysia GDP Unemployment Rates. The purpose of this research is to find out the trends and correlations that will be of help in the formation of policies that will enhance growth of the economy and tackle the rates of unemployment.

### 1.4 Objectives
The primary objectives of this research are:
1. To analyse the GDP and unemployment rates of Malaysia in a descriptive manner to identify the trends of the two variables in the country. This involves reducing the data and making an attempt of finding out the essentials which relate or link various economic factors.
2. To analyse trends or seasonal unemployment rates, and other components which are irregular, they need to be separated from the time series data. These aid in studying the natural trends with a view of identifying the contribution made by seasonal fluctuations and others.
3. To deliver the predictive aims and objectives, time series analysis techniques are used such as ARIMA and Prophet models to predict future unemployment rates. This entails development of models from data gathered from past performance.

These objectives will help in developing an all round and holistic understanding of GDP and unemployment rate in Malaysia. With the attainment of these specific objectives, the study will provide important findings in the field of economic analysis that will assist policymakers to design measures that can promote economic development and decrease unemployment levels.

### 1.5 Gap Analysis
Prior research has explored the interaction between GDP and unemployment in Malaysia, although many of them have left out additional analysis on the effects of this correlation, only analysed limited sizes of the data and have not applied for sophisticated time series figures. This research fills the gap by:
- Incorporating datasets from different sources including the official government web site of data.gov.my and other reliable sources in order to give a detailed overview of the specifics of economic indicators. This is in regards to collections on monthly unemployment instances, youth unemployment, unemployment span and several GDP indicators.
- Using simple statistical measures to describe the data as well as more refined procedures in order to identify more detailed patterns of changes over time. The use of simple statistical tools will in turn involve descriptive statistics to give a general view of the data collected while use of time series technique will help in realising trends, seasonal patterns and forecasting.
- This means that in specific analysis, certain dimensions of unemployment such as youth- and duration-based rates of unemployment, which are not considered when undertaking general studies, are examined. This enables the provision of further insight into the cause of the unemployment issues.
  
This research uses a vast amount of material to design a rich picture of the connection between GDP and the unemployment rate in the country in question. For this purpose, it is proposed to use several sources of data and apply methods of analysis that were not utilised in previous studies investigating the chosen subject matters.

### 1.6 Scope
The scope of this research includes:

- Datasets: Monthly unemployment data (lfs_month.csv), seasonally adjusted monthly unemployment data (lfs_month_sa.csv), monthly youth unemployment data (lfs_month_youth.csv), monthly unemployment duration data (lfs_month_duration.csv), monthly unemployment status data (lfs_month_status.csv), annual real GDP data (gdp_gni_annual_real.csv), annual nominal GDP data (gdp_gni_annual_nominal.csv), GDP lookup data (gdp_lookup.csv), GDP nominal supply data (gdp_annual_nominal_supply.csv), and Malaysia economic indicator data (malaysia_economic_indicator.csv).
- Methods: Descriptive statistics are used to summarise and visualise the data, and time series analysis techniques like ARIMA and Prophet models, to decompose and forecast unemployment rates.
- Time Period: The analysis will cover the available time period in the datasets, focusing on monthly data for a detailed temporal analysis. This includes data spanning multiple years, which allows for the identification of long-term trends and patterns.
- Geographical Focus: The study will be limited to Malaysia, providing insights specific to its economic and labor market conditions. This geographic focus ensures that the findings are relevant and applicable to the context of Malaysia.

The first step of the analysis will be to load the datasets, converting the date columns to datetime and resampling annual GDP data to monthly if needed. This will be succeeded by data merging where the datasets will be merged on date index to form a complete data set to be used in the analysis.

Exploratory Data Analysis (EDA) will be employed to gain insights into the key features in the merged dataset by generating descriptive statistics and data visualization techniques. This will include measures of central tendency and variability and graphs such as histograms, box plots and time series graphs.

For the purpose of analysis the time series will be decomposed to trends, seasonality and residuals. It will assist in identifying other factors such as seasonality and filter out the impacts to gain a better understanding of the tendencies.

ARIMA and Prophet models will be used in time series analysis to predict future employment rates. The autocorrelations in the data will be captured with the help of ARIMA models, while the more flexible and capable models to be used will be the Prophet models.

The results obtained from the descriptive analysis and time series forecasting will help in formulating the policy implications and the recommendations as well. Such information can be useful in recommending policies on job creation for the growth of the economy of Malaysia.

Through the use of an extensive and reliable source of data and appropriate methods of analysis, this study will provide significant insights into the literature of economic analysis and help policy-makers in improving the economic growth and unemployment rate in Malaysia. The combination of various data sets and the use of complex time series models enable the authors to capture the dynamics and specifics of the interaction between GDP and unemployment, which is beneficial for economic forecasting and policy making.


### Conclusion
In conclusion, this chapter has outlined the introduction, problem background, problem statement, objectives, gap analysis, and scope of the research. Descriptive statistics accompanied by time-series data analysis of the GDP and unemployment rates of Malaysia is an important exercise for the identification of the changes in the Malaysian economy and to facilitate policy decision-making. Using multiple sets of data and creating a complex and intricate analysis, this research will work to contribute specific knowledge to the study of the link between the GDP and the unemployment rate in Malaysia, to the study of economics in general.
