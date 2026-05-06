# 📰 NewsBot Intelligence System
An end-to-end NLP pipeline for news classification, sentiment analysis, and named entity recognition.

## 📌 Project Overview
This project implements a complete NLP pipeline for analyzing news articles. It integrates text classification, sentiment analysis, and named entity recognition to generate actionable insights from unstructured text data.

---

## ⚙️ Features
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Multi-model classification (Naive Bayes, Logistic Regression, SVM)
- Sentiment analysis using VADER
- Named Entity Recognition (spaCy)
- Comprehensive analytics and insights
- End-to-end NewsBot processing pipeline

---

## 🧠 System Pipeline
1. Text Preprocessing  
2. Feature Extraction (TF-IDF)  
3. Classification (Category Prediction)  
4. Entity Extraction (NER)  
5. Sentiment Analysis  
6. Insight Generation  

---

## 📊 Key Results
- Best Model: Naive Bayes  
- Accuracy: ~56%  
- Strong performance in clearly defined categories (e.g., Sports)  
- Challenges with overlapping categories (e.g., Tech vs Business)

---

## 💡 Insights
- TF-IDF alone struggles with contextual meaning  
- Entity extraction reveals strong patterns across categories  
- Sentiment varies significantly by news type  
- Additional features (POS, syntax) could improve performance  

---

## 🚀 How to Run
1. Open the notebook in Google Colab or VS Code  
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn spacy nltk
   python -m spacy download en_core_web_sm
