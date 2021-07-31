# SMS-spam-detection

#### The dataset of the model can be found [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset)

In this project, I have explored and compared text preprocessing and feature selection methods among word count, character count, bag of words, removing stop words,and Lemmatization. [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier#Multinomial_na%C3%AFve_Bayes) classifier is used to detect ham or spam SMS messages. The dataset is a collection of 5,574 text messages in English, taggled according being ham (legitimate) or spam.

**Libraries and Modules used**
- Pandas
- Numpy
- NLTK
- Sklearn

#### **Result**
- Confusion matrix :- [[939,10],[8,158]]
- F1-Score :- 0.99(Spam),0.95(Ham)
- Accuracy :- 0.98

