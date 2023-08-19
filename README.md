# Spam-Classifier


## 📌 Introduction:-

A Natural Language Processing with SMS Data to predict whether the SMS is Spam/Ham with various ML Algorithms like multinomial-naive-bayes,logistic regression,svm,decision trees to compare accuracy and using various data cleaning and processing techniques like PorterStemmer,CountVectorizer,TFIDF Vetorizer,WordnetLemmatizer.
It is implemented using LSTM and Bi-directional LSTM to gain accuracy of 97.84%(LSTM) and  98.9%(Bi-directional LSTM).

## ✔❌Accuracy ❌✔:-
| Text Preprocessing Type              | Logistic Regression | Multinomial NB | Support Vector Machine  | Decision Tree |
|--------------------------------------|---------------------|----------------|-------------------------|---------------|
| TFIDF Vectorizer + PorterStemmer     | 96.68%              | 97.30%         | 98.47%                  | 96.68%        |
| CountVectorizer + PorterStemmer      | 98.65%              | 98.56%         | 98.74%                  | 97.84%        |
| CountVectorizer + WordnetLemmatizer  | 98.56%              | 98.29%         | 98.38%                  | 97.75%        |
| TFIDF Vectorizer + WordnetLemmatizer | 96.41%              | 97.48%         | 98.47%                  | 96.86%        |



## 🏁 Datasets Used:-
* The dataset used is SMS Spam Dataset created by UCI Machine Learning.This dataset is downloaded in kaggle.You can download it [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset/download).

## 📧Contact:-
For any kind of suggesstions/ help in models code Please mail me at thananseyakalanithi@gmail.com .


