A visual representation of the project framework is shown in Figure 1. It contains the flow of the project in conducting topic-based sentiment analysis on Langkawi, Kedah. The entire process can be categorised into six phases:

1. Problem Formulation
2. Data Collection
3. Data Pre-processing
4. Modelling
5. Testing and Validation
6. Performance Evaluation


<p align="center">
  <img src="https://github.com/user-attachments/assets/2dffad2e-ac08-407a-ae2a-881c1b59da0a">
</p>
Figure 1: Project Framework

## Problem Formulation

The primary aim of this project is to identify the key topics that influence the tourists in Langkawi, Kedah using BERTopic and using deep learning methods for sentiment classification on chosen topics. Understanding tourist sentiments in Langkawi, Kedah, is critical for improving services and visitor experiences. Traditional sentiment analysis approaches may not fully capture the nuances of user feedback. Advanced models such as BERTopic, LSTM, and BERT could increase sentiment analysis accuracy.

## Data Collection

Tourists' reviews are crawled from TripAdvisor websites using Instant Data Scraper, SimpleScraper and Apify. The data collection is done by restricting the review’s date starting from January 2020. 5 popular destinations are chosen based on TripAdvisor Travellers Choice; Langkawi Sky Bridge, Crocodile Adventureland Langkawi, Kilim Geoforest Park, Cenang Beach, Telaga Tujuh Waterfalls and Underwater World Langkawi. 1,187 reviews are extracted from TripAdvisor website. The datasets with their description are summarised in Table 1. TripAdvisor has a filter section where the language of the review can be chosen. Since this project scope focuses on English dataset, only English reviews are extracted. However, Google Map website does not have filter features, hence the dataset consists of multiple languages such as Chinese, Arabic, Malay, English, German. The data cleaning process will be discussed in the next sub section.

## Data Pre-processing

Preliminary analysis is done to understand the data and identifies the important and related features needed for the project. This dataset contains 1187 rows and 24 columns. The first step is removing unwanted columns from the dataset to get a better view of the dataframe. After deleting unwanted columns, the remaining columns are renamed into more understandable formats and re-arrange to four columns; Destination, TravelDate, Rating and Review. Review column is the concatenation of text (the reviews) and title (title of the reverie) columns. Data cleaning includes finding duplicate and missing rows and removing them. Then, both datasets are concatenated into a single dataframe for further data cleaning. 


![1](https://github.com/user-attachments/assets/a836f19e-5d81-4c0d-94fd-72347370cec4)

Figure 2: Name of columns of the dataset.

![2](https://github.com/user-attachments/assets/eb99671c-aabc-43ff-a922-1acd6c51f266)

Figure 3: Dataset before cleaning

![3](https://github.com/user-attachments/assets/7e12aad4-47f7-4ffa-927c-878d6d6aee32)

Figure 4: Dataset after cleaning.

![image](https://github.com/user-attachments/assets/8a5c4949-a817-4828-afbf-bce6205c7bf4)

Figure 5: Summarisation of duplicate and missing rows.



