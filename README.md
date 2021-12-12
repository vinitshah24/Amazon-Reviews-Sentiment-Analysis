# Sentiment Analysis on Amazon Customer Review Dataset

The key goal of this project is to develop the sentiment analysis model which would allow the company to
classify whether a particular customer review is positive or negative. To develop the model, the raw
unstructured data is preprocessed through a series of NLP techniques like removing stop words,
applying lemmatization, applying tokenization, etc. Once the data is cleaned, several different Machine
Learning models are tested:

* Gaussian Naïve Bayes
* Multinomial Naïve Bayes
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Logistic Regression
* Long Short-Term Memory (LSTM) model

After applying the models, several performance metrics like accuracy, precision, recall, F1-measure,
and AUI score will be considered and analyzed to determine the model which best fits the dataset.