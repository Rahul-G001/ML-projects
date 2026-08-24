# 📦 SMS Spam Classifier

A machine learning project that classifies SMS messages as **spam** or **ham** using classical NLP preprocessing and a Multinomial Naive Bayes model.

---

## 📁 Project Structure

sms-spam-classifier/
│
├── data/                # Raw dataset (spam.csv)
├── notebooks/           # Jupyter notebooks (exploration, training)
├── src/                 # Python scripts (preprocessing, model training)
├── models/              # Saved model files (.pkl / .joblib)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation


---

## 🎯 Objective

The goal of this project is to build a simple, efficient SMS spam detection model using classical NLP techniques such as **TF‑IDF vectorization** and **Naive Bayes classification**.

---

## 📊 Dataset

**Source:** SMS Spam Collection Dataset  
**Format:**
- `label` → spam or ham  
- `message` → SMS text  

---

## 🔧 Features & Techniques

### 🧹 Text Cleaning
- Lowercasing  
- Removing punctuation  
- Removing stopwords  
- Lemmatization  

### 🔠 Feature Extraction
- TF‑IDF vectorization  
- N‑grams  

### 🤖 Model
- Multinomial Naive Bayes  

### 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone <your-private-repo-link>
cd sms-spam-classifier   

