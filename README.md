# SentimentClassifier
Implemented a Naive Bayes Classifier for sentiment analysis on test data by utilizing a corpus tokenized from real and fake news datasets. Each row underwent preprocessing steps including tokenization, lemmatization, and stemming. Upon completion of preprocessing, the dataset was divided into 70% for training and 30% for testing purposes. Manual sentiment analysis was conducted on the training data, determining the polarity of each row and assigning it a polarity score (1 for Positive, 0 for Neutral, -1 for Negative). Subsequently, a Multinomial Naive Bayes Classifier was developed and applied to perform sentiment analysis on the test data.


# Built With
 
* Jupyter Notebook
* Libraries: NLTK, SKLearn, pandas, numpy
* Language: Python

# Examples

* Pre-processed Text: 
![Pre-processed Text](images/pre-processed.png)


* Post-processed Text:
![Post-processed Text](images/post-processed.png)


* Manual Sentiment Analysis:
![Manual Sentiment Analysis](images/manual_sentiment.png)


* Naive Bayes Classifier Sentiment Analysis:
![Naive Bayes Classifier Sentiment Analysis](images/naive_bayes.png)


# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
