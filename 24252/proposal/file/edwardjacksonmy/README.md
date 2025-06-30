<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="img/person_icon.png" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>SOH JOEN SHIUAN</td>
    <td>MCS241028</td>
  </tr>
</table>

# CUSTOMER CHURN PREDICTION IN E-COMMERCE INDUSTRY USING RANDOM FOREST ALGORITHM

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="c1/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="c2/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="c3/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="c4/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="c5/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="Full Chapter/"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="code"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

Customer churn in e-commerce affects business sustainability, with retention costs being lower than acquisition costs. Existing studies lack comprehensive approaches in handling imbalanced datasets and feature engineering methodologies for e-commerce customer churn prediction. This research gap highlights the need for improved techniques that effectively address class imbalance while maximizing predictive performance. The purpose of this study is to investigate key features that affect customer churn and develop a machine learning model implemented in Python. Four algorithms are systematically compared, including Logistic Regression, Random Forest, Random Forest with SMOTE, and XGBoost, utilizing correlation analysis and comprehensive hyperparameter optimization to identify the best performing model for this use case. The dataset comprises 5,630 customer records with a class imbalance ratio of 4.94:1, where 83.2% of customers are non-churned and 16.8% are churned. Without hyperparameter tuning, XGBoost performs best with F1-Score of 0.8456 and ROC-AUC of 0.9662. After hyperparameter optimization, Random Forest achieves superior performance with F1-Score of 0.8556 and ROC-AUC of 0.9801, demonstrating significant improvement through systematic parameter tuning. These findings provide an actionable framework for e-commerce customer churn prevention systems, enabling businesses to implement proactive retention strategies and improve customer lifetime value through data-driven decision making.

## Keywords

Customer Churn, E-Commerce, Imbalanced Dataset, Feature Engineering, Machine Learning, Classification, Random Forest, Hyperparameter Tuning

## Research Objectives

1. To preprocess the customer churn data, leading to cleaned data for model training
2. To identify the key relevant attributes that affects the custome churn rate using Correlation Coefficient Matrix
3. To develop a machine learning model using Random Forest Algorithm that predicts the potential churning customers, visualizing the results in dashboard.

## Scope of Work
- The customer churn dataset will be collected from Kaggle Open Data Source.
- Tenure, CashbackAmount, OrderCount, SatisfactionScore, NumberOfDeviceRegistered, DaySinceLastOrder, Complain, OrderAmountHikeFromlastYear, CouponUsed, and customer behavioral attributes (PreferredLoginDevice, Gender, MaritalStatus, PreferedOrderCat, PreferredPaymentMode) will be used to calculate the impact towards customer churn pattern.
- The study would be focusing on e-commerce industry.
- Python programming language would be used to preprocess the data.
- Multiple machine learning algorithms will be evaluated, with Random Forest as the primary focus, alongside comparative analysis with Logistic Regression, Random Forest + SMOTE, and XGBoost.
- --------------------------------------------------------
- Project Limitations
- The analysis is limited to provided Kaggle Dataset (5630) and may not generalize to all e-commerce platforms.
- Temporal analysis is restricted due to the dataset itself is static and does not involve any real-time streaming process.
- Model deployment and production monitoring are excluded from this research scope.
- Cross-industry validation is not covered 

## Methodology

1. **Data Collection:**
   - The dataset titled "E-commerce Customer Churn Analysis and Prediction" is collected from Kaggle.

2. **Data Analysis:**
   - Data Preprocessing Techniques: Handling Missing Values, Duplicate Removal, Outlier Detection
   - Feature Engineering Techniques: Categorical Encoding and Derived Feature Creation
   - Exploratory Data Analysis (EDA): Univariate Analysis and Bivariate Analysis
   - Experimental Machine Learning Algorithms: Logistic Regression, Random Forest, Random Forest + SMOTE, XGBoost
   - Model Optimization: Hyperparameter Tuning
   - Performance Metrics: Accuracy Score, Precision Score, Recall Score, F1-Score, ROC-AUC Score
  
3. **Validation:**
   - Split the dataset into 80% training set and 20% testing set
   - Apply K-Fold cross validation reduce overfitting, making the model more stable
   - Compare multiple algorithms to find the best model for the use case

## Expected Outcomes
- Complete data preprocessing pipeline for e-commerce churn dataset
- The trained model achieve the baseline of the following metrics. (Accuracy >=85%, Precision>=80%, Recall>=85%, F1-Score>=77%)
- Models undergo hyperparameter tuning improves the result generation.
- Identify the key metric that affects the customer churn rate.
- Improve ROI as in reducing the customer requisition cost, leading to lower operational cost in e-commerce industry.

*For inquiries, contact: sohjoenshiuan@graduate.utm.my*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


