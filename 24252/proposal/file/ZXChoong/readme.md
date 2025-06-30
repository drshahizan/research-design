<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="image/CZX picture.jpeg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Choong Zi Xuan</td>
    <td>MCS241038</td>
  </tr>
</table>

# Detecting Signs of Mental Health Crises in Malaysian Social Media Text Using Emotion Classification and Explainable AI

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="Proposal/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="Chapter 1/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="Chapter 2/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="Chapter 3/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="Chapter 4/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="Chapter 5/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="All Chapter/"><img src="image/pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="code"><img src="image/python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

The increasing of mental health issues in Malaysia has highlighted the need for innovative approaches to identify early signs of emotional distress in online communication. This project explores the use of Natural Language Processing (NLP) techniques to detect potential mental health concerns from Malaysian social media posts collected from Reddit. A ttal of 13,726 posts with comments were gathered using Python Reddit API Wrapper (PRAW) based on keywords like ‘mental health’, ‘stress’, ‘depression’, and ‘anxiety’. After that some preprocessing step such as text normalization, stop word removal, and lemmatization was applied to the Reddit dataset. Emotion classification model based on DistilBERT ‘bhadresh-savani/distilbert-base-uncased-emotion’ was applied to classify each post with comment into one of six emotions like anger, fear, sadness, joy, love, and surprise. After that, emotions like sadness and fear were identified as high-risk indicators of mental health crises was flagged out which have 6,035 posts were classified with these emotions. To improve interpretability and trust in model decisions, the Local Interpretable Model-Agnostic Explanations (LIME) was used to explain why certain classifier were made. It highlighting the key words that contributed most to the emotion detection. To further assess model performance, a training and evaluation phase was introduced. The model was fine-tuned using the publicly available dataset ‘dair-ai/emotion’ and evaluated on the Reddit-based pseudo-labeled test set. Based on the outcome, it shows a steady decrease in training loss and validation loss increased over time, this was the signs of overfitting. The Evaluation metrics showed very low accuracy (7.5%) and F1-score (0.18), this shows the models trained on general English emotion dataset may not perform well when applied to Malaysian English expression. This is because Malaysian English often include mix language of Malay and English and have informal tone in the text. This project contributes to both research and practical application by developing an end-to-end pipeline for detecting emotional distress from social media content. It also demonstrates the value of Explainable AI (XAI) in validating model outputs when true labels are unavailable. 



## Keywords

Mental Health, Explainable AI, DistilBERT, Emotion classificaion, Social Media

## Research Objectives

1. To collect and preprocess mental health related social media data from Malaysian Reddit users for emotion-based analysis.
2. To apply a pretrained DistilBERT emotion classification model to detect high-risk emotional states in Malaysian social media text.
3. To interpret the model predictions using Explainable AI (XAI) techniques. 

## Scope of Work
- Data Sources: This study will do the web scrapping to get the real time dataset from Reddit
- Target Conditions: This study aim to get the outcome of emotion classification with flag out the post with emotion that have high-risk for mental health crises.
- Technical Focus: This study will use DistilBERT model to do the prediction of mental health crises and LIME to interpret the machine learning.  

## Methodology

1. **Data Collection:**
   - Scrape data from social media Reddit using PRAW

2. **Data Analysis:**
   - Data Preprocessing like text normalization, remove of URLs, special characters, and unnecessary symbols, stop wprds filtering and lemmatization.
   - Emotion classification using a DistilBERT model 'bhadresh-savani/distilbert-base-uncased-emotion' to classify the text into 6 emotion (sadness, anger, joy, love, fear, and suprise)

3. **Validation:**
   - XAI Interpretation : LIME was used to explain model decisions and validate whether predictions were based on emotionally relevant words.
   - Model Evaluation : Accuracy and F1-score were calculated based on pseudo-labels generated by the same model during testing.]

## Expected Outcomes

This project aims to produce several key outcomes related to mental health risk detection using social media data. First, it is expected to develop an end-to-end pipeline for collecting, cleaning, and classifying Malaysian English text from Reddit into emotional categories such as sadness , fear , anger , and love . This will allow for the identification of high-risk posts that may indicate signs of emotional distress or potential mental health concerns. Second, the application of the DistilBERT emotion classification model will provide insights into how well general English emotion models perform when applied to culturally nuanced and informal language found in Malaysian online discussions. Third, the use of Explainable AI (XAI) techniques like LIME will add transparency to the model’s decision-making process, helping to validate whether predictions are based on meaningful words or not. Although accuracy may be limited due to domain mismatch and lack of true labels, this project is expected to serve as a foundation for future work involving manual labeling , model fine-tuning , and local adaptation for better performance in detecting emotional cues in Malaysian digital communication.

*For inquiries, contact: choongzixuan@graduate.utm.my*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


