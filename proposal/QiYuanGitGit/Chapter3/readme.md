
# Chapter 3: Research Methodology

## 3.1 	Introduction
In chapter-3, it explores the research methodology employed and is divided into three main parts: Research Design, Problem Formulation, and Datasets, all critical to the overall study's success. Research design outlines the strategic plan implemented to achieve the research objectives. A thorough explanation of the methods and techniques used and the reasons for choosing particular sentiment analysis algorithms and machine learning models is given. This section also addresses the procedural steps taken to collect, process, and analyse data, ensuring the research is carried out systematically and scientifically. Problem formulation is about clearly defining the research problem. This section explores the key challenges in accurately predicting stock prices using sentiment analysis techniques, particularly within the Malaysian context. It outlines the research questions, hypotheses, and objectives, preparing for a focused analysis of the relationship between news sentiment and stock price changes. Datasets provide a thorough summary of the data sources used in the study. This includes a detailed description of the primary data sources, such as reputable Malaysian online news portals like New Straits Times, Bursa Malaysia, and The Edge Market. The section also covers the data collection process, highlighting the criteria for selecting news articles and the methods used to classify sentiments at a granular level. The datasets section ensures transparency in the data handling process and emphasizes the trustworthiness of the information used for analysis.

## 3.2 	Research Design
This study will employ a mixed-methods research design, combining both approaches of quantitative and qualitative, to investigate the impact of sentiment expressed and found in financial news headlines on stock price movements in the Malaysian market. Research framework for this proposal as below:
![image](https://github.com/user-attachments/assets/e8cd318c-c815-486f-ae5a-acda1c1fcced)



## 3.2.1 	Quantitative Approach
The quantitative component of the research design will involve the following key elements illustrated in Table 3.1.
![image](https://github.com/user-attachments/assets/1da4211b-4bd9-4dda-92de-b1cfd6df8412)


## 3.2.2 	Qualitative Approach

The qualitative components of the research design are described in Table 3.2.
![image](https://github.com/user-attachments/assets/cceae56d-9f67-4da7-ae8f-30326925bb37)


## 3.3 	Problem Formulation
Specific problems that the study aims to address are highlighted in Table 3.3.
![image](https://github.com/user-attachments/assets/0753c1a7-84e1-4743-b7de-d5935445be77)


## 3.4 	Datasets
The success of any stock price prediction model largely depends on the quality and relevance of the data used for training and evaluation. In the context of this project, the data collection process involves gathering the necessary information to support the analysis and modelling tasks. The description of these datasets is explained in Table 3.4.
![image](https://github.com/user-attachments/assets/fcf5268e-a564-49d3-972b-0e3d0f97ba77)


3.4.1 	News Article Data
The main data for this research will be financial news headlines gathered from trusted Malaysian online news websites such as Malaysiakini, New Straits Times, Bursa Malaysia, and The Edge Market. These news sources were selected based on their prominence and credibility in the Malaysian financial landscape. The news headlines will be collected over 5 years, from January 2018 to June 2024, to ensure a robust and representative dataset for analysis. This timeframe was chosen to capture the potential impact of various economic and market events on the relationship among news sentiment and stock price movements.

![image](https://github.com/user-attachments/assets/5d036381-b053-42c7-98eb-af4a60ee1843)

![image](https://github.com/user-attachments/assets/ebb7fd6e-50c8-4e78-844d-0f386937a12e)

![image](https://github.com/user-attachments/assets/28241dbc-e859-4d4e-a910-0e80f596fa56)


## 3.4.2 	Stock Price Data
In addition to the financial news headlines, the study will also include historical stock price information for the Malaysian stock market. This dataset will be obtained from the yfinance which contains essential fields such as Date, Open, High, Low, Close, Volume, and Adjusted Close prices.
![image](https://github.com/user-attachments/assets/bbb45a5c-740d-4f9d-a292-ccbbe2d7dfbe)
![image](https://github.com/user-attachments/assets/fd4db1a8-338a-4eee-a3f7-0dda7bad2393)

## 3.4.3 	Lexicon-based Approach
To aid the sentiment analysis aspect of the research, sentiment lexicons will be used. These lexicons are collections of words and their corresponding sentiment ratings. These dictionaries will act as a basis for the conventional algorithms used in sentiment analysis, such as the Lexicon-based method. The study will investigate the effectiveness of different sentiment lexicons, such as general-purpose and finance-specific lexicons, to identify the most suitable resources for the Malaysian financial context.

![image](https://github.com/user-attachments/assets/e8a542a5-ec4f-4256-a17f-971e73f96785)
![image](https://github.com/user-attachments/assets/dd16a56c-d531-4e7c-a459-0b54fb64f2ea)
![image](https://github.com/user-attachments/assets/6bf10aa7-1ce1-490d-839c-002dbd4252ea)
![image](https://github.com/user-attachments/assets/896000b7-575c-4452-812f-d5c0dcfb9079)

## 3.4.4 	Machine Learning Models
Training a model in machine learning for sentiment analysis involves categorizing text into sentiment categories like positive, neutral, or negative using a dataset with labels. This approach can be more accurate and flexible than the lexicon-based approach, as it can learn to capture more complex patterns and relationships in the data. However, it requires a larger and more labelled dataset for training and can be more computationally intensive.

![image](https://github.com/user-attachments/assets/7734f605-2f07-4808-aa24-b877f39d5bc9)
![image](https://github.com/user-attachments/assets/2491c33f-08e1-4101-b198-b399be45a28f)

## 3.4.5 	Sentiment Classification Refinement (Hybrid Approach)
A hybrid approach, or combination of lexicon-based and machine learning-based approaches to leverage the strengths of both methods. In this approach, the lexicon-based approach is used to provide an initial sentiment score, which is then refined and adjusted by using a machine learning model trained on labelled data. This can result in more accurate and robust sentiment analysis, particularly for more complex or ambiguous text.

![image](https://github.com/user-attachments/assets/ac0193cf-15d3-4a1a-923e-548eafd3a7d4)

## 3.4.6 	Deep Learning Techniques

Recent advancements in deep learning have led to the development of more advanced sentiment analysis techniques. Among them, include the use of neural networks, such as convolutional neural networks (CNNs) and recurrent neural networks (RNNs), use to capture the semantic and contextual information in the text. Deep learning models can provide higher accuracy than traditional machine learning approaches, especially tasks that require a deep understanding of language and sentiment.
When selecting a sentiment analysis technique for stock price prediction, factors such as the availability and quality of labelled data, the complexity of the sentiment expressions in the text, and the computational resources available need to be consider. A combination of different techniques, or a hybrid approach, could provide the best results.
![image](https://github.com/user-attachments/assets/acad213c-48d5-430c-848f-adcab2d97518)


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
