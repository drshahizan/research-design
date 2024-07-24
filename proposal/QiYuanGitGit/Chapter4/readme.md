
# Chapter 4: Exploratory Data Analysis/Initial Results

## 4.1 Introduction
In chapter-4, the exploratory data analysis (EDA) and initial results will be the main focus of the study. It is divided into three main parts: 4.2 Visualisations and descriptive statistics for data exploration, 4.3 Feature engineering, 4.4 Expected results. Section 4.2.1 using different visualization methods, the study will uncover the patterns, trends, and potential correlations between news sentiment and stock price changes in the Malaysian market. For section 4.2.2, by analyzing metrics like mean, median, standard deviation, and frequency counts, the research will provide a comprehensive understanding of the sentiment distribution and characteristics within the dataset. Section 4.3 using techniques like text preprocessing, categorical feature encoding, and the incorporation of relevant stock market features to transform the raw data into a format that suitable for the subsequent predictive modeling. In section 4.4, preliminary insights generated from the exploratory data analysis that affects stock price changes, guiding the direction and focus for more advanced modeling and evaluation.


## 4.2 Visualisations and descriptive statistics for data exploration
Visualizations and descriptive statistics play a crucial role in exploring and understanding the data (Qin et al., 2020). The duo will be employed in this research for effective presentation and analysis of results.


## 4.2.1 Visualisation tools
For this study, the first step will examine the distribution of sentiment scores using histograms. These visualizations will provide insights into the central tendency, spread, and skewness of the sentiment scores derived from both machine-learning models and lexicon-based approaches. Histograms will be used to visualize the frequency of different sentiment scores, which will allow how sentiments are distributed across the articles to be seen. Box plots will be used in this exploration to highlight the median, quartiles, and potential outliers, thus offering a clear view of the variability and central tendencies of the sentiment scores. Such visual tools, according to Ortis, et al. (2021) are essential in understanding whether the sentiment distribution is balanced or biased towards positive, negative, or neutral sentiments.
Time series analysis is another powerful approach this research will explored. Line plots of sentiment scores over time can reveal trends, patterns, and anomalies in the data, which can then be correlated with stock price movements. By resampling the data on a monthly or weekly basis, the study can observe how average sentiment scores evolve and identify periods of significant sentiment shifts. Additionally, scatter plots and heatmaps will be used for correlation analysis. Scatter plots can visually demonstrate the relationship between sentiment scores and stock prices, potentially uncovering trends or patterns that indicate a correlation between media sentiment and market behaviour. Heatmaps of correlation matrices can concisely present the direction of relationships between multiple variables (sentiment scores and various stock market indicators) and their strength. These visualizations, combined with rolling mean and standard deviation plots, will help in identifying trends and volatility in sentiment over time, providing a dynamic view of how sentiment interacts with stock market movements. 


## 4.2.2 Descriptive statistics
Descriptive statistics complement visualization tools by providing a numerical summary of the data (Narechania, et al., 2020). Metrics such as mean, median, standard deviation, and variance offer a quantitative understanding of the central tendency and dispersion of sentiment scores which will be used in this research. Frequency counts of sentiment categories (positive, negative, neutral) add another layer of analysis that will help to quantify the overall sentiment landscape of the news articles. By combining these descriptive statistics with visual tools, the research will comprehensively explore the sentiment data, uncovering patterns and insights that inform the relationship between media sentiment and stock price movements. This integrated approach of visualization and descriptive statistics will not only enhance the understanding of the dataset but also provides a solid foundation for further predictive modelling and analysis in the context of financial markets.


## 4.3 Feature engineering
Feature engineering is the process that extracts and creates new variables (features) from raw data that can help improve the performance of machine learning models by using domain knowledge (Verdonck et al., 2021). It involves selecting, modifying, and transforming data to enhance the predictive power of models. Effective feature engineering, according to Fan et al. (2019), can lead to better model accuracy and insights, as it allows the model to focus on the most relevant aspects of the data. In the context of this research, feature engineering is crucial to transform raw text data from news articles into meaningful features that can be used to predict stock price movements. In this research, feature engineering will be applied in the following:
o	Text Preprocessing: This involves tokenization which has to do with breaking down the article content into separate words or tokens; stop words removal (remove the common words that do not have important meaning), and stemming and lemmatization (reducing words to their root forms to ensure consistency e.g. "running" to "run").
o	Sentiment Scores:  This involves overall sentiment score (using NLP models to assign a sentiment score to each article, indicating whether the sentiment is positive, neutral, or negative, and lexicon-based sentiment score (calculating sentiment based on predefined lexicons to provide an alternative measure of sentiment).
o	Textual Features: This involves the term frequency-inverse document frequency (TF-IDF), i. e. Measuring the importance of words in an article relative to a corpus of articles, helping to highlight unique and significant terms, and N-grams (extracting contiguous sequences of n words e.g., bigrams, trigrams, to capture context and common phrases).
o	Temporal Features: This has to do with publication date and time (incorporating the date and time when the article was published to analyse temporal patterns and their impact on stock prices) and lag features (i.e. creating lagged versions of sentiment scores to capture delayed effects of news sentiment on stock prices, e.g., sentiment score from the previous day or week).
o	Categorical Features: Such features include source and author (encoding the source and author of the article to account for potential biases or credibility variations).
o	Stock Market Features: This includes previous day’s stock price (including the stock price from the previous trading day to account for existing market trends) and trading volume (incorporating trading volume to understand market activity and sentiment impact).

![image](https://github.com/user-attachments/assets/8d1564b3-ec34-4999-a5b4-29febbd975f7)

## 4.4	Expected results
![image](https://github.com/user-attachments/assets/dc545ddc-eeae-4e75-90da-d9e50b00425b)
![image](https://github.com/user-attachments/assets/74d20ff3-490a-49ae-9411-81f0bc3b877a)
![image](https://github.com/user-attachments/assets/967fba39-c9d0-41c6-9e0a-ee906f0562d3)


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
