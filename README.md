# Word-Level-Language-Identification-for-Code-Mixed-Social-Media-Content
This repository contains code for word-level language identification in code-mixed social media content. It utilizes various techniques such as TF-IDF, logistic regression, SVM, MLP classifier, and BERT-based deep learning models. The project aims to accurately identify the language of English and Kannada words in Roman script.
ntroduction and Problem Definition
Word-level language identification is an essential prerequisite for extracting useful information from code-mixed social media content. Previous studies have shown that considering the local context and isolating words from their context lead to effective language classification. This project addresses these observations and aims to accurately identify the language of code-mixed words.

Dataset
The CoLI-Kenglish dataset is utilized in this project. It consists of English and Kannada words in Roman script and is grouped into six major categories: "Kannada", "English", "Mixed-language", "Name", "Location", and "Other".

Code Overview
The code provides implementations of the following techniques and models:

TF-IDF: Utilizes the TfidfVectorizer from scikit-learn to convert the training and test data into TF-IDF features. Logistic regression and linear SVM models are trained and evaluated using these features.

MLP Classifier: Implements a multilayer perceptron (MLP) classifier using the MLPClassifier from scikit-learn. This model uses TF-IDF features as input.

BERT-Based Model: Utilizes BERT-based models for language identification. The code uses the Hugging Face transformers library to load the pre-trained BERT model and tokenizer. The BERT model is fine-tuned using a custom neural network architecture and trained on the provided dataset.
