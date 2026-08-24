sms-spam-classifier/
│
├── data/                # Raw dataset (spam.csv)
├── notebooks/           # Jupyter notebooks (exploration, training)
├── src/                 # Python scripts (preprocessing, model training)
├── models/              # Saved model files (.pkl / .joblib)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

 Objective
The goal of this project is to build a simple, efficient SMS spam detection model using classical NLP techniques such as TF‑IDF vectorization and Naive Bayes classification.

Dataset
Source: SMS Spam Collection Dataset

Format:

label → spam or ham

message → SMS text

Features & Techniques
Text cleaning

Lowercasing

Removing punctuation

Removing stopwords

Lemmatization

Feature extraction

TF‑IDF vectorization

N‑grams

Model

Multinomial Naive Bayes

Evaluation

Accuracy

Precision

Recall

F1-score