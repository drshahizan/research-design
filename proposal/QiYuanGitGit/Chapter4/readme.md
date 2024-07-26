
# Chapter 4: Exploratory Data Analysis/Initial Results

## 4.1 Introduction
In chapter-4 of this research, the exploratory data analysis (EDA) as well as the initial findings of the study will be outlined. It is divided into three main parts: 4.2 Visualisations and descriptive statistics for data exploration, 4.3 Feature engineering, 4.4 Expected results.  Section 4.2 employs varying kinds of visualization techniques. The study will reveal the pattern, trend, direction and / or relationship, if any, between the News sentiment and stock price fluctuation in the Malaysian market. For section 4.2, by calculating the mean, median, standard deviation, as well as frequency counts the research will be able to give a detailed description of the overall sentiment distribution and characteristics in the data set. Section 4.3 applies data preprocessing to cleanse the raw data, feature conversion for categorical variables and addition of other stock market features from the raw data into a format that is more perceivable to the upcoming predictive modelling section. In section 4. 4, the preliminary hypotheses of exploratory data analysis of the factors that influence stock price changes to determine the direction and focus for improvements in quantitative modelling and assessment.

## 4.2 Visualisations and descriptive statistics for data exploration
Visualizations and descriptive statistics play a crucial role in exploring and understanding the data (Qin et al., 2020). The duo will be employed in this research for effective presentation and analysis of results.


## 4.2.1 Visualisation tools
For this study, the first step will, therefore, involve plotting histogram graphs to analyze the distribution patterns of the sentiment scores. These visualizations will give information on the measures of central tendency, variability, and Bias/Skewness of the sentiments estimates generated from the machine learning algorithms and lexicon methods. Frequency distributions of sentiments they mean histograms will be used to depict how sentiments are distributed in the articles. The distribution of the sentiment scores will be presented by box plots, which will point out the median, the first and the third quartile, and if the case, potential outliers of the data, so providing a clean picture of the data’s dispersion and its middle values. Such graphical aids, as Ortis et al. (2021) has rightly pointed corporate decision makers can understand whether the sentiment distribution is skewed or not and if it is skewed then in what extent it is skewed towards positive, negative or neutral sentiments.
Another prominent method that this research will employed is time series analysis. Visual representations of the collected data in the form of line plots can help in capturing modulations and patterning of the sentiment score which can then be mapped with the stock prices. Indeed, by taking the sample on the monthly or weekly basis, the study can see how average sentiment score changes, and what periods are the most sensitive to sentiment shift. Further, scatter and Heat maps will work for correlation or association analysis. Scatter plots can be useful in establishing the connection between sentiment scores and stock prices and might reveal trends or pattern which will help to establish the availability of a connection between media sentiment and behavior in the market. Maps of correlation matrices can effectively and briefly represent the direction of dependencies between multiple variables (sentiment scores and diverse indicators of the stock exchange) as well as the degree of their bonds. These visualizations along with the rolling mean and standard deviation plots for the sentiment will give trends and the level of volatility over time and gives a dynamic view of how sentiment is influenced by stock market.
 


## 4.2.2 Descriptive statistics
For example, descriptive statistics work hand in hand with visualization tools because it presents the data numerically (Narechania, et al. , 2020). The numeric properties of mean, median, standard deviation and variance will give qualitative explanation of the sentiment scores which will be utilised for this research. Further to that, frequency counts of the subcategories of sentiment, that is positive, negative or neutral will bring another dimension of analysis that will aid in determining the general basal sentiment of the news articles. These descriptive statistics shall be complemented by the use of visual aids, this shall ensure that the research avails a vast opportunity to analyze the sentiment data as well as patterns that determines the media sentiment in relation to the stock price. This choice of the visualization and this type of descriptive statistics not only enrich the comprehension of the dataset but also serve as a proper groundwork for the subsequent predictive modelling and research in the field of financial markets.


