For exploratory data analysis, we want to analyse the corpus with details by identifying the most frequent words in the corpus and this can be established by using WordCloud. The first step is to expand contractions. The shortened version of words  “don’t”  is changed to “do not”. The next step is by converting all documents into lowercase letters to standardise them. Any punctuation like commas, full stops, hyphens are removed. The next step is preparing data for Document Term Matrix where it provides the frequency of words in a collection of documents. In this section, the steps include removing stop words which are the most common words such as ‘I’, ‘this’, ‘is’. 
Expand Contractions
Lowercase characters
Punctuation Removals
Stop Words Removal
Lemmatization

![image](https://github.com/user-attachments/assets/ad12a5bb-5806-4998-8e26-7dc2a1391e4a)

Figure : Before processing steps.

![image](https://github.com/user-attachments/assets/71453529-f2bd-4910-98ab-0773f9cb00af)

Figure : After processing steps.

The following step is lemmatization where words are converted into their base form. The SpaCy library is used for these steps. After that, a document-term matrix is created and wordcloud library is used to plot those words. Word clouds are the visualisation of words where the bigger the size of the word, the more frequent it appears in the corpus.

![image](https://github.com/user-attachments/assets/95f3a4e5-e0a0-44d5-9c9c-638f52333ac4)

Figure : Number of Reviews per Destination.

![image](https://github.com/user-attachments/assets/43429131-7211-4e59-be13-6da81c153ffd)

Figure : Number of Reviews per Rating.

![image](https://github.com/user-attachments/assets/64e56789-854d-4323-8e29-72cb0f03017b)

Figure : WordCloud of the corpus.

![image](https://github.com/user-attachments/assets/32aa41aa-e8b9-40e5-a5ea-f76fa7f17ed6)

Figure : WordCloud for each destination.
