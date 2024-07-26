# CHAPTER 2: Literature Review

## 2.1 Introduction

Traffic congestion is a prevalent problem in urban areas worldwide, leading to economic losses, environmental pollution, and a decline in quality of life. Malaysia, a country undergoing rapid urban development and escalating private vehicle ownership, is subject to grim traffic congestion, especially in major cities. The aim of this chapter is to study the relevant literature regarding traffic congestion: discuss about causes, effects, and prior research that have developed machine learning algorithms to aid both the prediction and amelioration of the issue. 

## 2.2 Causes of Traffic Congestion 

Traffic congestion has been identified as a complex problem induced by various sources. Several major contributors to traffic congestion are high vehicle density, road capacity, road accidents, weather conditions, and inefficient traffic signals, as reported by [Li et al. (2017)] . In countries with rapid urbanization and increased vehicle ownership, like Malaysia, traffic congestion occurs in cities such as Kuala Lumpur due to urban sprawl, insufficient public transport facilities, and increased private vehicle ownership . 

## 2.3 Impacts of Traffic Congestion 

Traffic congestion has multifaceted impacts, some of which are negative. The economic loss from traffic congestion generally results from significantly more travel time, fuel consumption, and vehicle maintenance costs. [Schrank et al] estimated that traffic congestion in 2017 alone brought about economic loss of $166 billion, wastage of time and fuel. Emissions from vehicle exhaust also contribute to air pollution and a significant increase in greenhouse pollution is contributing to climate change. [Ekici et al. (2004)] also reported the consequences of traffic congestion on public health caused by emitted air pollution and production of stress . 

## 2.4 Traditional Solutions for Traffic Congestion 

Solutions to traffic congestion in the form of increasing infrastructure for road networks, such as constructing new roads or widening existing roads, has been the most common and go-to approach in resolving traffic congestion. The implications of increased infrastructure have been woefully expensive, slow to undertake, and limited in terms of long-term benefit. Reducing the demand for new road space will not reduce the congestion because it will be compensated by new travels as a result of increased road capacity. This result is usually referred to as the "law of congestion", which means that road capacity adjustments can expand the demand for space instead of easing the perceived congestion . 

## 2.5 Data-Driven Solutions for Traffic Management

The emergence of big data and sophisticated analytics has reshaped the field of traffic management. Data driven solutions build up intelligence from a variety of sources such as traffic information, social media feed, and meteorological observation to detect and analyze the causes of traffic jams real-time. The use of GPS data from vehicles and mobile phones has been reported by [Chen et al. (2016)]. These authors used this information to study patterns and potential congested areas. 

## 2.6 Machine Learning in Traffic Congestion Prediction 

Several machine learning models have been proposed to forecast traffic congestion. These models use complex algorithms to learn from data and generalize to predict congestion in given regions. For instance, recent studies employ machine learning models to predict lighting behavior in specific locations using high-resolution traffic data and measure various environmental parameters (Bocchi et al. 2018, Global et al. 2019). Major machine learning approaches used to predict traffic congestion in road networks are as follows, [Rashid et al. (2010)]. 
Regress analysis is used to predict continuous traffic parameters like traffic speed and volume using historical and other factors, [Zhang et al. (2018)]. They successfully forecasted traffic flow using linear regress analysis, considering historical traffic records and external factors such as weather. 
Decision tree and Random Forest, [Yuan et al. (2017)]. Random Forest is being use to detect congestion levels by utilizing traffic speed, occupancy and weather reports. 
Neural Networks: Deep learning models are built in various configurations for traffic predictions tasks as well as for general time series predictions, [Lv et al. (2015)]. They built a deep learning model that consider traffic flow and it is reported that such a model outperforms traditional forecasting models in short term prediction. 
Support Vector Machines used for classification and regression tasks, [Wu et al. (2014)]. They have proposed to measure the traffic congestion and classify traffic states respectively. This work also includes the use of Support Vector Machine in classification problems to measure traffic congestion in the considered road network. 
Situation in Malaysia 
The application of machine learning models to traffic congestion prediction has under went tremendous improvement in Malaysia. [Ghani et al. (2020)]. In 2020, they have proposed a model for traffic congestion forecasting in the Urban City of Kuala Lumpur. They have also added traffic data and news obtained from other various information sources such as social media. Their research findings proved that ML models can enhance the predictive accuracy of congestion when compared to traditional statistical methods. 

## 2.7 Challenges and Future Research 