## 4.3 Feature engineering
Feature engineering is the process that enables formation of new variables (features) from raw data, which are supposed to enhance the learning models by applying prior knowledge about the application domain (Verdonck et al ., 2021). It means data selection and data preparation that act in the capacity of modifying and transforming data to create a better predictive model. In the case of Fan et al. (2019), the authors argue that good feature engineering boosts the credibility of a model as well as the quality of insights generated from the data because it directs the models’ attention to what matters most in the data. As part of feature engineering in this work, raw text data from news articles are transformed into features that can be utilised for the determination of the movements in the stock prices. In this research, feature engineering will be applied in the following:
![image](https://github.com/user-attachments/assets/a44f33ce-4d7c-4ff2-bf56-842fa2d3174e)
![image](https://github.com/user-attachments/assets/37a82d0d-ecdd-4694-be6b-fc3e32be391a)



## 4.4	Expected Results
![image](https://github.com/user-attachments/assets/a145c85b-1224-4fe6-a1f8-1b88d2917349)
![image](https://github.com/user-attachments/assets/c58324c4-f907-419d-96a4-3980148ece2c)
![image](https://github.com/user-attachments/assets/6874a0c1-e315-48c5-96f0-cb55cbe366da)
![image](https://github.com/user-attachments/assets/cd143414-24ba-415e-a31c-b4749b087455)
![image](https://github.com/user-attachments/assets/17e535d7-f6dc-4def-afff-462ced103553)
![image](https://github.com/user-attachments/assets/b0176a4b-be15-4015-b335-c16c31a8a801)



## 4.4.1 Machine Learning (Initial Result)

The process and steps to get initial result of machine learning by using Scikit-learn (sklearn) at Colab as shown at below: 

### Figure 4.2: Initial result of machine learning by Scikit-learn:
![image](https://github.com/user-attachments/assets/7d358401-fde2-4a11-8c8b-8e1987a6ea41)
![image](https://github.com/user-attachments/assets/8d38eb65-aeb8-4071-ad92-42b919f3b5ec)
![image](https://github.com/user-attachments/assets/8838195f-86da-43dd-afb2-7c2d6a810022)
![image](https://github.com/user-attachments/assets/2380972f-5f56-4d80-93f0-33a8bc4a80de)
![image](https://github.com/user-attachments/assets/73dd107a-1f01-4bb5-96cd-efa4447442dc)
![image](https://github.com/user-attachments/assets/c510c15d-7048-4d61-9890-a321e19655a9)
![image](https://github.com/user-attachments/assets/7d38c671-ecaf-4879-90a7-b28399e9dafc)


### Figure 4.3: Coding for Data Collection of News title:
![image](https://github.com/user-attachments/assets/091e1d54-e1fc-4717-a1d6-bc67091bc6d7)


### Figure 4.4: Coding to get sentiment score:
![image](https://github.com/user-attachments/assets/ea886fef-274b-4b68-92a0-2db7c075eeaf)
![image](https://github.com/user-attachments/assets/9ee669a7-1cf1-4620-a9b8-71ae9461dbd5)
![image](https://github.com/user-attachments/assets/523b182c-7e41-44dc-a741-68bf9925cdce)


## 4.5 Future Work
Potential avenues for future research include:
![image](https://github.com/user-attachments/assets/028712c1-678d-44db-be55-3af493ac6787)


## References
1. Albada, A., & Nizar, N. (2022). The Impact of the Investor Sentiment Index (SMI) on the Malaysian Stock Market during the COVID-l9 Pandamic. International Journal of Economics and Management, 16(2), 225–236. https://doi.org/10.47836/ijeam.16.2.06
2. Aslim, M. F., Firmansyah, G., Tjahjono, B., Akbar, H., & Widodo, A. M. (2023). Utilization of LSTM (Long Short Term Memory) Based Sentiment Analysis for Stock Price Prediction. Asian Journal of Social and Humanities, 1(12), 1241-1255.
3. Chau, N. T., Kien, L. V., & Phong, D. T. (2023). Stock price movement prediction using text mining and sentiment analysis. Studies in Computational Intelligence, 167–179. https://doi.org/10.1007/978-3-031-29447-1_15 
4. Cheng Kuan, M., Zayet, L., Akmar Ismail, T. M. A., & Mohamed Shuhidan, S. (2019). Prediction of Malaysian stock market movement using sentiment analysis. Journal of Physics: Conference Series, 1339(1), 012017. https://doi.org/10.1088/1742-6596/1339/1/012017 
5. Gangthade, R. A. (2024b). Stock price prediction using machine learning. International Journal for Research in Applied Science and Engineering Technology, 12(4), 3472–3477. https://doi.org/10.22214/ijraset.2024.60725 
6. Fan, C., Zhao, Y., Song, M., & Wang, J.Sun, Y. (2019). Deep learning-based feature engineering methods for improved building energy prediction. Applied energy, 240, 35-45.
7. Jiang, T., & Zeng, A. (2023). Financial sentiment analysis using FinBERT with application in predicting stock movement (arXiv:2306.02136). arXiv. http://arxiv.org/abs/2306.02136
8. Liu, J.-X., Leu, J.-S., & Holst, S. (2023). Stock price movement prediction based on Stocktwits investor sentiment using FinBERT and ensemble SVM. PeerJ Computer Science, 9, e1403. https://doi.org/10.7717/peerj-cs.1403
9. McCarthy, S., & Alaghband, G. (2023). Enhancing Financial Market Analysis and Prediction with Emotion Corpora and News Co-Occurrence Network. Journal of Risk and Financial Management, 16(4), 226. https://doi.org/10.3390/jrfm16040226
10. Mishra, J. (2023). TWITTER SENTIMENT ANALYSIS. INTERANTIONAL JOURNAL OF SCIENTIFIC RESEARCH IN ENGINEERING AND MANAGEMENT, 07(06). https://doi.org/10.55041/IJSREM24071
11. Momaya, H., Patel, V., & Momaya, V. (2023). Forecasting of Stock Trend and Price using Machine Intelligence LSTM and GRU Models. 2023 2nd International Conference on Vision Towards Emerging Trends in Communication and Networking Technologies (ViTECoN), 1–6. https://doi.org/10.1109/ViTECoN58111.2023.10157684 
12. Narechania, A., & Stasko, J., A., Srinivasan, (2020). NL4DV: A toolkit for generating analytic specifications for data visualization from natural language queries. IEEE Transactions on Visualization and Computer Graphics, 27(2), 369-379.
13. Non, N., & Ab Aziz, N. (2023). An exploratory study that uses textual analysis to examine the financial reporting sentiments during the COVID-19 pandemic. Journal of Financial Reporting and Accounting, 21(4), 895–915. https://doi.org/10.1108/JFRA-10-2022-0364 
14. Ortis, A., Torrisi, G. M., G., & Battiato, Farinella, S. (2021). Exploiting objective text description of images for visual sentiment analysis. Multimedia Tools and Applications, 80(15), 22323-22346.
15. Praturi, Ramakrishnan, A., S. S. G., & Deepthi, L. R. (2023, July). Stock Price Prediction Using Sentiment Analysis on Financial News. In International Conference on Data Science and Applications (pp. 551-567). Singapore: Springer Nature Singapore.
16. Qin, X., Tang, N., Luo, Y., & Li, G. (2020). Making data visualization more efficient and effective: a survey. The VLDB Journal, 29(1), 93-117.
17. Rajanikanth, J., Haritha, K., & Shankar, R. S. (2023). Forecasting stock close price using machine learning models. ARPN Journal of Engineering and Applied Sciences, 412–420. https://doi.org/10.59018/022361 
18. Rizinski, M., K., Jovanovik, H., Mishev, Peshov, M., & Trajanov, D. (2024). Sentiment Analysis in Finance: From Transformers Back to eXplainable Lexicons (XLex) (arXiv:2306.03997). arXiv. http://arxiv.org/abs/2306.03997
19. Shah, D., H., & Zulkernine, Isah, F. (2019). Stock market analysis: A review and taxonomy of prediction techniques. International Journal of Financial Studies, 7(2), 26.
20. Shuhidan, S. R., Kazemian, S. M., Hamidi, S., Shuhidan, S. M., & Ismail, M. A. (2018). Sentiment Analysis for Financial News Headlines using Machine Learning Algorithm. In A. M. Lokman, T. Yamanaka, P. Lévy, K. Chen, & S. Koyama (Eds.), Proceedings of the 7th International Conference on Kansei Engineering and Emotion Research 2018 (Vol. 739, pp. 64–72). Springer Singapore. https://doi.org/10.1007/978-981-10-8612-0_8
21. Sidek, Z., Ahmad, S. S. S., & Teo, N. H. I. (2023). Associating deep learning and the news headlines sentiment for Bursa stock price prediction. Indonesian Journal of Electrical Engineering and Computer Science, 31(2), 1041. https://doi.org/10.11591/ijeecs.v31.i2.pp1041-1049
22. Sinatrya, N. S., I., & Budi Santoso, Budi, A. (2022). Classification of Stock Price Movement With Sentiment Analysis and Commodity Price: Case Study of Metals and Mining Sector. 2022 International Conference on Advanced Computer Science and Information Systems (ICACSIS), 59–64. https://doi.org/10.1109/ICACSIS56558.2022.9923452
23. Srivastava, R., Bharti, P. K., & Verma, P. (2022). Comparative Analysis of Lexicon and Machine Learning Approach for Sentiment Analysis. International Journal of Advanced Computer Science and Applications, 13(3). https://doi.org/10.14569/IJACSA.2022.0130312
24. Verdonck, T., Óskarsdóttir, B., Baesens, M., & vanden Broucke, S. (2021). Special issue on feature engineering editorial. Machine learning, 1-12.
