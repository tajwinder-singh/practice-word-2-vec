# Word2Vec from Scratch: Building Semantic Understanding with Deep Learning

This project explores **Word2Vec** for text representation and compares it with **TF-IDF**, highlighting how different vectorization techniques capture semantic meaning from text.

---

## •  Objective
To understand how **Word2Vec embeddings** differ from traditional **TF-IDF** in representing textual data and their impact on downstream NLP tasks.

---

## •  Key Steps

1. Installed and configured essential libraries: `gensim`, `nltk`, `spacy`, and `scikit-learn`.
2. Preprocessed text data using tokenization and stopword removal.
3. Trained a **Word2Vec model** using `gensim` to generate word embeddings.
4. Converted sentences to vectors by averaging their word embeddings.
5. Compared model performance against **TF-IDF** representations.

---

## •  Observations

- Word2Vec produced weaker results on small datasets compared to TF-IDF.  
- Averaging word embeddings led to loss of meaning for rare or unique words.  
- Example: “win a free iPhone now” lost its promotional intent due to simple averaging.  
- Word2Vec performs better on **large datasets** where it can capture deeper contextual relationships.

---

## •  Learnings

- **TF-IDF** is more effective on smaller datasets.  
- **Word2Vec** embeddings work best when used with **sequence-based models** like **LSTM, GRU, or Transformers** that preserve word order.  
- Averaging word vectors distorts contextual meaning; advanced sequential models overcome this limitation.  
- Focus of this project was on **understanding representation techniques**, not on optimizing final accuracy.

---

## •  Technologies Used

- Python  
- Gensim  
- NLTK  
- SpaCy  
- Scikit-learn  
- Jupyter Notebook

---

## •  Future Scope

- Integrate Word2Vec embeddings with **LSTM/GRU models** for sequence preservation.  
- Experiment with **contextual embeddings** (BERT, FastText).  
- Apply to real-world text classification and sentiment analysis datasets.

---

## •  Author

**Tajwinder Singh**  
Aspiring Data Scientist | Machine Learning | NLP | Deep Learning  
[LinkedIn](https://www.linkedin.com/in/tajwinder-singh-) • [GitHub](https://github.com/tajwinder-singh)
