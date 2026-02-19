
# AIG 230 – Lab 05  
## Sequence Models with PyTorch: Learning from Ordered Text

### Overview
An NLP pipeline that shows how to process and analyze raw text. Using Jane Austen's Emma from the NLTK library as the dataset, the project demonstrates how to take messy, unstructured text and turn it into formats that machine learning models can understand. It covers the essential steps of text analysis, from basic cleaning to training models that can generate text and find relationships between words.

The project is broken down into three main parts. First, the text is cleaned and standardized by splitting it into words, removing punctuation and common words (stopwords), and reducing words to their base forms (lemmatization). Next, the text is converted into numbers using Bag-of-Words and TF-IDF to compare different sections of the book and find out which parts are the most similar. Finally, the pipeline trains two types of models: a statistical language model that can generate new sentences in the style of the book, and a Word2Vec model that learns the underlying meanings and analogies behind the vocabulary.

---

### Tools and Libraries

Working with:

- **Python** for building the pipeline  
- **NLTK** for accessing the Gutenberg corpus, tokenization and basic preprocessing
- **Gensim**  to to train and evaluate Word2Vec embeddings.
- **NumPy / Pandas** for data handling  
- **Scikit Learn** for building sparse vector representations (CountVectorizer and TfidfVectorizer) and calculating cosine similarity between text documents
- **Jupyter Notebook** for interactive experimentation  

---

### Submission File

- `nlp_assignment5.ipynb`  

---
