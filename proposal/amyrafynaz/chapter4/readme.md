# Chapter 4 - EDA/Initial Results

### Project Title: Time Series Forecasting for Energy Consumption in Malaysia Using Regression Technique

### Prepared by: NURAMIRA SHAFINAZ BINTI ZULAILEE, MCS231031

## Chapter 4: EDA/Initial Results


### Case 2: Secondary Data
#### Introduction
The Exploratory Data Analysis (EDA) phase is vital for understanding the dataset, identifying patterns, and gaining insight into the subsequent modelling phase. This chapter will outline the expected outcomes from the EDA process, including visualisation, descriptive statistics, initial findings, and future engineering.

#### Visualizations
Visualisation is one of the most potent tools for uncovering patterns and anomalies within the data. The following explanation of the visualisation is expected to be produced during the EDA process: 
1)	Time Series Plots <br>
  •	Purpose: Time series plots are fundamental to understanding the temporal dynamics of energy     consumption. They help visualise how energy consumption has changed over time, identifying      trends and seasonality.<br>
  •	Implementation: The historical energy consumption data such as the amount of electricity        consumed in Malaysia, total electricity consumption, energy demand by sector in Malaysia,       household electricity per capita in Malaysia, and urbanization in Malaysia based on year        and primary energy supply in Malaysia. Separate plots for different sectors will be created     to identify the consumption patterns. For instance, a time series for energy demands by         sector in Malaysia may reveal increases in usage during a specific time. Similarly, the         household per capita plots may show the correlations between energy used within the year.
2)	Correlation Heatmaps:
•	Purpose: Correlation heatmaps visualize the strength and direction of the relationships between multiple variables. They are instrumental in identifying which variables are vital and correlated with energy consumption.
•	Implementation: A heatmap will display the correlation between energy consumption in Malaysia and various economic, demographic, and climatic variables. For example, a strong positive correlation between GDP and energy consumption would indicate that economic growth drives higher energy usage, and population growth leads to higher energy consumption. The negative correlation with temperature might suggest that energy consumption will decrease during milder weather conditions. This insight will help to select relevant features for the regression model that will be implemented later.
3)	Scatter Plots:
•	Purpose: Scatter plots are effective in exploring the relationship between two variables and identifying potential linear and non-linear relationships.
•	Implementation: This will examine the relationship between energy consumption and key predictors such as GDP, population growth, temperature, and humidity. For example, plotting energy consumption in Malaysia against GDP can reveal whether there is a linear relationship (indicating GDP increases so with the energy consumption) or to see if there are non-linear patterns. This help to understand the relationship and determine whether polynomial or interaction terms are needed in the regression models.
4)	Box Plots:
•	Purpose: The box plot provides a visual summary of the dataset's distribution, which helps identify outliers and compare distributions across different groups.
•	Implementation:  The box plot will visualize the distribution of variables such as energy consumption, GDP, economic factors, and climate variables. It will help to identify the outliers and understand the spread and central tendency of the data. For example, the box plot energy consumption for various factors such as residential, industrial, and commercial can highlight variations and outliers within each sector to focus on specific analysis and feature engineering.
5)	Histograms:
•	Purpose: Histograms visualize the distribution of a single variable, showing the frequency of different values and helping to identify patterns such as skewness or kurtosis.
•	Implementation: Histograms will assess the distribution of individual variables, such as energy consumption, GDP, and temperature. For instance, a histogram of energy consumption might reveal a right-skewed distribution, indicating that a few periods have exceptionally high consumption. This insight may prompt transformations to normalize the data. Similarly, GDP, temperature and humidity histograms will help understand their distributions and any potential need for scaling or transformation.

#### Visualizations
#### Visualizations
#### Visualizations
#### Visualizations
#### Machine Learning (Initial Result)
(Description of initial machine learning results)
