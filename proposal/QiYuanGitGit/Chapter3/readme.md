
# Chapter 3: Research Methodology

## 3.1 	Introduction
In chapter-3, it explores the research methodology employed and is divided into three main parts: Research design, problem formulation and datasets, all components considered highly important to a study’s outcome. Research design describes the overall concept and its elements employed to realize the research goals and objectives. The detailed information about the employed methods and techniques, as well as, the justification of the choice of certain sentiment analysis algorithms and machine learning models is provided. This section also looks at the procedures followed in gathering data as well as in tabulating and analyzing information so that the research is conducted systematically and scientifically. Formulating the problem can be described as the process of identifying and defining the research problem. t contains the methodology description of research questions and hypothesis, objectives in order to provide the basis for further detailed examination of the connection between news sentiment and stock price fluctuations. Databases give a comprehensive description of the data sources that were used in the research work. This entails providing a comprehensive account of the main data source as are the credible online news portals in Malaysia that include New Straits times, Bursa Malaysia and the Edge Market among others. It also provides information about the data collection process and focuses on the criteria for selection of the articles, and on the techniques used for the classification of sentiments on the granular level. The datasets section increases the degree of transparency while using the given data and highlights the reliable sources used for analysis.

## 3.2 	Research Design
The study will use both quantitative and qualitative methods in the analysis of the given research questions, which are essential in examining the influence of sentiment expressed and found in financials news headlines on stock prices in the Malaysian market. Research framework for this proposal as shown in Figure 3.1.
In phase one there is problem formulation and the identification of the background to the study through literature review. In Phase 2, the researchers will gather all relevant data such as news articles retrieved from appropriate online sources concerning the Malaysian market, headlines of the articles, and the historical stock price data. Phase 3 will be involved in the main analysis processes where the extracted news headlines will be subjected to sentiment analysis both using lexicon-based and machine learning based sentiment analysis to obtain sentiment scores. This sentiment data will then be combined with the stock price data of the specific firm in question. In Phase 4, the features from the integrated dataset will be utilized to build models that are regression based and deep learning based such as LSTM and GRU to forecast the movement of the stock prices. Finally, in Phase 5 the results coming from the two phases of the sentiment analysis and stock price modelling phases will be analysed and discussed emphasising on the comparison of the most effective approaches to the sentiment analysis, revised list of relevant sentiment related features, and concluding remarks as to the practical implications of the results for multiple stakeholders. The results of the conducted research will be described and exemplified utilizing multiple forms of visualization and reporting tools for better information sharing with regard to the outcomes of the study.

