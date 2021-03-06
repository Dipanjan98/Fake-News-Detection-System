# Fake-News-Detection

In this project, We have implemented fake news detective classifier by using several NLP techniques and classified news as fake or real by standard Machine Learning alorithms.

## Dataset
Collection of 20,000+ news articles from 2016 US Presidential Election (Trump vs Clinton)

5 columns:

1. id: unique id for a news article </br>
2. title: the title of a news article </br>
3. author: author of the news article </br>
4. text: the text of the article; could be incomplete </br>
5. label: a label that marks the article as potentially unreliable. Where 1: fake and 0: true. </br>

## Data Pre-processing
Cleaning (or pre-processing) the data consists of a number of steps: </br>

Remove Stopwords: English stopwords: is, how, why, where, the, etc. Stopwords are common words that will likely appear in any text. They don’t tell us much about our data so we remove them. </br>

Stemming: Stemming helps reduce a word to its stem (base) form. It removes suffices, like “ing”, “ly”, “s”, etc. by a simple rule-based approach and hence reduces the size of corpus. </br>

## Vectorizing Data
Vectorizing is the process of encoding text as integers i.e. numeric form to create feature vectors so that machine learning algorithms can understand our data. </br>



## Accuracy
Logistic Regression (Accuracy: 96%)</br>
Multinomial-NB Algo (Accuracy: 90%) </br>
Passive Aggressive Classifier Algorithm (Accuracy: 95%) </br>

