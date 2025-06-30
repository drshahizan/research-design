<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="img/微信图片_20250630154622.jpg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>[Yi Xindie]</td>
    <td>[MCS241027]</td>
  </tr>
</table>

# [Insert Project Title Here]

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/proposal.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="c1/Chapter1.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="c2/Chapter2.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="c3/Chapter3.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="c4/Chapter4.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="c5/Chapter5.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="Full Chapter/Complete Chapter.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="https://colab.research.google.com/drive/1OW5wYhkTFzti2u4EsF4ofItfms9eh4bf"><img src="img/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

[Wildfires have become an increasingly severe threat to ecosystems, property, and 
human safety, especially in regions like California where climate conditions and human 
activities often contribute to fire outbreaks. This study explores how machine learning 
methods can be applied to predict wildfire risk by analyzing environmental, geographic, 
and human-related factors. Using a dataset covering California wildfire records from 
2014 to early 2025, this project tests and compares four models: Logistic Regression, 
Support Vector Machine (SVM), Random Forest, and XGBoost. 
Among these models, XGBoost showed the best overall performance, achieving an 
accuracy of about 79.3% and an AUC of 0.86. Important variables identified by the 
model include temperature, NDVI, wind speed, relative humidity, and road density, 
which together provide meaningful insight into the factors that influence wildfire 
occurrence. In addition to evaluating the model’s predictive ability, this study also 
discusses the main sources of prediction errors and highlights potential ways to refine 
the model in the future. 
The findings of this research suggest that combining structured environmental data with 
machine learning can support early wildfire risk detection and help inform more 
effective fire prevention and management strategies. It is hoped that this project can 
provide a small reference point for further academic research and practical applications 
related to wildfire prediction. ]

## Keywords

[wildfire prediction, machine learning, XGBoost, environmental data, 
California ]

## Research Objectives

1. [Improve wildfire risk forecasting by analyzing climate, terrain, and human factors  ]
2. [Optimize emergency response through better resource allocation  ]
3. [Support sustainable policies for long-term fire resilience  ]

## Scope of Work
1. [Geographic Focus: California or other wildfire-prone regions]
2. [Time Frame: Analysis of wildfire data from the past decade (2013–2023)]
3. [Technical Scope:
   - Machine learning for risk prediction (e.g., Random Forest, LSTM)
   - Geospatial analysis of fire-prone zones]

## Methodology

1. **Data Collection:**
   - [This study uses the “California Wildfire Damage (2014–Feb 2025)” dataset 
from Kaggle as the main source of data. Covering over ten years of wildfire activity in 
California, this dataset includes essential information such as the name and location of 
each fire, the date it occurred, the area burned, the number of structures affected, and 
other relevant attributes. These records form the basis for understanding how different 
environmental and human-related factors might be linked to wildfire events. ]

2. **Data Analysis:**
   - [Once XGBoost was chosen as the final model, I looked into which features had 
the most influence on its predictions. This is useful not just for understanding how the 
model works, but also for drawing practical insights into what really matters when it 
comes to wildfire risk. 
According to the model’s output, the top contributing variables were 
temperature, NDVI (a vegetation index), wind speed, relative humidity, and road 
density. Among these, temperature came out on top—likely because heat plays a direct 
role in fire ignition and spread. NDVI also made sense, as it reflects how dry or sparse 
the vegetation is. Low NDVI values could indicate areas where vegetation is dry or 
unhealthy, increasing the chance of fires catching on. Wind speed and humidity affect  
30 
 
how quickly a fire can grow, while road density might be a proxy for human activity, 
which can sometimes trigger wildfires. 
Even though machine learning models like XGBoost are often seen as black 
boxes, this kind of feature importance analysis helps shed some light on the logic behind 
their predictions. It gives a clearer picture of which environmental factors deserve more 
attention in fire prevention strategies. ]

3. **Validation:**
   - [We also looked at the ROC curve, which is a way of measuring how well the 
model separates fire from no-fire cases at different thresholds. The curve for XGBoost 
stayed above the baseline and had an AUC score of around 0.86. That basically tells us 
that the model does a pretty good job distinguishing between risky and safe areas. ]

## Expected Outcomes

- [Looking back on this project, I think it gave me a valuable chance to explore 
how machine learning can be applied to a real-world problem like wildfire risk. I tried 
several models—XGBoost, Random Forest, Logistic Regression, and SVM—and after 
some comparisons, XGBoost gave the most reliable results. Its predictions were fairly 
accurate, and it seemed good at picking out which areas might be more at risk. Of course, 
it’s not perfect, but it did give a sense that machine learning could be a useful tool in 
fire prevention if used properly. 
What surprised me a bit was how much the different features affected the 
outcome. Things like temperature, wind speed, and NDVI clearly had a big influence 
on how the model behaved. It made me realize that even small changes in 
environmental conditions can shift the results. I guess it helped me see wildfires as not 
just random events, but something that can be studied and maybe even predicted with 
the right tools.]


*For inquiries, contact: [yixindie@graduate.utm.my]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

