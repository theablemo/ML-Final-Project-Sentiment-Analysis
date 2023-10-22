Sentiment Analysis using different classification methods
========

This is the final project for the Machine Learning course. In this project, I run sentiment analysis on [this dataset](data-train.csv) using different classification methods.
First, I will talk about the data preprocessing and word vectorization methods, and then I will talk about the classification methods that I used.

The project notebook can be found [here](98103867-ml-project.ipynb). Documentation is available [here](<98103867-ML Project Report.pdf>).

Results are available in the notebook and the documentation.

# Data preprocessing 

The following preprocessing tasks are done on the data:

- **Low casing words**
- **Delete additional spaces**
- **Remove stopwords**
- **Remove punctuation marks**
- **Word Lemmatization**: Using the `nltk` library
- **Word Tokenization**

After that, I leveraged the undersampling method to balance classes.

# Word embedding

I used the following methods to embed words:

1. **TFIDF Vectorization**: Using the `sklearn` library
2. **CBOW**
3. **Skip-Gram**

# Classification methods

The following classification methods are used:

- Logistic Regression
- Gaussian Naive Bayes
- Random Forest
- Adaboost
- Support Vector Machine (SVM)
- Neural Net (MLP)
