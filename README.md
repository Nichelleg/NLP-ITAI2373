# AI-Portfolio-Nichelle-Graf
Applied AI and Robotics Portfolio - Houston City College
# NLP Course Portfolio — ITAI 2373

**Natural Language Processing | Spring 2026**
Applied Artificial Intelligence & Robotics · Houston City College
Professor Anna Devarakonda

> *Bridging the gap between humans and machine.*

---

## Course Overview

This repository contains all labs, assignments, and projects completed in ITAI 2373 — Natural Language Processing. The course covered the full NLP pipeline from raw text preprocessing through advanced topic modeling and conversational AI, with a production-grade final project as the capstone.

**Tools & Libraries Used:** Python · NLTK · spaCy · VADER · TextBlob · Scikit-Learn · Pandas · Seaborn · Matplotlib · Jupyter · VS Code · Kaggle

---

## Repository Structure

```
NLP-ITAI2373/
├── README.md
│
├── Lab02-Preprocessing/
│   ├── lab02_preprocessing.ipynb
│   ├── README.md
│   └── requirements.txt
│
├── Lab04-Text-Representation/
│   ├── lab04_text_representation.ipynb
│   ├── README.md
│   └── requirements.txt
│
├── Lab05-POS-Tagging/
│   ├── lab05_pos_tagging.ipynb
│   ├── README.md
│   └── requirements.txt
│
├── Lab07-Sentiment-Emotion/
│   ├── lab07_sentiment_emotion.ipynb
│   ├── README.md
│   └── requirements.txt
│
├── Midterm-NewsBot/
│   ├── newsbot_midterm.ipynb
│   ├── README.md
│   ├── requirements.txt
│   └── data/
│
└── Final-NewsBot2/
    ├── newsbot_v2_final.ipynb
    ├── README.md
    ├── requirements.txt
    └── data/
```

---

## Learning Journey

The course was structured as a progressive build — each lab introduced a concept that the next one depended on, culminating in a production-ready NLP system.

| Phase | Lab / Project | Key Concepts |
|-------|--------------|-------------|
| Foundation | Lab 02 — Preprocessing | Tokenization, stemming, lemmatization, stop words, pipeline design |
| Core NLP | Lab 04 — Text Representation | BoW, TF-IDF, N-Grams, word embeddings, semantic similarity |
| Linguistic Analysis | Lab 05 — POS Tagging | Parts-of-speech, dependency parsing, syntactic structure |
| Machine Learning | Lab 07 — Sentiment & Emotion | VADER, TextBlob, emotion classification, multi-dataset analysis |
| Midterm | NewsBot Intelligence System | TF-IDF classification, topic modeling (LDA/NMF), NER, Kaggle |
| Final | NewsBot 2.0 | Transformer embeddings, conversational AI, live news querying |

---

## Featured Projects

### NewsBot Intelligence System (Midterm)

A production NLP pipeline for automated news article categorization. Given a dataset of news articles from Kaggle, the system classifies them into categories using a multi-stage pipeline that combines TF-IDF vectorization, topic modeling, and named entity recognition to produce interpretable, human-readable outputs.

**Approach:**
- Text cleaning and preprocessing pipeline (tokenization, stop word removal, lemmatization)
- TF-IDF vectorization for feature extraction
- LDA and NMF topic modeling for thematic discovery
- Named Entity Recognition (NER) for entity-level analysis
- Multi-class classification with evaluation metrics

**Results:** Multi-class news categorization with interpretable topic outputs and NER-enhanced entity tagging.

**Technologies:** Python · Scikit-Learn · NLTK · spaCy · Pandas · Seaborn · Kaggle

→ [View Notebook](./Midterm-NewsBot/newsbot_midterm.ipynb)

---

### NewsBot 2.0 — Intelligence System Enhancement (Final)

An extension of the NewsBot midterm project incorporating advanced NLP techniques learned in the second half of the course. NewsBot 2.0 moves from classical ML methods toward transformer-based approaches and adds a conversational interface for querying the news corpus directly.

**Enhancements over Midterm:**
- Transformer-based word embeddings replacing TF-IDF as the core representation
- Improved NER pipeline for more precise entity extraction
- Conversational AI interface for natural language news queries
- Live querying capability against the categorized article corpus

**Technologies:** Python · Word Embeddings · NER · Conversational AI · Kaggle

→ [View Notebook](./Final-NewsBot2/newsbot_v2_final.ipynb)

---

## Lab Summaries

### Lab 02 — Basic NLP Preprocessing Techniques

Explored the full preprocessing pipeline and its effect on different text types (simple, academic, social media, news, product reviews). Key comparisons: NLTK vs. spaCy tokenization, stemming vs. lemmatization, and minimal vs. standard vs. aggressive pipeline configurations.

**Core finding:** No universal preprocessing solution exists — the right approach depends entirely on the downstream task. Removing punctuation helps topic modeling but can flip sentiment. Aggressive stemming speeds up search but ruins sentiment accuracy.

→ [View Lab](./Lab02-Preprocessing/lab02_preprocessing.ipynb)

---

### Lab 04 — Text Representation: From Words to Numbers

Implemented Bag of Words, TF-IDF, N-Grams, and word embeddings from scratch before comparing against Scikit-Learn's library implementations. Explored the distributional hypothesis and semantic vector arithmetic.

**Core finding:** The "king − man + woman ≈ queen" relationship in embedding space demonstrates that embeddings encode relational structure, not just similarity — a fundamentally different way of representing meaning than sparse methods.

→ [View Lab](./Lab04-Text-Representation/lab04_text_representation.ipynb)

---

### Lab 05 — Parts-of-Speech Tagging

*See lab PDF for full write-up.*

→ [View Lab](./Lab05-POS-Tagging/lab05_pos_tagging.ipynb)

---

### Lab 07 — Sentiment and Emotion Analysis in the Real World

Comparative analysis of VADER and TextBlob across multiple dataset types. Explored aspect-based sentiment, emotion wheel classification, and the critical edge cases where both libraries fail — sarcasm, negation, and informal spelling.

**Core finding:** VADER outperforms TextBlob on social media and informal text due to its lexicon being specifically trained on that domain. TextBlob performs better on formal prose. Neither handles sarcasm reliably without context.

→ [View Lab](./Lab07-Sentiment-Emotion/lab07_sentiment_emotion.ipynb)

---

## Key Takeaways

1. **Preprocessing decisions are as consequential as model choice.** The same stop word removal that helps topic modeling can reverse the sentiment of a sentence containing "not."

2. **Sparse and dense representations solve different problems.** TF-IDF is interpretable and fast; embeddings capture meaning but require more data and compute.

3. **Ethics is not a footnote.** Bias encoded in training corpora becomes bias encoded in outputs — and in production systems, that has real consequences.

4. **Every pipeline involves trade-offs.** Speed vs. accuracy, information vs. noise, generalization vs. domain specificity. There is no universally correct answer.

---

## Requirements

Each lab and project folder contains its own `requirements.txt`. To install dependencies for a specific notebook:

```bash
pip install -r requirements.txt
```

Common across all labs:

```
nltk
spacy
scikit-learn
pandas
numpy
matplotlib
seaborn
jupyter
```

To download required NLTK data:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
```

To install the spaCy English model:

```bash
python -m spacy download en_core_web_sm
```

---

## About

**Nichelle Graf** — Applied AI & Robotics, Houston City College
**Course:** ITAI 2373 — Natural Language Processing | Spring 2026
**Professor:** Anna Devarakonda

→ [Main Portfolio](https://github.com/Nichelle-Graf/Nichelle-Graf-AI-Portfolio)
