# Chapter 4: Initial Findings

## 4.1 Introduction 

This chapter contains the inital findings from the exploratory data analysis (EDA) and machine learning models development. Our research examines the prediction of traffic congestion for Malaysia, using a number of datasets. The datasets are as follow; traffic data, weather data, public transport ridership data, vehicle registration data. Through the data we aim to identify patterns and forecast future congestion.

## 4.2 Exploratory Data Analysis (EDA)


Visualizations and Descriptive Statistics 
During EDA, descriptive statics and visualizations were carried out. Below, the visualizations and descriptive statistics are provided.

### 4.2.1. Public Transport Ridership Over Time  

<p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/2.png?raw=true"  height="400" />
</p>

<p align="center">
 
Description: A line plot for daily ridership for bus and LRT Ampang Line. The data is cyclic and highlight peaks where ridership is high and throughs when ridership is low. 
Statistics: 
Bus Ridership - Mean: 180,000 - Std Dev: 30,000 
LRT Ampang Line - Mean: 150,000 - Std Dev: 25,000

### 4.2.2. Malaysia Road Accident Statistics (2010 - 2019)  

<p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/3.png?raw=true"  height="400" />
</p>

<p align="center">
 
Description: A line plot to capture time and increase in road accidents - Statistics:  
Average Annual Increase: 4%

### 4.2.3. Malaysia Road Fatalities (2010 - 2019)  

<p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/4.png?raw=true"  height="400" />
</p>

<p align="center">
 
Description: A line plot showing the trend of road crash deaths through out the years. The death rates decreased drasiclly recent years 
Statistics: o Peak Fatalities: 7152

### 4.2.4. Vehicle Registration Over Time 

<p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/5.jpeg?raw=true"  height="400" />
</p>

<p align="center">
  
Description: A line plot to capture the increase and decrease in vehicle registrations over time 
Statistics: o Peak Registrations: January and July

### 4.2.5. Temperature Variation Over Time

<p align="center">
<img src="https://github.com/drshahizan/research-design/blob/main/proposal/LURUIQI7/Chapter5/6.jpeg?raw=true"  height="400" />
</p>

<p align="center">

Description: A line plot showing max and min daily temperatures 
Statistics: - Max Temperature: 33°C - Min Temperature: 24°C

## 4.3 Initial Insights Gained from EDA

Traffic Patterns: Public transport ridership has certain daily peak periods, which are likely with commuting patterns. 
Accident Trends: Yearly accidents have been on the rise, with the number of fatalities occurring annually varying in number, although they had significantly dropped recently. 
Vehicle Registrations: The number of vehicle registrations has some periodic peaks, which could suggests that there might be yearly surges in vehicle ownership, perhaps due to seasonal environmental factors or conducive economic conditions for purchasing vehicles. 
Weather Impact: It is suspected that there are effects from the measurements of temperature that could have an effect on the road conditions and thus the congestion level too.

## 4.4 Feature Engineering

In view of what has been observed, new features are engineered and added to the original datasets to aid in prediction. 
Derived Features: The day of the week, month, indicators on whether a day is a public holiday, weather conditions (temperature, whether it is raining or snowing) and special events which occurred on that day. 
Time Series Features: Data from the previous day or time segment as features any temporal correlations can be captured in the features.

## 4.5 Expected Outcome

The main outcome of this research would be the development of a model for predicting traffic congestion in Malaysia. By providing a comprehensive set of features from different datasets and a significant amount of complimentary feature engineering, pitfalls which lead to traffic congestions, could possibly be detected. Consequently, authorities could be provided with actionable insights to manage such occurences.

## 4.6 Future Work

Improved models could be developed after this research phase and with availability of realtime data, this model could be further improved. Furthermore, we will also look into incorporating additional emerging technologies, such as the Internet of Things (IoT) and edge computing, to enhance the capabilities of data collection and data processing.
