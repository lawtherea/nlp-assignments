# Natural Language Processing - Exercise Lists

Solved exercise lists for the **Natural Language Processing** course taught by **Professor Thales Vieira** at the **Institute of Computing (Instituto de Computação)**, **Federal University of Alagoas (UFAL)**.

## Students

- Leila Maria Biggi de Souza Cavalcante
- Maria Antonia Ribeiro Ramos

## Contents

| Notebook | Description |
|---|---|
| [`assignment1.ipynb`](assignment1.ipynb) | Assignment 1: regular expressions, corpus analysis, preprocessing, bag-of-words, POS tagging, and stemming |
| [`assignment2.ipynb`](assignment2.ipynb) | Assignment 2: document similarity (CountVectorizer and TF-IDF with cosine), text classification, and topic modeling (NMF and BERTopic) |

The notebooks use the **BBC News Archive** as the English text corpus. The Python stack is Jupyter, NumPy, pandas, NLTK, spaCy, scikit-learn, matplotlib, and BERTopic.

## Dataset

[BBC News Archive](https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive/) on Kaggle (`hgultekin/bbcnewsarchive`).

## How to run

Open the notebook, select the project environment, and run the **Installation and imports** section once. That cell installs the required packages and downloads the spaCy English model. Then run the exercises in order. Assignment 2 reuses the preprocessing from Assignment 1 (tokenize, drop digits, lowercase, strip punctuation, remove English stopwords, and Porter stemming).