![image](https://github.com/user-attachments/assets/95cbc484-281d-4ea8-80a6-b0b92edf2941)

## 3.3 	Problem Formulation
Specific problems that the study aims to address are highlighted in Table 3.3.
![image](https://github.com/user-attachments/assets/6707715c-e9e7-4136-9b00-a1c7e3411d57)


## 3.4 	Datasets
In sum, it is evident that the methodology of any stock price prediction model is highly dependent on the data used for testing and training the model. In the process of implementing this concept, the data accumulation phase entails the acquisition of information pertinent to the current project’s analysis and modeling components. The description of practical datasets is shown in the following Table 3.5.
![image](https://github.com/user-attachments/assets/34a75377-e8c7-4be8-b828-711e5878ab8b)

## 3.4.1 News Article Data

The primary data for this research shall be the headlines that relate to financial news in Malaysia, which may be obtained from the following Malaysians reputable online newspapers; Malaysiakini, New Straits Times, Bursa Malaysia, and The Edge Market. The following news sources were identified and chosen from the list of those most prominent and credible in the Malaysian financial sphere: The news headlines will be accumulated for half a decade: From January 2018 to June 2024, so as to have a standard and sufficient amount of material to make an analysis. Such period was selected to test how different economic and market events can affect the correlation between the news sentiment and stock price fluctuation.
![image](https://github.com/user-attachments/assets/f19ec097-4117-4a61-ae75-e5f743571c98)
![image](https://github.com/user-attachments/assets/d4339a0e-16c2-4e67-922c-b5376fe59837)
![image](https://github.com/user-attachments/assets/3d05d5ed-85e8-4ffa-903c-af77960f946b)


## 3.4.2 Stock Price Data
In the same regard, historical data concern to the index of stock price of the Malaysian stock market also will form part of the result headline. This data will be extracted from the Yfinance which includes mandatory columns namely Date, Open, High, Low, Close, Volume, and Adjusted Close prices. From reliable sources like the Bursa Malaysia, which is the Malaysian stock exchange or even from sources like yahoo finance or bloomberg. The following key stock market data will be collected: 
1. Stock Prices, as shown in Table 3.8.
2. Trading Volume: The number of shares traded for a particular stock on a given day.
3. Stock Indices: Relative stock market indexes, for instance, the FTSE Bursa Malaysia KLCI often abbreviated as FBMKLCI, is the main stock market index in Malaysia.
Related stock price data of the particular stock will also be extracted for the same time period as the news article data so that both could be integrated for analysis. The data of the stock prices will be again cleaned and preprocessed so as to handle any missing data, any outliers, or else. Through the inclusion of the Malaysian stock price data, the research will be able to analyse the relationship that exists between news sentiment and actual stock price in the Malaysian market. This will be helpful to investors, traders and especially the financial analyst in a way that they will be able to comprehend the relationship between news sentiment and stock return.
![image](https://github.com/user-attachments/assets/0f26fe6c-5c8f-4bf8-8a4c-596863fdd28c)
![image](https://github.com/user-attachments/assets/e6d585cb-1293-4fb5-a846-e1d1bb31fef3)



## 3.5 Data Preprocessing and Feature Engineering
In the news article collection from the different online source, the data will go through a rigorous process of preprocessing to increase its quality for the sentiment analysis and the stock price prediction modeling to be done on it. In feature engineering, the preprocessed news article data is formatted to a set of useful features that can be used for the analysis of sentiments and stock prices. The feature engineering step will make the dataset ready for the steps that follow sentiment analysis and stock price prediction modeling using both text data and data from the financial market to map the sentiment of news with the volatility of stock prices. Data Preprocessing steps and Feature Engineering as shown in Table 3.6 and Table 3.7, respectively.
![image](https://github.com/user-attachments/assets/7092e0cb-545d-47c3-ad0c-88f2b0e4b3f3)
![image](https://github.com/user-attachments/assets/32ba344d-a0cf-47b5-b33d-f67737969ebd)

## 3.6 	Quantitative Approach
The quantitative component of the research design will involve the following key elements illustrated in Table 3.8.
![image](https://github.com/user-attachments/assets/af312f19-587a-4143-9765-4e1d67e1b1e9)


## 3.6.1 Lexicon-based Approach
To aid the sentiment analysis aspect of the research, sentiment lexicons will be used. These lexicons are collections of words and their corresponding sentiment ratings. These dictionaries will act as a basis for the conventional algorithms used in sentiment analysis, such as the Lexicon-based method. The study will investigate the effectiveness of different sentiment lexicons, such as general-purpose and finance-specific lexicons, to identify the most suitable resources for the Malaysian financial context.
![image](https://github.com/user-attachments/assets/1628f65b-0c40-4a77-b17c-3ce133ce530b)
![image](https://github.com/user-attachments/assets/476a0701-83e1-43c3-bd7d-7b6bf5c6d04f)
![image](https://github.com/user-attachments/assets/94b840f6-135b-4cfb-a49f-cb1c0df2abf7)


## 3.6.2 Machine Learning Models
Training of a model in sentiment analysis in machine learning involves the use of a training dataset which has labels, and categorizing of a text or a document in terms of positive, negative or neutral sentiment. It is often easier and more accurate than the aforementioned lexicon-based approach because it can learn such patterns and relationships from the data. But, it needs a bigger and more marked up data corpus for training and may be slower.
![image](https://github.com/user-attachments/assets/7b9ceaab-f2a4-4f53-ac6f-6fb7e8cbaddd)
![image](https://github.com/user-attachments/assets/ea33d704-e67a-48d2-ae8b-00114c9bfd3b)


## 3.6.3 Sentiment Classification Refinement (Hybrid Approach)
The mixed strategy based on the usage of both the lexicon-selected benchmark and machine learning tools to take advantage of both approaches. In this case, the lexicon-based method is first applied to give a raw sentiment score that is then further adjusted by a machine learning model trained with sentiment labelled data. This can help in giving more accurate and refine sentiment analysis especially when dealing with more elaborate or vague text.
![image](https://github.com/user-attachments/assets/c6a73894-13db-4ea8-a5bf-038437b14a3d)

## 3.6.4 Deep Learning Techniques
As was mentioned before, the modern advancements in deep learning have contributed to the improvement of the sentiment analysis approaches. Some of these are the application of feed forward neural networks for instance convolutional neural networks (CNNs) and recurrent neural networks (RNNs) used in prevailing semantic and contextual nuances of the text data. Analyzing the results of the current deep learning models, a higher level of accuracy compared to traditional machine learning can be achieved, especially in tasks that require an understanding of the depth of the language and sentiment.
Among them, the necessity of the labelled data, the complexity of sentiment patterns identified in the text and the availability of computational power are to be taken into consideration. 
![image](https://github.com/user-attachments/assets/083dfb0d-5eb1-4411-b8b0-1b3d43527446)

## 3.7 Qualitative Approach
The qualitative components of the research design are described in Table 3.11.
![image](https://github.com/user-attachments/assets/308fea83-f71e-4a04-9379-0adb541f335f)

## 3.8 Results and Interpretation
In this phase, the major findings from sentiment analysis and the chosen stock price prediction models elaborated in the previous phase. The results and their interpretation will be structured as follows:
![image](https://github.com/user-attachments/assets/777d5101-11cf-4a68-88e5-bbc690fec5d4)
![image](https://github.com/user-attachments/assets/d1a7a3d3-2e86-4d1e-9cab-a51151acebbe)
![image](https://github.com/user-attachments/assets/11603d13-e44d-42c2-8c8b-35837a0fc4b3)
![image](https://github.com/user-attachments/assets/f1f0601c-effc-48b3-b701-be255131e488)
![image](https://github.com/user-attachments/assets/7da4c16f-e97b-46f4-8bda-8c3df7cac3dc)
![image](https://github.com/user-attachments/assets/03396aae-9d6e-4c24-9f6a-e17b44947415)



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
