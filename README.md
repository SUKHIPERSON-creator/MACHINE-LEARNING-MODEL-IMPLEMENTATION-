COMPANY = CODTECH IT SOLUTIONS

NAME = AAKASH PASWAN

INTERN ID : CT04DG1070

DOMAIN : PYTHON PROGRAMMING

DURATION:4 WEEKS

MENTOR NEELA SANTOSH
# MACHINE-LEARNING-MODEL-IMPLEMENTATION
                       Spam Detection Using Machine Learning
This project implements a simple spam email classifier using Natural Language Processing (NLP) and Multinomial Naive Bayes. It reads an email dataset and predicts whether a message is spam or ham (not spam) based on the content of the email.

🔍 Features
Dataset: CSV-based labeled spam/ham email dataset

Text preprocessing using CountVectorizer

Model: Multinomial Naive Bayes classifier

Performance evaluation using accuracy score and confusion matrix

Includes prediction test on a custom email input
 The code follows these key steps:

Data Loading
Loads the labeled email dataset (spam_ham_dataset.csv) containing the email text and a label (label_num: 1 for spam, 0 for ham).

Data Preparation

x stores the email texts (features)

y stores the corresponding labels (target)

Data is split into training and testing sets (80/20 split)

Text Vectorization

Uses CountVectorizer from sklearn to convert raw email texts into numerical feature vectors that ML models can understand.
#Model Training
Trains a Multinomial Naive Bayes model, which is ideal for text classification problems like spam detection.
Prediction & Evaluation
The trained model is used to predict the labels of the test data
#Model performance is evaluated using:

Accuracy Score
Confusion Matrix
 #Requirements
Python
pandas
numpy
scikit-learn (sklearn)

Output:-