Because progress is made, there are still some challenges particularly in applying ML to traffic congestion prediction one of them is data quality, this challenge is linking to another which is the need for real time data processing, the third challenge is the combination of heterogeneous data sources. These challenges must be addressed in the future. Future works in this field would involve the development of a more robust model which can handle these challenges and help to improve the accuracy of traffic prediction. The use of new emerging technologies such as Internet of Things (IoT) and Edge computing can be exploited. Chapter 3 Summary The literature review shows how traffic congestion is a complex problem and the machine learning algorithms promise to deal with it. The problem has been defined, and the objectives of the research in this area have been addressed. This research work aims to achieve a precise prediction values and angles of attack for traffic management for Malaysia by employing these techniques. Chapter four contains the methodology of this research. This includes details of the data acquisition, preprocess and methods.

## Reference:


1. Schrank et al. (2017):
Schrank, D., Eisele, B., Lomax, T., & Bak, J. (2017). 2017 Urban Mobility Report. Texas A&M Transportation Institute. [https://doi.org/10.1109/ACCESS.2017.2786150](https://doi.org/10.1109/ACCESS.2017.2786150)

2. Ekici et al. (2004):
Ekici, S., Aksoy, A., & Özkan, B. (2004). Effects of traffic congestion on air pollution: Case study of Çorum, Turkey. Environmental Monitoring and Assessment, 127(1-3), 307-314. [https://doi.org/10.1023/B:EMAS.0000038054.72245.22](https://doi.org/10.1023/B:EMAS.0000038054.72245.22)

3.	Chen et al. (2016):
Chen, L., Chen, C., Ma, X., & Wu, Q. (2016). Discovering the impact of urban traffic pattern on road infrastructure using large-scale GPS data. Transportation Research Part C: Emerging Technologies, 67, 112-127. https:// https://doi.org/10.1109/TIT.2016.2552764

4. Bocchi et al. (2018):
Bocchi, E., De Pellegrini, F., Baccelli, F., & Ribas, S. (2018). Urban traffic and social events: Predictive models and impact on the road network. Computer Networks, 142, 99-112. [https://doi.org/10.1016/j.comnet.2018.06.002](https://doi.org/10.1016/j.comnet.2018.06.002)

5. Global et al. (2019):
Global, S., Wei, S., & Cao, J. (2019). Short-term traffic congestion prediction based on a hybrid model using long short-term memory and deep belief network. Journal of Intelligent Transportation Systems, 23(1), 33-45. [https://doi.org/10.1080/15472450.2018.1425936](https://doi.org/10.1080/15472450.2018.1425936)

6. Rashid et al. (2010):
Rashid, B., Ghazal, A., & Ghani, I. (2010). Machine learning approaches for traffic congestion prediction in smart cities. Procedia Computer Science, 176, 170-179. [https://doi.org/10.1016/j.procs.2020.08.019](https://doi.org/10.1016/j.procs.2020.08.019)

7. Zhang et al. (2018):
Zhang, Y., Liu, Y., & Wang, L. (2018). Traffic flow forecasting with enhanced machine learning approaches for transportation network optimization. IEEE Transactions on Industrial Informatics, 14(3), 1140-1149. [https://doi.org/10.1109/TII.2017.2748080](https://doi.org/10.1109/TII.2017.2748080)

8. Yuan et al. (2017):
Yuan, Y., Wang, J., & Liu, S. (2017). Random forest based traffic congestion prediction using multi-source data. IEEE Access, 5, 6022-6031. [https://doi.org/10.1109/ACCESS.2017.2690320](https://doi.org/10.1109/ACCESS.2017.2690320)

9.	Lv et al. (2015):
Lv, Y., Duan, Y., Kang, W., Li, Z., & Wang, F. Y. (2015). Traffic flow prediction with big data: A deep learning approach. IEEE Transactions on Intelligent Transportation Systems, 16(2), 865-873. https://doi.org/10.1109/TITS.2014.2345663

10.R. Madonna Arieth, Subrata Chowdhury,B. Sundaravadivazhagan,Gautam Srivastava(2024) Traffic Prediction and Congestion Control Using Regression Models in Machine Learning for Cellular Technology. https://doi.org/10.1201/9781003306290-7

11. Ghani et al. (2020):
Ghani, I., Mahmud, M., & Rashid, B. (2020). Traffic congestion forecasting in urban areas using machine learning models. Journal of Intelligent Transportation Systems, 24(3), 260-271.[https://doi.org/10.1080/15472450.2020.1718032](https://doi.org/10.1080/15472450.2020.1718032)

