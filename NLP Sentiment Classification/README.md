# NLP Sentiment Classification Using TF-IDF

## Project Overview
This project focuses on Natural Language Processing (NLP) to classify customer product or movie reviews into positive and negative sentiment categories.

Text data is cleaned and preprocessed before converting it into numerical features using TF-IDF. Machine Learning algorithms are then trained to predict the sentiment of reviews.

## Objectives
- Clean and preprocess raw text data.
- Remove HTML tags, punctuation and stopwords.
- Apply tokenization and lemmatization.
- Convert text into numerical features using TF-IDF.
- Train and evaluate sentiment classification models.
- Predict sentiment for custom user-input reviews.

## Dataset
**Dataset:** Sentiment Reviews Dataset

**Source:** https://www.datheon.in/datasets/sentiment_reviews.csv

The dataset contains text reviews and their corresponding sentiment labels.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## NLP Techniques
1. Text Cleaning
2. Lowercase Conversion
3. HTML Tag Removal
4. Stopword Removal
5. Tokenization
6. Lemmatization
7. TF-IDF Feature Extraction

## Machine Learning Algorithms
1. Multinomial Naive Bayes
2. Logistic Regression

## Model Evaluation
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Interactive Sentiment Prediction
A custom `predict_sentiment()` function is developed to classify new user-input reviews as:

- Positive
- Negative

## Project Structure
```text
NLP Sentiment Classification/
│
├── NLP_Sentiment_Classification.ipynb
└── README.md
```

## Expected Outcome
The project demonstrates an end-to-end NLP classification pipeline that processes textual reviews, extracts TF-IDF features, trains machine learning models and predicts sentiment for new reviews.

## Author
Harini T

## License
This project is developed for educational purposes.
