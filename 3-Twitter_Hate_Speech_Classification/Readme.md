# README

## Twitter Hate Speech Classification

### Problem Statement

The goal of this project is to predict the class label for Twitter data based on the text. The text is classified as hate-speech, offensive language, or neither.

### Dataset

The dataset used in this project is Twitter data and is used to research hate-speech detection. Due to the nature of the study, it’s important to note that this dataset contains text that can be considered racist, sexist, homophobic, or generally offensive. The dataset contains the following columns:

#### Column Description

1. count - number of CrowdFlower users who coded each tweet (min is 3, sometimes more users coded a tweet when judgments were determined to be unreliable by CF)
2. hate_speech - number of CF users who judged the tweet to be hate speech
3. offensive_language - number of CF users who judged the tweet to be offensive
4. neither - number of CF users who judged the tweet to be neither offensive nor non-offensive
5. class - class label for majority of CF users. 0 - hate speech, 1 - offensive language, 2 - neither
6. tweet - text tweet

#### Target Column

The target column is the class label for majority of CF users. It is an integer valued 0 - hate speech, 1 - offensive language, 2 - neither.

### Methodology

We will apply suitable NLP-based algorithms, such as bag-of-words, word embeddings, and deep learning models, to predict the class label for test data based on the text tweet. We will preprocess the text, including tokenization, stopword removal, and stemming or lemmatization, to prepare the data for NLP models. We will use various NLP-based models, such as naive Bayes, logistic regression, support vector machines, and neural networks. We will use cross-validation and hyperparameter tuning to optimize the model's performance and evaluate the models' performance using various evaluation metrics such as accuracy, precision, recall, and F1-score.

### Conclusion

By the end of this project, we will have an NLP-based model that can classify Twitter data as hate-speech, offensive language, or neither.
