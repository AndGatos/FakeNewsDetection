# FakeNewsDetection
Machine Learning Course --- 2nd Assignment

## Google Colab notebooks

The notebooks in the directories "stemming" and "lemmatization" are used in the beginning. 

It is in these notebooks where the appropriate text preprocessing is implemented (nltk for stemming, spacy for lemmatization).

The gensim models are also trained in order to produce the necessary word vectors (Gensim was used).

The CSV files (for headlines and article bodies) and gensim models are then stored in their respsective directories .

Finally, the CSV files and gensim models are loaded into the notebooks "stem_mlp.ipynb" and "lemma_mlp.ipynb" in order to train the Multilayer Perceptron either with the "Average Word2Vec" method or the "TFIDF-Average Word2Vec" method.
