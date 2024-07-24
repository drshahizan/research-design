
Chapter 3: Research Methodology

3.1 	Introduction

	In chapter-3, it explores the research methodology employed and is divided into three main parts: Research Design, Problem Formulation, and Datasets, all critical to the overall study's success. Research design outlines the strategic plan implemented to achieve the research objectives. A thorough explanation of the methods and techniques used and the reasons for choosing particular sentiment analysis algorithms and machine learning models is given. This section also addresses the procedural steps taken to collect, process, and analyse data, ensuring the research is carried out systematically and scientifically. Problem formulation is about clearly defining the research problem. This section explores the key challenges in accurately predicting stock prices using sentiment analysis techniques, particularly within the Malaysian context. It outlines the research questions, hypotheses, and objectives, preparing for a focused analysis of the relationship between news sentiment and stock price changes. Datasets provide a thorough summary of the data sources used in the study. This includes a detailed description of the primary data sources, such as reputable Malaysian online news portals like New Straits Times, Bursa Malaysia, and The Edge Market. The section also covers the data collection process, highlighting the criteria for selecting news articles and the methods used to classify sentiments at a granular level. The datasets section ensures transparency in the data handling process and emphasizes the trustworthiness of the information used for analysis.

3.2 	Research Design

This study will employ a mixed-methods research design, combining both approaches of quantitative and qualitative, to investigate the impact of sentiment expressed and found in financial news headlines on stock price movements in the Malaysian market. Research framework for this proposal as below:
![image](https://github.com/user-attachments/assets/b93de487-5843-40a5-a7a8-917270ec3cbc)

3.2.1 	Quantitative Approach

The quantitative component of the research design will involve the following key elements illustrated in Table 3.1.
![image](https://github.com/user-attachments/assets/aaa1078a-6f76-4085-8d79-de9180c4c93a)

3.2.2 	Qualitative Approach

The qualitative components of the research design are described in Table 3.2.

![image](https://github.com/user-attachments/assets/5498e539-c604-4c54-b906-5f4d54ab1fc9)

3.3 	Problem Formulation

Specific problems that the study aims to address are highlighted in Table 3.3.

![image](https://github.com/user-attachments/assets/41c2c5d3-48cd-4f20-9f9d-5ef53da1c9c6)

3.4 	Datasets

The success of any stock price prediction model largely depends on the quality and relevance of the data used for training and evaluation. In the context of this project, the data collection process involves gathering the necessary information to support the analysis and modelling tasks. The description of these datasets is explained in Table 3.4.

![image](https://github.com/user-attachments/assets/332260f4-f893-4ad2-a3ce-862e2e11bf70)

3.4.1 	News Article Data

The main data for this research will be financial news headlines gathered from trusted Malaysian online news websites such as Malaysiakini, New Straits Times, Bursa Malaysia, and The Edge Market. These news sources were selected based on their prominence and credibility in the Malaysian financial landscape. The news headlines will be collected over 5 years, from January 2018 to June 2024, to ensure a robust and representative dataset for analysis. This timeframe was chosen to capture the potential impact of various economic and market events on the relationship among news sentiment and stock price movements.

![image](https://github.com/user-attachments/assets/5d036381-b053-42c7-98eb-af4a60ee1843)

![image](https://github.com/user-attachments/assets/1c7a26c5-9b04-45a2-a37e-e03aac7456f7)

![image](https://github.com/user-attachments/assets/7c744fd8-a1f0-43cf-a146-14a78f45ad20)

3.4.2 	Stock Price Data

In addition to the financial news headlines, the study will also include historical stock price information for the Malaysian stock market. This dataset will be obtained from the yfinance which contains essential fields such as Date, Open, High, Low, Close, Volume, and Adjusted Close prices.

![image](https://github.com/user-attachments/assets/47fd247f-e03d-47f6-9a7b-dd2532612ecb)
![image](https://github.com/user-attachments/assets/fd4db1a8-338a-4eee-a3f7-0dda7bad2393)

3.4.3 	Lexicon-based Approach

To aid the sentiment analysis aspect of the research, sentiment lexicons will be used. These lexicons are collections of words and their corresponding sentiment ratings. These dictionaries will act as a basis for the conventional algorithms used in sentiment analysis, such as the Lexicon-based method. The study will investigate the effectiveness of different sentiment lexicons, such as general-purpose and finance-specific lexicons, to identify the most suitable resources for the Malaysian financial context.

![image](https://github.com/user-attachments/assets/e8a542a5-ec4f-4256-a17f-971e73f96785)

![image](https://github.com/user-attachments/assets/09e58c0e-d7ee-4104-8a4d-d5f02fe0e6e0)
![image](https://github.com/user-attachments/assets/6bf10aa7-1ce1-490d-839c-002dbd4252ea)
![image](https://github.com/user-attachments/assets/801a1d8e-e332-4dfd-a8d6-ea048eec4b24)

3.4.4 	Machine Learning Models

Training a model in machine learning for sentiment analysis involves categorizing text into sentiment categories like positive, neutral, or negative using a dataset with labels. This approach can be more accurate and flexible than the lexicon-based approach, as it can learn to capture more complex patterns and relationships in the data. However, it requires a larger and more labelled dataset for training and can be more computationally intensive.

![image](https://github.com/user-attachments/assets/7734f605-2f07-4808-aa24-b877f39d5bc9)
![image](https://github.com/user-attachments/assets/9a027211-4319-4cc2-ae37-0603bb133d54)

3.4.5 	Sentiment Classification Refinement (Hybrid Approach)

A hybrid approach, or combination of lexicon-based and machine learning-based approaches to leverage the strengths of both methods. In this approach, the lexicon-based approach is used to provide an initial sentiment score, which is then refined and adjusted by using a machine learning model trained on labelled data. This can result in more accurate and robust sentiment analysis, particularly for more complex or ambiguous text.

![image](https://github.com/user-attachments/assets/ac0193cf-15d3-4a1a-923e-548eafd3a7d4)

3.4.6 	Deep Learning Techniques

Recent advancements in deep learning have led to the development of more advanced sentiment analysis techniques. Among them, include the use of neural networks, such as convolutional neural networks (CNNs) and recurrent neural networks (RNNs), use to capture the semantic and contextual information in the text. Deep learning models can provide higher accuracy than traditional machine learning approaches, especially tasks that require a deep understanding of language and sentiment.
When selecting a sentiment analysis technique for stock price prediction, factors such as the availability and quality of labelled data, the complexity of the sentiment expressions in the text, and the computational resources available need to be consider. A combination of different techniques, or a hybrid approach, could provide the best results.



