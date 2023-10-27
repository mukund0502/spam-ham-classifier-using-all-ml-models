Spam Ham Classification Using Glove NLP Preprocessing and Various Machine Learning Models
This repository contains code for classifying SMS messages as spam or ham using a variety of machine learning models, including SVM, decision tree, logistic regression, AdaBoost, random forest, KNN, naive Bayes, and gradient boosting. The code also preprocesses the SMS messages using GloVe, a word embedding technique.

To run the code, you will need to have the following Python libraries installed:
1. NumPy
2. Pandas
3. Scikit-learn
4. NLTK
5. GloVe
Once you have the required libraries installed, you can run the code.

Machine learning models used for clasification: 
1. Logistic Regression
2. SVM
3. Decision Tree	
4. AdaBoost	
5. Random Forest	
6. KNN	Precision: 
7. Naive Bayes	
8. Gradient Boosting   


******* SVM ********

printing old classification report: 

              precision    recall  f1-score   support

           0       0.97      1.00      0.98      1191
           1       0.98      0.79      0.87       202
    accuracy                           0.97      1393
    macro avg      0.97      0.89      0.93      1393
    weighted avg   0.97      0.97      0.97      1393


confusion matrix for old model: 

    1188   3
    43    159


**** KNN ****
printing old classification report: 

              precision    recall  f1-score   support

           0       0.88      1.00      0.94      1191
           1       0.92      0.23      0.37       202

    accuracy                           0.89      1393
    macro avg      0.90      0.61      0.65      1393
    weighted avg   0.89      0.89      0.86      1393


confusion matrix for old model: 

    1187    4
    155    47



**** Random forest ****
printing old classification report: 

              precision    recall  f1-score   support

           0       0.94      1.00      0.97      1191
           1       1.00      0.62      0.77       202

    accuracy                           0.95      1393
    macro avg      0.97      0.81      0.87      1393
    weighted avg   0.95      0.95      0.94      1393


confusion matrix for old model: 

    1191   0
    76    126



**** Logistic regression ****
printing old classification report: 
              precision    recall  f1-score   support

           0       0.97      0.98      0.98      1191
           1       0.88      0.84      0.86       202

    accuracy                           0.96      1393
    macro avg      0.93      0.91      0.92      1393
    weighted avg   0.96      0.96      0.96      1393


confusion matrix for old model: 

    1169   22
    33    169




**** Naive Bayse ****
printing old classification report: 
              precision    recall  f1-score   support

           0       1.00      0.01      0.01      1191
           1       0.15      1.00      0.25       202

    accuracy                           0.15      1393
    macro avg      0.57      0.50      0.13      1393
    weighted avg   0.88      0.15      0.05      1393


confusion matrix for old model: 

    9  1182
    0  202



**** GB ****
printing old classification report: 
              precision    recall  f1-score   support

           0       0.97      0.98      0.97      1191
           1       0.85      0.79      0.82       202

    accuracy                           0.95      1393
    macro avg      0.91      0.88      0.90      1393
    weighted avg   0.95      0.95      0.95      1393


confusion matrix for old model: 

    1163   28
    42    160



**** Decision Tree ****
printing old classification report: 
              precision    recall  f1-score   support

           0       0.95      0.95      0.95      1191
           1       0.70      0.71      0.70       202

    accuracy                           0.91      1393
    macro avg      0.82      0.83      0.83      1393
    weighted avg   0.91      0.91      0.91      1393


confusion matrix for old model: 

    1128   63
    58    144




**** AdaBoost ****

printing old classification report: 
              precision    recall  f1-score   support

           0       0.95      0.98      0.96      1191
           1       0.84      0.70      0.77       202

    accuracy                           0.94      1393
    macro avg      0.90      0.84      0.86      1393
    weighted avg   0.93      0.94      0.94      1393


confusion matrix for old model: 

    1164   27
    60    142





