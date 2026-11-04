# HateSpeech-detection Report

LSTM RNN (Without Dropout)

              precision    recall  f1-score   support

           0       0.65      0.84      0.73       329
           1       0.70      0.45      0.55       269

    accuracy                           0.67       598
   macro avg       0.67      0.65      0.64       598
weighted avg       0.67      0.67      0.65       598

LSTM RNN (with Dropout)

              precision    recall  f1-score   support

           0       0.55      1.00      0.71       329
           1       0.00      0.00      0.00       269

    accuracy                           0.55       598
   macro avg       0.28      0.50      0.35       598
weighted avg       0.30      0.55      0.39       598

Bidirectional LSTM (Without Dropout)

              precision    recall  f1-score   support

           0       0.55      0.69      0.61       321
           1       0.54      0.39      0.45       302

    accuracy                           0.55       623
   macro avg       0.55      0.54      0.53       623
weighted avg       0.55      0.55      0.53       623


Bidirectional LSTM (No Dropout)

              precision    recall  f1-score   support

           0       0.59      0.63      0.61       321
           1       0.58      0.54      0.56       302

    accuracy                           0.59       623
   macro avg       0.59      0.59      0.59       623
weighted avg       0.59      0.59      0.59       623

MultinomialNB:

              precision    recall  f1-score   support

           0       0.72      0.69      0.71       343
           1       0.61      0.64      0.63       255

    accuracy                           0.67       598
   macro avg       0.67      0.67      0.67       598
weighted avg       0.67      0.67      0.67       598

LogisticRegression: 

              precision    recall  f1-score   support

           0       0.73      0.75      0.74       343
           1       0.65      0.63      0.64       255

    accuracy                           0.70       598
   macro avg       0.69      0.69      0.69       598
weighted avg       0.69      0.70      0.69       598
