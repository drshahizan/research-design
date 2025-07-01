<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)
<p align="center">
  <img src="https://github.com/user-attachments/assets/fbc820ef-f65f-4892-beaf-fa4985e62d03" alt="MiraEdoraBintiYunos_ID" width="300"/>
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Mira Edora Binti Yunos</td>
    <td>MCS241057</td>
  </tr>
</table>

# FORECASTING AIRASIA’S PROFITABILITY BASED ON FUEL PRICE TRENDS USING ARIMA AND XGBOOST

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/"><img src="pdf1.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="Chapter 1/Chapter1_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a>|
|  3.  | Chapter 2 | <a href="Chapter 2/Chapter2_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a>|
|  4.  | Chapter 3 | <a href="Chapter 3/Chapter3_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a>|
|  5.  | Chapter 4 | <a href="Chapter 4/Chapter4_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a>|
|  6.  | Chapter 5 | <a href="Chapter 5/Chapter5_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a>|
|  7.  | Complete Chapter | <a href="Full chapter/Thesis_MiraEdoraYunos.pdf"><img src="pdf1.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="Code/ForecastingProfitibilityAirAsia.ipynb"><img src="python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

This thesis focuses on forecasting AirAsia’s profitability in response to fuel price trends using a hybrid approach that combines ARIMA for univariate time series analysis and XGBoost for Multivariate machine learning modeling. This approach is employed to enhance forecasting accuracy and deliver actionable insights for financial planning and informed strategic decision-making in the airline industry. The dataset used spans a minimum of 3–5 years, contains between 500,000 and 1,000,000 records, and includes at least 5–7 key variables, such as fuel prices, revenue, operating costs, and passenger demand, ensuring it is comprehensive yet manageable in terms of size and complexity. Data preprocessing steps such as handling missing values, outlier detection, normalization, and feature engineering, including lagged features, rolling averages, and Seasonal indicators, are applied to enrich the datasets and enhance model performance. The study also examines the relationship between fuel price volatility and profitability, emphasizing the importance of combining time series decomposition and exploratory data analysis (EDA) to identify meaningful patterns and trends. Ultimately, the research contributes to advancing the application of machine learning and time series analysis in aviation finance, offering a framework that supports cost management, risk mitigation, and strategic planning in an economically volatile environment.

## Keywords

Fuel Price Volatility, AirAsia Profitability Forecasting, ARIMA Time Series Model, XGBoost Machine Learning, Hybrid Predictive Modeling

## Research Objectives

1. To develop and apply an ARIMA model to forecast fuel price trends over time.
2. To utilize XGBoost to model the nonlinear relationships between fuel prices and AirAsia’s profitability.
3. To integrate both models into a hybrid framework to improve the accuracy of financial
forecasting.

## Scope of Work
-The project focuses on forecasting the profitability of AirAsia based on fuel price
trends in Malaysia.
-Historical data on fuel prices and AirAsia’s financial performance will be utilized,
primarily from open data platforms or official reports.
-The study applies ARIMA for time series analysis and XGBoost for structured data
modeling, combining them into a hybrid forecasting model.

## Methodology

1. **Data Collection:**
   - The data for this study was collected from AirAsia’s quarterly financial reports (2021–2024), which were obtained from the official Bursa Malaysia website. These reports provided key financial indicators, including revenue, net profit or loss, fuel costs, and operating expenses. Additionally, historical fuel price data were retrieved from publicly available Kaggle datasets. The combined dataset, formatted in CSV, served as the foundation for developing the forecasting models using ARIMA and XGBoost.

2. **Data Analysis:**
   - Data analysis was conducted using Python, with libraries such as Pandas, NumPy, Matplotlib, and Seaborn for exploratory data analysis (EDA) and visualization. Techniques like time series decomposition, correlation analysis, and feature engineering (e.g., lagged values, moving averages, seasonal indicators) were applied to understand trends and patterns in fuel prices and AirAsia’s financial performance. The processed data was then used to train and evaluate ARIMA for linear time series forecasting and XGBoost for capturing nonlinear relationships.

3. **Validation:**
   - Model validation was conducted using standard performance metrics, including Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), to assess forecasting accuracy. The dataset was split into training and testing sets to determine how well the models generalized to unseen data. Additionally, a confusion matrix and classification report were used to validate the XGBoost model’s ability to classify profit and loss cases, ensuring the reliability of predictions in the presence of fluctuating fuel prices.

## Expected Outcomes

This project aims to develop a robust hybrid forecasting model that accurately predicts AirAsia’s profitability based on fuel price trends by integrating ARIMA and XGBoost. The findings aim to provide valuable insights into how fuel volatility impacts airline financial performance, supporting more informed strategic planning and risk mitigation. The model can serve as a practical decision-support tool for financial analysts and airline stakeholders. Additionally, the results may contribute to academic research on hybrid forecasting techniques, with the potential for publication in journals related to aviation management or data science.

*For inquiries, contact: miraedora@graduate.utm.my*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

