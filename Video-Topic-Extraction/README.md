# Video topic extraction

- **Goal:** discover the main topics discussed across TED Talks from their transcripts.
- **Data:** the [TED Talks dataset on Kaggle](https://www.kaggle.com/datasets/rounakbanik/ted-talks) (`transcripts.csv`, not included in the repo — download it next to the notebook).
- **Method:** text cleaning with NLTK and spaCy, bag-of-words corpus with Gensim, LDA topic model tuned with coherence scores, word clouds and pyLDAvis to interpret the topics.

Notebook: [`video-topic-extraction.ipynb`](video-topic-extraction.ipynb)
