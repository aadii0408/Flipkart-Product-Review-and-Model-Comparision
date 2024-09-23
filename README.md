# FlipKart Product Review and Model Comparison

##Project Overview
> This project aims to perform sentiment analysis on Flipkart product reviews using various machine learning models. We have compared the performance of three models:

- Logistic Regression Model
- Random Forest Classifier
- Naive Bayes Model
The objective is to determine which model is best suited for the sentiment analysis of product reviews on Flipkart.

- Dataset
The dataset used for this project consists of Flipkart product reviews, which have been labeled with positive or negative sentiments. The dataset has been preprocessed for text cleaning, tokenization, and feature extraction.

## Models Compared
1. Logistic Regression Model
The Logistic Regression model is a linear model that estimates the probability that a given input belongs to a certain class. It works well for binary classification tasks such as sentiment analysis.

2. Random Forest Classifier
The Random Forest Classifier is an ensemble learning method that builds multiple decision trees and merges them together to get a more accurate and stable prediction.

3. Naive Bayes Model
The Naive Bayes model is based on Bayes’ Theorem and assumes independence between predictors. It is simple and effective for text classification tasks.

## Model Performance
The models were evaluated based on the following metrics:

- Accuracy
- Precision
- Recall
- F1-score

## Results
Based on the evaluations, the Logistic Regression Model and the Random Forest Classifier performed better than the Naive Bayes Model. However, when comparing Logistic Regression and Random Forest, both models performed almost equally well for this dataset.

| Model                   | Accuracy | Precision | Recall | F1-score |
|--------------------------|----------|-----------|--------|----------|
| Logistic Regression       | 0.87     | 0.88      | 0.86   | 0.87     |
| Random Forest Classifier  | 0.88     | 0.87      | 0.87   | 0.88     |
| Naive Bayes               | 0.79     | 0.80      | 0.78   | 0.79     |

## Conclusion
From the analysis, it is observed that both Logistic Regression and Random Forest Classifier are well-suited for sentiment analysis of Flipkart reviews. They outperform the Naive Bayes Model significantly. Although both Logistic Regression and Random Forest performed almost equally, the Random Forest Classifier is slightly better and may be more suited for this task due to its robustness and flexibility.

## Technologies Used
- Python: Core language for building the models.
- scikit-learn: Used for machine learning models, evaluation metrics, and data preprocessing.
- pandas: For data manipulation and handling.
- nltk (Natural Language Toolkit): For text preprocessing, including tokenization and stopword removal.
- matplotlib/seaborn: For data visualization of the model performance.
