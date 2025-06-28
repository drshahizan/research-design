<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="Profile_white.JPG" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>CHEN JUNHAO</td>
    <td>MCS241030</td>
  </tr>
</table>

# Amazon Best-seller Rank Prediction Using Machine Learning

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
|  8.  | Code | <a href="https://colab.research.google.com/drive/1cSYJa8LTeEMsMApQnc2L1xLjiB3x6ZN_?usp=sharing"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

This study explores the application of supervised machine learning models to predict Amazon Best Seller Rank (BSR) using structured product-level data. By collecting real-time information from Amazon’s software category, the research investigates how factors such as product price, star ratings, review volume, and geographic marketplace influence a product’s sales rank. Following comprehensive data cleaning and exploratory analysis, feature engineering was performed to enhance predictive power, introducing variables like review density, weighted rating, and log-transformed review counts.

Three regression models—Linear Regression, Decision Tree, and Random Forest—were developed and evaluated using standard performance metrics including R², RMSE, and MAE. Among them, the Random Forest Regressor achieved the highest predictive accuracy, explaining over 57% of the variance in BSR and demonstrating strong generalisation in cross-validation. Feature importance analysis further revealed that review behaviour and pricing are key predictors of best seller status.

The findings support the value of ensemble learning and engineered features in modelling complex, non-linear outcomes in e-commerce settings. This research contributes both theoretically, by validating advanced modelling approaches, and practically, by offering a replicable framework that sellers and analysts can use to forecast product performance and inform strategic decisions.

## Keywords

Amazon Best Seller Rank, machine learning, predictive research

## Research Objectives

1. To identify the key factors that influence BSR
2. To perform data cleaning and exploratory data analysis (EDA)
3. To apply and compare multiple supervised regression models
4. To evaluate model performance

## Scope of Work
Data collection, Data cleaning and preprocessing, Feature engineering, Exploratory Data Analysis (EDA) 
Implementation and comparison of three supervised regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Evaluation using performance metrics:
- R²
- RMSE
- MAE
Cross-validation to assess generalisability.

## Methodology

1. **Data Collection:**
   The dataset used in this research was sourced from Kaggle, specifically from a dataset titled Amazon Best Sellers Data, which contains real-time snapshots of software products listed on Amazon. The dataset includes key structured attributes such as product price, star rating, number of ratings, country of listing, and Best Seller Rank (BSR). This dataset was chosen due to its comprehensive coverage of multiple marketplaces and its relevance to ranking prediction tasks. Data was accessed and imported using Python’s pandas library for cleaning, transformation, and analysis.

2. **Data Analysis:**
The data analysis process consisted of several stages:
- **Data Cleaning:** This included handling missing values, removing non-numeric symbols from price fields, and converting data types appropriately.
- **Exploratory Data Analysis (EDA):** Visualisations such as histograms, box plots, count plots, and correlation heatmaps were created using seaborn and matplotlib to understand distributions and relationships between variables.
- **Feature Engineering:** New variables were constructed to improve model performance, including review_density, weighted_rating, and log_num_ratings. Categorical data such as country was one-hot encoded.
- **Modelling:** Three supervised regression models were trained—Linear Regression, Decision Tree, and Random Forest—using the scikit-learn library. Model performance was measured using R², RMSE, and MAE.

3. **Validation:**
   To validate the findings and ensure generalisability, cross-validation was used—specifically 3-fold cross-validation on the Random Forest model. This method split the dataset into multiple folds to train and test the model on different subsets, thereby reducing bias from a single train-test split. The consistency between training and cross-validated R² scores demonstrated that the model was not overfitting and could generalise well to unseen data. Feature importance analysis further validated the influence of engineered variables in improving prediction accuracy.

## Expected Outcomes

This project is expected to demonstrate that supervised machine learning models, particularly ensemble methods like Random Forest, can effectively predict Amazon Best Seller Rank (BSR) using structured product-level data. The key outcomes include the development of a predictive framework capable of identifying the most influential product features—such as price, rating, and review activity—and modelling their impact on sales rank with a reasonable degree of accuracy.

It is anticipated that the final model will not only achieve satisfactory performance metrics (e.g., R², RMSE, MAE) but also offer clear interpretability through feature importance analysis. These results will contribute to both academic research and practical decision-making in the field of e-commerce analytics. Specifically, the study will provide actionable insights for sellers aiming to optimise product listings and for analysts seeking to understand the factors behind marketplace visibility.

While this research is primarily academic, the modelling pipeline can be extended into future real-time applications, such as ranking dashboards or automated product tracking tools. The research may also serve as a foundation for a future journal article or conference paper, focusing on the application of interpretable machine learning in dynamic online marketplaces.

*For inquiries, contact: [chenjunhao@graduate.utm.my]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


