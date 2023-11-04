
# Movie Genre Classification

**CODSOFT TASK 1**

The movie genres are predicted based on the plot summary.

# Author

Samriddhi Karki

# Batch

October 15 - November 15

# Domain

Machine Learning

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Term Frequency-Inverse Document Frequency (TF-IDF)](#term-frequency-inverse-document-frequency-tf-idf)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Testing on New Data](#testing-on-new-data)

## Introduction

This project explores text classification techniques to predict movie genres based on plot summaries. Various models, including Naive Bayes, Random Forest, and Logistic Regression, have been implemented and evaluated to determine the classification accuracy.

## Dataset

The dataset used contains movie titles, genres, and plot descriptions. The data is separated by ':::' and '\n' characters, which are cleaned and preprocessed for further analysis.

## Data Preprocessing

Following steps have been applied to plot descriptions to create a clean and uniform dataset for classification.

- Cleaning the text by removing non-alphabetic characters and converting it to lowercase.
- Tokenizing the text and removing common stopwords.
- Lemmatization to reduce words to their base forms.



## Term Frequency-Inverse Document Frequency (TF-IDF)

The Term Frequency-Inverse Document Frequency (TF-IDF) technique is used to transfrom the text data into numerical features. TF-IDF measures the importance of a word within a document relative to all documents in the dataset. 

## Model Training

The dataset is split into training and test sets, and different classification models are trained:

- **Random Forest Classifier**: Movie genres are predicted using TF-IDF-transformed features and multiple decision trees.

- **Naive Bayes Classifier**:  Genre labels have been encoded for training and testing.

- **Logistic Regression Classifier**: This model uses TF-IDF features to predict genres and provides high accuracy for genre classification.

The models are evaluated to select the one with the highest accuracy for further testing.

## Model Evaluation

The models are evaluated using metrics such as accuracy, precision, recall, and F1-score to assess their performance on the test dataset.

## Testing on New Data

The selected Logistic Regression model is used to predict genres for new movies based on their plot descriptions. 

The project's accuracy of the data is approximately 71%.

Enjoy!
