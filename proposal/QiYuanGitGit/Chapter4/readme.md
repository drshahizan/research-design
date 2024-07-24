
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

4.4	Expected results
![image](https://github.com/user-attachments/assets/895fe1bb-d87a-4bf8-aef0-636fdec05f89)

4.4.1 Machine Learning (Initial Result)

The process and steps to get initial result of machine learning by using Scikit-learn (sklearn) at Colab as shown at below: 

![image](https://github.com/user-attachments/assets/2d88d1c6-0478-4d68-bb3a-fdfe7b9acdc1)
![image](https://github.com/user-attachments/assets/7ed6d1d6-eae6-4701-b578-e90487aa5131)


