# Detecting Fake News with Python

The main goal is to build a model to classify a piece of news as REAL or FAKE. In this repo TfidfVectorizer is implemented on dataset along with PassiveAggressiveClassifier.

# TfidfVectorizer

The TfidfVectorizer will allow you to encode new documents by converting a collection of raw documents into a matrix of TF-IDF features. 

In general, TF-IDF is a statistical measure that evaluates how relevant a word is to a document in a collection of documents. 
Two metrics : 
i) Term Frequency(TF) - number of times a word appears in a document
ii) Inverse Document Frequency(IDF) - simply it is a measure of how significant a term is present in the entire corpus.

# Passive Aggressive Classifier
Passive Aggressive algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. The purpose of passive aggressive algorithm is to make updates that correct the loss. 

By using sklearn, we build a TfidfVectorizer on our dataset. Then, we initialize a PassiveAggressiveClassifier and fit the model.

You can download the dataset [here.](https://drive.google.com/file/d/1C-Ei3aQOhwjZ2GCieFs9LjFV0Olej6rV/view?usp=sharing)

# Dependencies
- Numpy
- Pandas
- Sklearn


# Result
Ended up by obtaining an accuracy of 92%. 
