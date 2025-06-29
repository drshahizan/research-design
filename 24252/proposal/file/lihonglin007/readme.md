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
    <td>[LI HONGLIN]</td>
    <td>[MCS241031]</td>
  </tr>
</table>

# [Sentiment Analysis of Public Opinion on Trump’s 2025 China Tariff Policy Based on "X"]

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="/proposal/Proposal_LIHONGLIN.pdf"><img src="img/pdf.svg" width="24px" height="24px"></a> |
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

[This study explores public sentiment on social media "X" (formerly Twitter) in response to the Trump administration’s 2025 China tariff policy. Using natural language processing (NLP) and the VADER sentiment analysis tool, the study analyzes English tweets from January to May 2025. A three-stage unsupervised analysis shows that negative sentiment dominates (60%), followed by positive (28%) and neutral (12%) emotions.

To improve classification performance, VADER compound scores are used to generate pseudo-labels for a balanced dataset. Supervised models including Support Vector Machine (SVM), Logistic Regression, and Gradient Boosting are trained and compared. The soft voting ensemble of the three models achieves the highest accuracy at 73.05%.

This research proposes a semi-supervised sentiment analysis framework suitable for policy-sensitive topics, demonstrating that pseudo-labeling can be effectively used without manual annotation. It also reveals a strong correlation between policy intensity and emotional polarization—more extreme policies trigger stronger emotional reactions and reduce space for rational discussion.

The study offers practical insights into public opinion dynamics during high-impact policy events and provides a methodological reference for researchers, policymakers, and analysts monitoring online discourse.

## Keywords

[Sentiment Analysis, China Tariff, VADER, Social Media, Pseudo-labeling, Semi-supervised Learning]

## Research Objectives

1. [ To analyze public sentiment trends regarding Trump’s 2025 China tariff policy based on posts from “X]
2. [ To identify emotional shifts across key policy stages (before, during, after).]
3. [ To construct a balanced dataset using VADER-generated pseudo-labels,to evaluate the performance of supervised and ensemble machine learning models on sentiment classification.]

## Scope of Work
**Included:**

Analyzing mass commentary on Trump's China tariff policy in 2025

Data scope: Collect English review data of "X" platform only based on keywords

Time range: January-May 2025

Analysis Method:  applied NLP and the VADER tool to generate pseudo-labels for sentiment classification,  
and evaluated four supervised learning models:  Logistic Regression, Support Vector Machine (SVM), Random Forest, and Gradient Boosting.


**Excluded:**

Social media other than "x" platform

Factors influencing public sentiment towards tariff policy

Pseudo-label Strategy Optimization

## Methodology

1. **Data Collection:**
   
Crawl data from social media "X"

3. **Data Analysis:**
   
Sentiment Scoring: VADER was used to conduct unsupervised sentiment analysis and generate pseudo-labels (positive, neutral, negative) for tweet classification

Data Preprocessing: Language filtering (English only), duplicate removal, text cleaning (remove URLs, @mentions, emojis, punctuation)

Feature Engineering: TF-IDF (1–3 grams, min_df=3, max_df=0.7, 8,000 terms)

Exploratory Data Analysis (EDA): Sentiment distribution, time-based trend analysis, word cloud visualization

Machine Learning Algorithms: Logistic Regression, Support Vector Machine (SVM), Random Forest, Gradient Boosting

Hyperparameter Tuning: GridSearchCV with 3-fold cross-validation

Ensemble Model: Soft voting ensemble combining Logistic Regression, SVM, and Gradient Boosting; achieved 73.05% accuracy

Performance Metrics: Accuracy, Precision, Recall, F1 Score


3. **Validation:**
   - [State how you validate your findings.]

## Expected Outcomes

This study combines VADER pseudo-labeling with supervised learning to build a semi-supervised sentiment classification model, achieving 73.05% accuracy while revealing policy-driven sentiment trends and contributing a practical framework for public opinion analysis.
- [Any intended publications or implementations.]

*For inquiries, contact: [your.email@utm.my]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

