# Spam/Ham Email Classifier

## Overview

This project involves building a binary classifier to distinguish between spam and legitimate emails (ham). The classifier uses Natural Language Processing (NLP) techniques and machine learning algorithms to automate the classification of emails.

## Technologies Used

- **Python**: The programming language used for developing the classifier.
- **Scikit-learn**: A machine learning library in Python used for implementing the classification algorithms.
- **Natural Language Processing (NLP)**: Techniques for processing and analyzing text data.
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: A feature extraction method used to represent email text data numerically.
- **Logistic Regression**: A statistical method used for binary classification.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.

## Techniques

The project involved the following steps:

1. **Text Preprocessing**:
   - Removal of stop words.
   - Tokenization of email text.
2. **Feature Extraction**:
   - Vectorization of email text using the TF-IDF approach.
3. **Classification**:
   - Implementation of Logistic Regression and Naive Bayes classifiers to classify emails as spam or ham.
4. **Evaluation**:
   - Performance of the classifiers was evaluated using accuracy metrics.

## Learning Outcomes

- Acquired hands-on experience with text preprocessing techniques and their importance.
- Gained understanding of feature extraction from text data using TF-IDF.
- Experimented with different classification algorithms and assessed their performance.

## Results

- **Logistic Regression**: Achieved an accuracy of approximately 96%.
- **Naive Bayes**: Achieved an accuracy of approximately 93%.

### MNIST Classifier Using SVM

#### Technologies Used
1. Python
2. Scikit-learn
3. Support Vector Machine (SVM)

#### Techniques
The project involved building a multi-class classifier for handwritten digits (0-9) using the MNIST dataset. The preprocessing steps included normalizing the images, and then pixel values were fed into an SVM classifier. Various kernel functions (linear, polynomial, RBF) were tested to improve classification performance.

#### Learning Outcomes
1. Acquired knowledge about the SVM algorithm and its hyperparameters.
2. Investigated the influence of different kernel functions on model performance.
3. Gained insight into the significance of dataset normalization for improving accuracy.

#### Results
1. Linear Kernel: 92% accuracy
2. RBF Kernel: 98% accuracy
![image](https://github.com/user-attachments/assets/693e82a6-37bd-41e4-bb9b-735d8d10d138)
