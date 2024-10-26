# Sentiment Analysis of the Israel-Palestine Conflict on Twitter

## Project Overview
In this project, I analyzed Twitter data to understand public sentiment surrounding the Israel-Palestine conflict. By focusing on tweets with hashtags like `#standwithisrael` and `#standwithpalestine`, the project captures a wide range of opinions. We examine how these sentiments evolve over time in response to major events, providing deeper insight into public opinion on this complex topic. This approach combines sentiment analysis with temporal tracking to highlight shifts in discourse, contributing valuable context to this sensitive geopolitical discussion.

## Step-by-Step Procedure

### 1. Data Collection
- **Tool Used**: NTScraper
- **Action**: Gathered a substantial volume of tweets tagged with relevant hashtags like `#standwithisrael` and `#standwithpalestine` to represent diverse viewpoints.

### 2. Data Preprocessing
- **Tokenization**: Split text into individual words or tokens.
- **Text Normalization**: Converted text to lowercase to ensure uniformity.
- **Lemmatization**: Reduced words to their root form for standardization.
- **Clean Text Preparation**: Removed special characters, URLs, mentions, and irrelevant words to refine the dataset.

### 3. Feature Extraction
- **Techniques Used**: TF-IDF (Term Frequency-Inverse Document Frequency) and Word2Vec.
- **Action**: Transformed preprocessed text into numerical vectors suitable for machine learning models.

### 4. Model Training
- **Algorithms Tested**: Random Forest, Support Vector Machine (SVM), Logistic Regression (TF-IDF), Logistic Regression (Word2Vec), and Decision Tree.
- **Action**: Trained and evaluated various machine learning algorithms to classify tweet sentiments effectively.

### 5. Model Evaluation
- **Best-Performing Model**: Support Vector Machine (SVM)
- **Accuracy Achieved**: 86.5%
- **Action**: Selected SVM as the final model based on its high accuracy in sentiment classification.

### 6. Temporal Sentiment Analysis
- **Action**: Analyzed sentiment trends over time, correlating shifts with key geopolitical events and developments.

### 7. Insights and Analysis
- **Objective**: To observe how public sentiment changed in response to significant events in the Israel-Palestine conflict.
- **Outcome**: The project offers valuable insights into the dynamic nature of public sentiment and its contextual shifts over time.

## Summary
This project developed a robust sentiment classification model and conducted a comprehensive temporal analysis of Twitter sentiments related to the Israel-Palestine conflict. By testing various machine learning models and analyzing sentiment trends over time, it provides nuanced insights into this complex discourse, highlighting how public opinion evolves with real-world events.
