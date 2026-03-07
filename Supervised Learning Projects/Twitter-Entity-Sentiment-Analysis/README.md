# Twitter Entity Sentiment Analysis

**About the Project**: Twitter Entity Sentiment Analysis 

This project focuses on Natural Language Processing (NLP) and machine learning classification to analyze the sentiment expressed in Twitter data directed at various entities (companies, games, etc.).

**Key Objective**


**Sentiment Classification**: The primary goal is to classify the sentiment of a given text (tweet) into one of four categories: Positive, Negative, Neutral, or Irrelevant.

**Entity-Specific Analysis**: The dataset includes tweets related to different entities such as Amazon, Microsoft, Google, Facebook, and various gaming titles (e.g., CS-GO, Borderlands).

**Methodology**


The project follows a standard NLP workflow:

**Data Loading & Inspection**: Loading the twitter_validation.csv dataset, which contains columns for Id, Media (the entity), Target (the sentiment label), and the tweet Text.

**Text Preprocessing**: The notebook imports essential libraries like nltk and re, indicating steps for text cleaning and normalization will be performed.

**Model Training & Evaluation**: The analysis involved training and evaluating different classifiers, including the Decision Tree Classifier (which achieved an accuracy of 47.79%) and the Random Forest Classifier (which achieved an accuracy of 52.21%).

This project serves as a hands-on demonstration of text preprocessing and supervised learning techniques for Sentiment Analysis.
