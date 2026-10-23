Financial Sentiment Analysis Using Machine Learning and Deep Learning

Project Overview

This project classifies financial news sentences into three sentiment categories: negative, neutral, and positive.

Dataset

Name: Financial PhraseBank

Configuration: Sentences 50Agree

Original samples: 4,846

Samples after removing duplicate sentences: 4,838

Training samples: 3,870

Testing samples: 968

Models Implemented

Logistic Regression with TF-IDF

Support Vector Machine (SVM) with TF-IDF

Long Short-Term Memory (LSTM) neural network

Technologies Used

Python

Pandas and NumPy

Scikit-learn

TensorFlow / Keras

Matplotlib

Google Colab

Results

Model

Accuracy

Weighted F1-score

Logistic Regression

76.24%

74.29%

SVM

77.27%

76.58%

LSTM

65.70%

64.74%

SVM achieved the highest accuracy and weighted F1-score among the three evaluated models.

Repository Contents

iNeuBytes_Task2_Sentiment_Analysis.ipynb — implementation notebook

iNeuBytes_Task2_Sentiment_Analysis_Report.docx — project report

task2_classification_reports.txt — detailed classification metrics

task2_model_comparison.csv — model comparison results

task2_model_comparison.png — performance comparison graph

How to Run

Open the notebook in Google Colab, run the cells in order, and ensure the required Python libraries are installed.

Conclusion

The experiments compare traditional machine learning methods with an LSTM-based deep learning model for financial sentiment classification. SVM performed best on the current test split.
