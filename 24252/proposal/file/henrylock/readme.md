<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="img/person_icon.jpg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Lock Chun Hern</td>
    <td>MCS241047</td>
  </tr>
</table>

# [Prediction of Health Expenditure in Malaysia Using Machine Learning]

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="c1/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="c2/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="c3/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="c4/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="c5/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="all/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="code"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

Rising healthcare expenditure is a global challenge. The escalation of healthcare cost, caused by the inflation in medication prices, medical expenses, and the ageing population in Malaysia, necessitates the development of a robust predictive model for health expenditure to aid in the planning of future healthcare budgets. From previous researches, it is suggested that machine learning algorithms have great potential when used in modern health economies. The aim of this research project is to predict health expenditure in Malaysia using machine learning techniques to provide insight for health financing and policy planning. Random Forest and ARIMA are selected and applied to predict health expenditure in Malaysia from 2026 to 2035. The healthcare spending data is sourced from Ministry of Health Malaysia, WHO Global Health Expenditure Database and World Development Indicators Database for the period of 2000 to 2022. Explanatory data analysis shows a gradual increase in health expenditures from 2000 to 2019, and some fluctuations between 2019 to 2022 due to the COVID-19 pandemic. Key determinants affecting health expenditure have been identified by investigating their correlations with the health expenditures. GDP, population in thousands, total population aged 65 years old, number of physicians per 1000 people, life expectancy at birth and population growth, are chosen as the predictive indicators for health expenditures. From the initial findings, it can be concluded that ARIMA outperform Random Forest in forecasting Malaysia’s Total Health Expenditure (TEH) from 2019 to 2022, achieving a low MAE of RM 2,191 million, a low RMSE of RM 2,731 million and a high R2 of 0.818, indicating strong predictive accuracy. Random Forest performance is poor in the initial result due to insufficient training data and lack of hyperparameter tuning. In future studies, hyperparameter tuning and validation should be prioritised to improve the accuracy and reliability of the models. The methodology of this study can be extended to include other ASEAN countries with similar health economic structures to improve the generalisability of the machine learning models and provide insights for healthcare budget planning based on varying health policies across counties.

## Keywords

Health Expenditure, Malaysia, Machine Learning, Random Forest, ARIMA

## Research Objectives

1. To identify the key determinants of health expenditure to use as features for machine learning algorithms
2. To apply Random Forest and ARIMA for predicting health expenditure in Malaysia from 2026 to 2035 
3. To evaluate and compare the performance metrics of the machine learning models and to identify the model with the highest accuracy in forecasting health expenditure in Malaysia

## Scope of Work
1. The data will be sourced from the Ministry of Health Malaysia, Department of Statistics Malaysia, World Bank Group, and World Health Organization
2. The data collected will only involve demographic data and data related to health economics. No individual data that reveals an individual’s medical and medication history will be used
3. 	The study will use data from 2000 to 2022, providing relevant and up-to-date data for health expenses forecasting
4. 	This research will apply two machine learning methods: Random Forest and ARIMA


## Methodology

1. **Data Collection:**
   - Data were collected from Ministry of Health Malaysia website, WHO Global Health Expenditure Database and World Development Indicators Database.

2. **Data Analysis:**
   - ARIMA and Random Forest were applied to the pre-processed dataset to predict the future health expenditure in Malaysia.  For ARIMA, input data will consist of past data of total health expenditure, GHE and OOP as a time series analysis to predict to future value of health expenditure. For Random Forest, as the machine learning model can handle more variables than the ARIMA model, multiple features were selected for data modelling.  

3. **Validation:**
   - The models will be evaluated for their performance. This step is crucial as it not only validates the performance of the model, but also enables comparison of performance between different models. There are 3 key evaluation metrics applicable to regression models that will be used in this project: Mean Absolute Error (MAE),	Root Mean Squared Error (RMSE), Coefficient of Determination (R² score)

## Expected Outcomes

This project can provide insights for policymakers in the country in planning health expenditures and allow strategic allocation of budgets for health expenses. This helps to ensure the long-term sustainability of funding for Malaysia’s healthcare system. Overall, this research is projected to contribute to better health outcomes for the patients and people in Malaysia. The findings of this project are also expected to provide insights for other countries with similar healthcare systems or income levels.


*For inquiries, contact: lock@graduate.utm.my*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

