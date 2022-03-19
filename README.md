# FakeNewsDetection
Machine Learning Course --- 2nd Assignment

## Google Colab notebooks

There are notebooks in the directories "stemming" and "lemmatization" where the appropriate text preprocessing has already been implemented.
The gensim models have also been trained in order to produce the necessary word vectors.

The CSV files and gensim models are then stored in their respsective directories (for headlines and article bodies).

Finally, the CSV files and gensim models are loaded into the notebooks "stem_mlp.ipynb" and "lemma_mlp.ipynb" in order to train the Multilayer Perceptron either with the Average Word2Vec method or TFIDF Average Word2Vec method.
