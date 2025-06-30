<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="photo_2025-06-17_09-45-26.jpg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Sivarajan Esvaran</td>
    <td>MCS241051</td>
  </tr>
</table>

# Sales Forecasting Models for Direct Selling Business: A Data-Driven Approach to Predictive Analytics

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/"><img src="pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 |<a href="Chapter 1/Chapter 1_Sivarajan_MCS241051.pdf"><img src="pdf.svg" width="24px" height="24px"></a>|
|  3.  | Chapter 2 | <a href="Chapter 1/Chapter2_Sivarajan_MCS241051.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="Chapter 1/Chapter3_Sivarajan_MCS241051.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <<a href="Chapter 1/Chapter 4_Sivarajan_MCS241051.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="Chapter 1/Chapter 5_Sivarajan_MCS241051.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="All Chapter_Sivarajan_MCS241051_Sales Forecasting.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="code"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract


The purpose of this study is to develop and evaluate sales forecasting models for the direct selling business using transactional data from an Amway distributor in Malaysia. This study aims to assist independent distributors in improving inventory planning, target setting, and strategic decision-making by implementing data-driven forecasting approaches. The dataset comprised 553,542 sales transactions spanning from April 2023 to April 2025, covering detailed customer demographics, product sales, and transaction-level information. Data preprocessing included cleaning, outlier detection, and extensive feature engineering to create meaningful predictors such as temporal features, customer loyalty metrics, pricing indicators, and purchase recency measures. Four forecasting models were implemented and compared: Long Short-Term Memory (LSTM) neural networks, Random Forest, Linear Regression, and ARIMA. The results revealed that although LSTM, Random Forest, and Linear Regression models achieved high R² scores of 0.964, their high MAPE of 52.68% limited their practical utility for business forecasting. In contrast, ARIMA showed poor overall performance with a negative R² but paradoxically achieved 100% custom accuracy within the defined criteria. Overall, the findings highlight the need for careful model selection, robust evaluation frameworks, and further optimization to achieve reliable sales forecasting in direct selling businesses. This research provides valuable insights for distributors and contributes to advancing predictive analytics applications in the direct selling sector.


## Keywords

Sales Forecasting, Direct Selling,Data Cleaning, Exploratory Data Analysis, Feature Engineering, Machine Learning

## Research Objectives

1. To conduct comprehensive exploratory data analysis
2. To analyse temporal sales patterns
3. To develop and implement multiple forecasting models
4. To establish comprehensive model evaluation criteria
5. To identify optimal forecasting approaches

## Scope of Work
The scope of this project encompasses the use of transaction and customer data collected from a single
Amway distributor, covering the period from April 2023 to April 2025. It involves developing and comparing
multiple forecasting models, including ARIMA, Exponential Smoothing, Random Forest, Linear Regression,
and LSTM, to determine their suitability for sales prediction in direct selling environments. The project
focuses on generating forecasts across different prediction horizons, to support both operational decision-making 
and long-term strategic planning. The technology stack employed includes Python libraries such as scikit-learn, 
TensorFlow/Keras, Prophet, and statsmodels to ensure robust model development. Furthermore, cross-validation and 


## Methodology

1. **Data Collection:**
The dataset was collected from a single Amway distributor, covering a 24-month period from April 2023 to April 2025. Monthly sales reports in PDF format were downloaded from the distributor portal. Using Python libraries such as pdfplumber, tabula, and PyPDF2, the PDF files were systematically converted into structured CSV files. The final dataset consisted of 553,542 transaction records with 12 core features including order details, product information, transaction amounts, return status, and customer demographics, providing comprehensive insights into purchasing behaviour and sales trends.

2. **Data Analysis:**
Exploratory Data Analysis (EDA) was conducted to understand the dataset characteristics and identify temporal patterns, customer behaviours, and product performance. Key analysis steps included:

Time Series Analysis: Identification of trends, seasonality, and cyclical sales behaviours to inform model development.

Pattern Recognition: Customer segmentation using RFM analysis, product performance assessment, and geographic market analysis.

Feature Engineering: Expanded the dataset from 12 to 28 variables, adding features such as:

Temporal features (month, quarter, day of week, is weekend)

Behavioural indicators (customer order count, total spend, average order value)

Pricing indicators (price per quantity, average item price per order)

Recency metrics (days since last purchase)
These enhancements improved the models’ ability to capture business dynamics and generate accurate forecasts.

3. **Validation:**
Model validation involved robust evaluation techniques to ensure reliable forecasting performance and avoid overfitting. The following approaches were used:

Cross-Validation: Time series cross-validation techniques to assess model generalizability on unseen data.

Walk-Forward Validation: Sequential training and testing to mimic real-world forecasting scenarios.

Performance Metrics: Evaluation based on R² (coefficient of determination), RMSE (root mean square error), MAE (mean absolute error), and MAPE (mean absolute percentage error).
Results showed that while LSTM, Random Forest, and Linear Regression models achieved high R² scores (0.964), they had high MAPE values (52.68%) limiting practical utility. Conversely, ARIMA demonstrated 100% custom accuracy despite a negative R², highlighting the complexity of aligning statistical performance with business applicability.

## Expected Outcomes

This project is expected to deliver robust sales forecasting models tailored for the direct selling industry, specifically for independent distributors like those in Amway. The expected results include:

Development of Multiple Forecasting Models:
The project will produce and compare forecasting models including ARIMA, LSTM, Random Forest, and Linear Regression, identifying their strengths and limitations in predicting highly variable sales data.

Enhanced Data Understanding:
Through comprehensive exploratory data analysis, the project will uncover key business insights such as temporal sales patterns, customer purchasing behaviours, and product performance disparities, enabling data-driven decision-making.

Creation of an Optimised Feature Set:
The feature engineering process expands the dataset from 12 to 28 features, incorporating temporal, behavioural, pricing, and recency indicators, which enhances model predictive power.

Reliable Sales Forecasts for Business Planning:
By providing forecasts at different horizons (1-week, 4-week, and 12-week), the models will support operational decisions such as inventory management and promotions, as well as long-term strategic planning.

Democratisation of Predictive Analytics:
The project contributes a scalable and automated analytics framework, making advanced forecasting tools accessible to individual distributors who typically lack technical expertise or resources for such capabilities.


*For inquiries, contact: [sivarajan@graduate.utm.my]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)
