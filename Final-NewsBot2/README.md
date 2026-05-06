# ITAI2373-NewsBot2-Final
# 🧠 NewsBot 2.0 — Advanced NLP News Intelligence System

## 📌 Overview
NewsBot 2.0 is a modular Natural Language Processing (NLP) system designed to analyze, interpret, and extract insights from news articles.  
It integrates multiple NLP techniques into a unified pipeline to simulate a real-world intelligent news analysis platform.

This project demonstrates end-to-end system design, implementation, and evaluation of an advanced NLP workflow.

---

## 🚀 Key Features

### 🏷️ Text Classification
- Multi-class news categorization
- Confidence scoring for predictions
- TF-IDF + Logistic Regression baseline model

### 🧭 Topic Modeling
- Automatic discovery of themes and trends
- Topic distribution analysis
- Basic trend tracking capability

### 😊 Sentiment Analysis
- Polarity and subjectivity detection
- Confidence scoring
- Temporal sentiment tracking

### 🔗 Entity Recognition & Relationships
- Named Entity Recognition (NER)
- Extraction of organizations, locations, and key terms
- Basic relationship mapping between entities

### 📝 Text Summarization
- Extractive summarization
- Key information preservation
- Multi-article summary support

### 🔍 Semantic Search
- Content similarity detection
- Article clustering
- Query-based retrieval

### 🌍 Multilingual Processing
- Language detection
- Translation-ready architecture
- Cross-lingual analysis support

### 💬 Conversational Interface
- Intent classification
- Query understanding
- Context-aware responses

### ⚙️ System Integration
- Modular architecture
- End-to-end pipeline orchestration
- Batch processing support

### 📊 Evaluation Framework
- Performance metrics (Accuracy, Precision, Recall, F1)
- Topic coherence evaluation
- Summary quality assessment
- System-level analysis

---

## 🏗️ System Architecture

The system follows a modular, end-to-end NLP pipeline designed to transform raw text into structured insights:

### Processing Pipeline:
```
Input Text
   ↓
Preprocessing
   ↓
Classification → Sentiment → Topics → Entities
   ↓
Summarization → Enhancement → Insights
   ↓
Conversational Interface / Output
```

Each component operates independently but integrates into a unified analysis workflow.

---

## 🧪 Example Output

The system can generate structured insights such as:

- Predicted category with confidence score  
- Sentiment (positive/neutral/negative)  
- Extracted entities (e.g., organizations, locations)  
- Topic distribution  
- Article summary  
- Key insights and patterns  

---

## 📈 Evaluation Summary

- Classification Accuracy: ~85%  
- Precision: ~83%  
- Recall: ~82%  
- F1 Score: ~0.825  

### Strengths:
- Modular architecture
- Integrated NLP pipeline
- Clear and interpretable outputs

### Limitations:
- Relies on traditional ML models (no deep learning yet)
- Topic modeling not fully optimized
- No real-time data integration

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

---

## 📁 Project Structure

ITAI2373-NewsBot2-Final/
│
├── NewsBot2_Student_Guidance_Notebook.ipynb
├── README.md


---

## 🎯 Future Improvements

- Integrate transformer models (BERT, GPT)
- Improve topic coherence tuning
- Add real-time news API integration
- Enhance conversational AI with trained models
- Deploy as a web-based application

---

## 👤 Author

Nichelle Graf
Houston City College — Artificial Intelligence & Robotics Program

---

## 💡 Final Note

This project was designed to simulate a real-world NLP system by combining multiple techniques into a cohesive, production-style architecture. It reflects both technical implementation and system-level thinking.
