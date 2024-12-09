# NLP-Topic-Modelling-LDA-and-NMF
#**NLP Topic Modeling with LDA, NMF, and NLP LDA with sklearn**

**This project demonstrates topic modeling using three popular techniques in Natural Language Processing (NLP): Latent Dirichlet Allocation (LDA), Non-Negative Matrix Factorization (NMF), and NLP LDA with scikit-learn. The goal is to extract meaningful topics from a given corpus of text.**

**Techniques Used**

**1. Latent Dirichlet Allocation (LDA)**

  -LDA is a generative probabilistic model used to identify topics in a collection of text documents.

  -It assumes each document is a mixture of topics, and each word is attributable to one of the document's topics.

**2. Non-Negative Matrix Factorization (NMF)**

  -NMF is a matrix factorization technique that decomposes the term-document matrix into two lower-dimensional matrices.
  
  -Unlike LDA, NMF is not probabilistic, but it is often used for topic modeling when interpretability is important.

**3. NLP LDA with scikit-learn**

  -NLP LDA uses the LDA algorithm from scikit-learn to perform topic modeling, enabling easy integration with the CountVectorizer and         TfidfVectorizer from scikit-learn.
  
  -This method works efficiently on text data preprocessed with techniques such as tokenization, stopword removal, and lemmatization.

**Features**

**Data Preprocessing:**

  -Includes text cleaning, tokenization, stopword removal, and lemmatization to prepare the text for modeling.
  
  -Visualization: Displays the topics with their top words using WordCloud or pyLDAvis for LDA models.
  
  -Model Evaluation: Evaluation of models using metrics such as perplexity and topic coherence.
  
  -Customizable: Allows adjusting the number of topics and other hyperparameters for each model.

