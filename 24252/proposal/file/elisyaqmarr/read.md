
<p align="center">
  <img height="300px" src="IMG_2816.jpeg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Siti Nur Elisya Aqmar binti Mohamad Kamal</td>
    <td>MCS241056</td>
  </tr>
</table>

# FLIGHT DELAYS PREDICTION MODEL USING MACHINE LEARNING

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/elisyaqmarr"><img src="pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="CHAPTER 1 - ELISYA.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="CHAPTER 2 - ELISYA.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="CHAPTER 3 - ELISYA.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="CHAPTER 4 - ELISYA.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="CHAPTER 5 - ELISYA.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="Thesis_Siti Nur Elisya Aqmar binti Mohamad Kamal.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="https://colab.research.google.com/drive/1pTbwUjSEs3O6TQxWFKCaz0cAh1bEodMI?usp=sharing"><img src="python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

In the aviation industry, flight delays have a significant impact on passenger satisfaction, operational management, and financial costs. In this study, a flight delay prediction model is developed using machine learning techniques to identify flights that are likely to be delayed based on operational and weather-related data. There are a number of features included in the dataset, such as departure and arrival times, airline, weather conditions, and airport traffic information, to name a few. There have been three types of machine learning models developed and compared, like Random Forest, XGBoost, and an Attention-based Bidirectional Long Short-Term Memory (ATT-BI-LSTM). A comparative analysis of the ATT-BI-LSTM model and the bi-LSTM model showed that the ATT-BI-LSTM model was the most accurate and able to accurately detect actual flight delays out of the bunch. As a result of this study, machine learning can be used in aviation to predict flight delays earlier, help to make proactive decisions, and reduce the impact of delays on operations and customer service. 



## Keywords

**Flight Delays, Prediction Model, Machine Learning**


## Research Objectives

a)	To collect and process flight and weather data for delay prediction

b)	To have a machine learning model for classifying delayed flights, such as Random Forest, XGBoost, and ATT-BI-LSTM, developed and compared.

c)	To identify the best model based on ROC-AUC, F1-score, and accuracy-precision metric.


## Scope of Work
This project aims to build a predictive model that can classify whether a flight will be delayed based on historical flight and weather data. The focus is on departure delays (over 15 minutes). Three machine learning models are applied and compared.

**Key focus:**
- Use structured flight and weather data.
- Apply supervised machine learning models.
- Predict binary outcomes: delayed or on-time.
- Evaluate models using accuracy, recall, and F1-score.

---

## Methodology

1. **Data Collection**
   - Dataset used: `M1_final.csv` (sourced from Kaggle)
   - Includes flight schedule, weather conditions, and delay labels.

2. **Data Preprocessing**
   - Fill missing values.
   - Drop irrelevant features.
   - Encode categorical variables.
   - Create binary target variable (`is_delayed`).

3. **Model Development**
   - Random Forest (RF)
   - XGBoost
   - Attention-Based Bidirectional LSTM (ATT-BI-LSTM)

4. **Model Evaluation**
   - Performance metrics: Accuracy, Precision, Recall, F1-Score.
   - Visual analysis: Confusion matrix, ROC curve, heatmaps.

---

## Expected Outcomes

The expected outcome of this project is the successful development of a robust and reliable flight delay prediction model using machine learning techniques. The model will be trained on historical flight and weather data to classify whether a flight is likely to be delayed or arrive on time. By implementing and comparing three different machine learning algorithms—Random Forest, XGBoost, and Attention-Based Bidirectional Long Short-Term Memory (ATT-BI-LSTM)—the project aims to evaluate each model's effectiveness in handling structured and temporal data. The models will be assessed using standard performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. Through this comparison, the study will identify the most suitable model for real-world deployment in flight operations. Another key outcome is the identification of influential features that contribute significantly to flight delays, such as weather conditions, departure time, and congestion levels. These insights can be used by airline operators to enhance scheduling, mitigate disruptions, and improve passenger satisfaction. In addition, the project is expected to provide a clear and reproducible workflow that demonstrates the full machine learning pipeline—from data collection and preprocessing to model training and evaluation—serving as a valuable resource for future research and industry applications in the field of intelligent transportation systems.
