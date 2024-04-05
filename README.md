# News-Classifier
### Project Description:
This project aims to build a supervised learning NLP model to classify fake news from true news using the "News Classifier Dataset." The dataset can be found at Kaggle.
Link: [https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)
Embedding used are given under this link: [https://tinyurl.com/NLPLAB3DATA](https://tinyurl.com/NLPLAB3DATA)

### Preprocessing Steps:
Tokenization: The text data will be tokenized into individual words or tokens for further analysis.

Stopword Removal: Commonly occurring words (stopwords) that do not contribute much to the classification will be removed.

Lemmatization : Words will be reduced to their base or root form using lemmatization to reduce feature dimensionality.

### Exploratory Data Analysis (EDA)
EDA provides insights into the dataset's characteristics and distributions. We conduct analyses such as bigram frequency, word frequency mapping, word cloud visualization, and KDE plot for word tokens.

### Vectorization
Two vectorization techniques, Bag of Words and TF-IDF, are employed to prepare the data for classification tasks. The accuracies of these techniques are compared for classification purposes.

### POS Tagging and Fake News Detection
We delve into POS tagging using NLTK and apply various machine learning models for fake news detection. Models include Naive Bayes, LSTM, RNN, and Bidirectional LSTM. Performance metrics such as confusion matrices are presented to evaluate the effectiveness of each model.

### Models:
Logistic Regression Model,
Passive Aggressive Classifier Model
Naive Bayes Model
LSTM 
RNN
Bidirectional LSTM
