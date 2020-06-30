# Scikit-Learn-Workshop

### Short Description

This workshop provides an introduction to reading using Python and the scikit-learn library to categorize documents. As a working example, we will use movie reviews to train a machine learning model to assess the sentiment (positive or negative) of a movie review. then This material is designed for at programmers, data scientists, and researchers who would like to get started with machine learning for natural language processing and analysis. 

### Long Description

Scikit-learn is a widely used Python baased machine learning and natural language processing library. This library provides methods for supervised and unsupervised learning, an implementation of different machine learning algorithms, and tools for common data preparation tasks involved in machine leaarning programming projects.

This workshop will focus on programming methods for using scikit-learn, rather than the theory behind the algorithms. The first workbook will introduce machine learning, document categorizaation, and sentiment analysis using a very small dataset. The second workbook will apply these techniques to a larger dataset using a scikit-learn pipeline. 

Through these two workbooks, participants will use scikit-learn to"

1. Find the vocabulary used in a collection of documents (a "bag of words")

2. Create a document vector for each document in a collection, indicating the word frequencies for each word in the entire collection

3. Scale the document term frequencies to reflect the greater and lesser frequency of certain terms

4. Use the word vectors and sentiment score for each document to train a machine learning model to recognize and assess document sentiment
 
5. Apply the machine learning model to assess the sentiment (or category) of new documents in the collection. 

### Prerequisites

This tutorial is intended for participants who have basic programming experience with Python, including loops, conditionals, and lists. No previous experience with scikit-learn or machien learning is expected. Some familiarity with pandas will help, but we will cover these concepts in the context of populating a scikit-learn model.  

## Workbooks

This tutorial consists of a series of notebooks. Further explanatory text is available in the notebook for each section or the tutorial. 

### Sentiment-Example.ipynb

How to create, populate, and apply a sentiment model on a very small set of observations (documents).

### Movie-Reviews-Pipeline.ipynb

How to use a scikit-learn pipeline to more efficently create, populate, and apply a sentiment prediction model on a larger document collection. 

## Links and Further Reading

These workbooks barely scratch the surface of machine learning or the scikit-learn library. Fortunately, the documentation for scikit-learn is extensive, providing programming guide for using the library as well as discussion on general use, background, theory, and examples. Once you've gotten familiar with the examples provided in this repository, you may find it usefult to work through the scikit-learn documentation.

As an entry point to scikit-leaarn, you may want to read more about the libraries and methods used in this workshop. 

* scikit-learn: https://scikit-learn.org/
* count vectorizer: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
* term frequency: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfTransformer.html
* random forest classifier: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

## Data Citation
This workshop uses data from the Cornell Movie Review dataset
http://www.cs.cornell.edu/people/pabo/movie-review-data/
