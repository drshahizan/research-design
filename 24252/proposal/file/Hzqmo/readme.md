<a href="https://github.com/drshahizan/research-design/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/research-design" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/research-design/network/members"><img src="https://img.shields.io/github/forks/drshahizan/research-design" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/research-design/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/research-design" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/research-design"><img src="https://img.shields.io/github/issues/drshahizan/research-design" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/research-design/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/research-design?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

<p align="center">
  <img height="300px" src="hziq.jpg" alt="Profile Image">
</p>

<table align="center">
  <tr>
    <th>Name</th>
    <th>Matric No.</th>
  </tr>
  <tr>
    <td>Muhammad Haziq Bin Mohamad</td>
    <td>MCS241036</td>
  </tr>
</table>

# BERT-BASED SEMANTIC SIMILARITY OF MALAYSIAN LEGAL PRECEDENTS

## Files

| No  | Chapter     |                                                 File |
| :-: | ---------- | :---------------------------------------------------------------------------------------------------: |
|  1.  | Proposal | <a href="proposal/"><img src="pdf.svg" width="24px" height="24px"></a> |
|  2.  | Chapter 1 | <a href="Chapter 1/CHAPTER1_HAZIQ.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  3.  | Chapter 2 | <a href="Chapter 2/Chapter 2_Haziq.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  4.  | Chapter 3 | <a href="Chapter 3/Chapter3_Haziq.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  5.  | Chapter 4 | <a href="Chapter 4/CHAPTER 4_Haziq.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  6.  | Chapter 5 | <a href="Chapter 5/CHAPTER 5_HAZIQ.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  7.  | Complete Chapter | <a href="Complete Chapter/THESIS_HAZIQ.pdf"><img src="pdf.svg" width="24px" height="24px"></a> |
|  8.  | Code | <a href="https://colab.research.google.com/drive/1B-WqOO8KPNcM4bX_N_mB_IyfoiRnh7LJ?usp=sharing"><img src="python_icon.png" width="24px" height="24px"></a> |


## Table of Contents
- [Abstract](#abstract)
- [Research Objectives](#research-objectives)
- [Scope of Work](#scope-of-work)
- [Methodology](#methodology)
- [Expected Outcomes](#expected-outcomes)

## Abstract

The increasing volume of digital legal documents within the Malaysian judiciary presents a significant challenge for efficient precedent analysis and legal research. Traditional keyword-based search methods often fail to capture the semantic nuances and contextual complexities inherent in legal texts, leading to incomplete or irrelevant results. Therefore, this project addresses this critical gap by investigating, developing, and evaluating a sophisticated deep learning model for semantic similarity tailored to Malaysian legal precedents. Thus, the primary objective is the development and fine-tuning of a bespoke BERT-based model, leveraging the Sentence-BERT (SBERT) architecture, to accurately quantify the semantic relationship between passages of legal text. For instance, the methodology follows a structured pipeline, commencing with the sourcing and compilation of a specialized corpus of Malaysian legal cases. A rigorous data cleaning and preprocessing phase was executed, featuring text normalization tailored to local legal statutes and terminology. The “all-MiniLM-L6-v2” model was subsequently fine-tuned on this curated dataset using a cosine similarity loss function to optimize for the semantic similarity task. Furthermore, a comprehensive, multi-faceted evaluation framework was implemented to validate the model's performance. The assessment involved quantitative analysis using a suite of metrics including accuracy, precision, recall, F1-score, and Pearson correlation, alongside a qualitative domain-specific analysis to gauge effectiveness across different areas of law. Then, the performance of the fine-tuned model was compared with other baseline model such as Bag of Words (Bow) and Term Frequency-Inverse Document Frequency (TF-IDF). The evaluation was augmented with key visualizations, including confusion matrices and score distribution plots, to provide intuitive insights into the model's predictive behavior. The results demonstrate that the fine-tuned model effectively captures the complex semantic relationships within Malaysian legal discourse, showing significant promise over generalized models. Hence, this research contributes a valuable, domain-specific tool that can enhance legal discovery, support case law analysis, and ultimately improve the efficiency of legal practitioners in Malaysia.






## Keywords

**Semantic Similarity, BERT, Legal NLP, Malaysian Legal Precedents, Legal Information Retrieval**


## Research Objectives

1. To investigate existing semantic similarity methods in the field of legal Natural Language Processing (NLP).

2. To develop and fine-tune a BERT-based model tailored for Malaysian legal case texts.

3. To evaluate and visualize model performance using comprehensive metrics and analysis.

## Scope of Work
- Fine-tune a Sentence-BERT (SBERT) model on English legal sentence pairs to predict semantic similarity.

- Use embeddings to compute similarity scores using cosine similarity.

- Compare SBERT model performance with traditional methods: Bag-of-Words (BoW) and TF-IDF, both evaluated using cosine similarity.

- Evaluate both regression-based scores and classification performance via thresholding.

Out of Scope:

- Full legal document-level similarity or multilingual modeling (e.g., Malay language) is not included.

- No legal advice, decision prediction, or summarization is generated from the model.

## Methodology

1. **Data Collection:**
   - Dataset sourced from Kaggle, comprising English legal case sentence pairs and labeled similarity scores.

- Columns used for model training and comparison:
  
| Column Name     | Description                                                  |
|------------------|--------------------------------------------------------------|
| `id`             | Unique identifier for the sentence pair                      |
| `case1_text`     | Sentence from the first legal case                           |
| `case2_text`     | Sentence from the second legal case                          |
| `case1_domain`   | Legal domain/category of the first case (e.g., contract law) |
| `case2_domain`   | Legal domain/category of the second case                     |
| `true_label`     | Ground truth similarity score (float, 0 to 1)                |

2. **Data Analysis & Modeling:**
   - Text Preprocessing:

- Lowercased all text to ensure uniformity.

- Cleaned punctuation to remove unnecessary symbols that do not contribute to meaning.

- Removed duplicate sentence pairs to prevent bias during training.

- Balanced the dataset using RandomOverSampler from the imblearn library to handle class imbalance (especially for binary classification thresholds).

SBERT Fine-Tuning:

- Fine-tuned a Sentence-BERT model using CosineSimilarityLoss from the sentence-transformers library.

- After training, the model generates embeddings for sentence pairs.

- Cosine similarity is computed between sentence embeddings to produce a final similarity score.

Baseline Methods for Comparison:

- BoW + Cosine Similarity

- TF-IDF + Cosine Similarity

- Used Scikit-learn's CountVectorizer and TfidfVectorizer respectively.

- Cosine similarity computed using sklearn's cosine_similarity.

3. **Validation:**
   - Regression Metrics:

- Pearson Correlation Coefficient

- Spearman Rank Correlation

- R² Score

- Root Mean Square Error (RMSE)

- Mean Absolute Error (MAE)

Classification Metrics (threshold-based):

- Accuracy

- Precision

- Recall

- F1-Score
 (Threshold optimized; e.g., 0.2)

- Split: 80% training, 10% validation, 10% test.



## Expected Outcomes

- A fine-tuned SBERT model capable of capturing the semantic similarity of legal sentence pairs more effectively than traditional NLP techniques.

- Quantitative comparison showing improved correlation and classification metrics for SBERT over BoW and TF-IDF.

- Usable embeddings for downstream tasks such as legal search, recommendation, or clustering.

*For inquiries, contact: [your.email@utm.my]*

 




## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/research-design/issues) for any improvements, suggestions or errors in the content.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

