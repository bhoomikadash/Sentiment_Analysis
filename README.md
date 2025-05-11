# Social Media Sentiment Analysis

A machine learning project to classify social media comments (tweets) as positive or negative using NLP and supervised learning techniques.

1) Introduction

Social media platforms like Twitter are rich sources of public opinion. This project applies **Sentiment Analysis**—an NLP technique—to classify tweets as either **positive** or **negative**, helping brands and analysts track public sentiment.

2) Objectives

- Clean and preprocess noisy tweet data.
- Convert text data into numerical features using **TF-IDF**.
- Train and compare multiple ML models for sentiment classification.
- Evaluate the models using accuracy, precision, recall, and F1-score.

3) Dataset

- **Source:** Preprocessed Sentiment140 dataset with 1.6 million labeled tweets.
- **Labels:** Positive (1) and Negative (0)
- **Challenges:** 
  - No neutral class
  - Noisy, short, and sarcastic content

4) Preprocessing

- Lowercasing text  
- Removing URLs, hashtags, mentions, punctuation, and numbers  
- Vectorizing text using **TF-IDF**

5) Models Used

| Model                         | Accuracy |
|------------------------------|----------|
| Logistic Regression          | 79.03%   |
| Stochastic Gradient Descent (SGD) | 78.04%   |
| XGBoost                      | 72.75%   |

6) Evaluation

- Logistic Regression showed the best performance.
- SGD had better recall for positive sentiments.
- XGBoost performed decently but lagged behind on negative sentiment recall.

7) Future Work

- Integrate **transformer-based models** (e.g., BERT, RoBERTa) for improved context handling.
- Improve sarcasm detection and ambiguity resolution.
- Apply the system to:
  - Fake news & hate speech detection
  - Customer feedback monitoring
  - Brand sentiment analysis


