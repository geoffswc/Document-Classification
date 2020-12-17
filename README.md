# Scikit-Learn-Workshop

### Short Description

This workshop provides an introduction Python and the scikit-learn module. For a working example, we will train a machine learning model to assess the sentiment (positive or negative) of a movie review. 

This material is designed for programmers, data scientists, and researchers who would like to get started with machine learning for natural language processing and analysis. 

### Long Description

Scikit-learn is a widely used Python based machine learning and natural language processing module. Scikit-learn provides methods for supervised and unsupervised learning, implementations of different machine learning algorithms, and tools for common data preparation tasks involved in machine leaarning programming projects.

This workshop will focus on programming with scikit-learn, rather than the theory behind ML algorithms. The material here is designed for a 2-3 hour workshop and consists of two workbooks. The first workbook introduces machine learning, document categorizaation, and sentiment analysis using a very small dataset. The second workbook applies these techniques to a larger dataset using a scikit-learn pipeline. 

Through these two workbooks, participants will use scikit-learn to:

1. Find the vocabulary used in a collection of documents (a "bag of words")

2. Create a term frequency vector for each document in a collection

3. Scale term frequency vectors to reflect the relevance of certain terms

4. Use term frequency vectors and sentiment scores for each document to train a machine learning model to recognize and assess document sentiment
 
5. Apply a machine learning model to assess the sentiment (or category) of new documents in the collection. 

### Prerequisites

This tutorial is intended for participants who have basic programming experience with Python, including loops, conditionals, and lists. No previous experience with scikit-learn or machine learning is expected. Some familiarity with pandas will help, but we will cover these concepts in the context of populating a scikit-learn model.  

## Workbooks

This tutorial consists of a series of notebooks. Further explanatory text is available in the notebook for each section or the tutorial. 

### Sentiment-Example.ipynb

How to create, populate, and apply a sentiment model on a very small set of observations (documents).

### Movie-Reviews-Pipeline.ipynb

How to use a scikit-learn pipeline to more efficently create, populate, and apply a sentiment prediction model on a larger document collection.

## Links and Further Reading

These workbooks barely scratch the surface of machine learning and scikit-learn. Fortunately, the documentation for scikit-learn is extensive, including a programming guide for using the library, discussion on general use, mathematical background, theory and algorithms, and examples. Once you've gotten familiar with the examples provided in this repository, one good way to get more familiar with machine learning is work through the scikit-learn documentation.

As an entry point to scikit-learn, you may want to read more about the libraries and methods used in this workshop. 

* scikit-learn: https://scikit-learn.org/
* count vectorizer: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html
* term frequency: https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfTransformer.html
* random forest classifier: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

## Data Citation

This workshop uses data from the Cornell Movie Review dataset
http://www.cs.cornell.edu/people/pabo/movie-review-data/

The data used in this workshop has already been processed and prepared for machine learning. The collection of movie review files on the cornell site have been collated into a comma separated file, with special characters and capitalization removed. Although this particular workshop focuses on using scikit-learn, it is worth mentioning how much programming work in ML goes into preparing data (over 90% of the programming effort, by many estimates). If you have extra time for the workshop, it might be worth reviewing the scripting and data munging that goes into preparing a data set.  
