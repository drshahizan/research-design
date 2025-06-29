<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="img/照片1.jpg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>[Zhao Zhihan]</td>
    <td>[MCS241041]</td>
  </tr>
</table>

# [RESEARCH ON SOIL ENVIRONMENTAL AND HEALTH RISK ANALYSIS BASED ON MACHINE LEARNING. ]

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/proposa.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="c1/Chapter1.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="C2/Chapter2.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="c3/Chapter3.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="c4/Chapter4.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="c5/Chapter5.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="Full Chapter/Complete Chapter.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="https://colab.research.google.com/drive/1GgHwHq_fYy65PbY157mxfEcQ1kGyNLtH"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

[Global industrial and agricultural activities have exacerbated soil pollution, with 
pollutants entering the food chain through crops, posing a significant threat to public 
health. Traditional assessment methods lack the ability to integrate multi-source data 
(such as soil pollutants, meteorological factors, and health records), which limits the 
accuracy of spatial risk mode. This study proposes a machine learning framework 
that integrates 3,000 samples from the Kaggle "Soil Pollution and Health Impact 
Case" dataset (2023-2024). Through data preprocessing (KNN interpolation, outlier 
handling), feature engineering (interaction terms, seasonal encoding), and training of 
random forest, XGBoost, and LightGBM models, it systematically analyzes the 
complex relationship between pollution and health. ]

## Keywords

[random forest,XGBoost,LightGBM.]

## Research Objectives

1. [To develop a data integration pipeline for harmonizing soil pollutant, weather, 
agricultural, industrial, health, and demographic data. ]
2. [To implement and compare multiple ML algorithms for predicting spatial health 
risks based on soil contamination.]
3. [To design a prototype early warning dashboard.]

## Scope of Work
 [The scope of the project encompasses a diverse range of data. Environmental 
data includes soil pollutant concentrations, soil types, and weather conditions. 
Industrial and agricultural data covers the types of industries and agriculture as well 
as industry distribution. Health data involves disease types, severity, symptoms, and 
health reports. Additionally, demographic data focuses on aspects such as the gender 
and age of the affected population. 
]

## Methodology

1. **Data Collection:**
   - [The data for this study is sourced from the publicly available Kaggle dataset 
titled "Soil Pollution and Health Impact Cases". This dataset integrates soil pollution 
monitoring data and health case records from multiple regions, spanning the time 
period from 2023 to 2024. It contains 3,000 samples and 24 variables, covering multi  
12 dimensional information such as soil pollutant concentrations, meteorological 
conditions, agricultural practices, and disease types.]

2. **Data Analysis:**
   - [The samples are divided into two parts: an 80% training set and a 20% test set, 
and the XGBoost is used to train the model. Then, the indexes of the 5 samples with 
the highest risks are selected. Combining with the feature importance of the model, 
the key influencing features and their corresponding contribution values of each high - 
risk sample are calculated and output. The results show that the risk probabilities of 
the 5 high - risk samples (indexes 103, 145, etc.) exceed 0.99. ]

3. **Validation:**
   - [The horizontal axis represents the False Positive Rate (FPR), and the vertical 
axis represents the True Positive Rate (TPR). The Area Under the Curve (AUC) 
reaches 0.95. An AUC value close to 1 indicates that the XGBoost model has a strong 
ability to distinguish between high - and low - soil - health - risk samples and can 
effectively identify risk patterns.]

## Expected Outcomes

- [The final comparison results are as follows: Both models take very little time, 
and the Random Forest is slightly faster than XGBoost. In terms of accuracy, the 
Random Forest reaches 0.90, while XGBoost reaches 1.00 (the reason for the 100% 
accuracy may be that the dataset is too small and the training task is too simple). In 
the analysis of soil environment and health risks, the XGBoost model has a higher 
accuracy and performs better, indicating that it fits the complex relationships of soil 
characteristics better.]

*For inquiries, contact: [zhaozhihan@graduate.utm.my ]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


