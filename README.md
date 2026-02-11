# Customer Support Ticket Cleaning & Annotation System

## 📌 Project Overview
This project builds a complete NLP preprocessing pipeline to clean, process, and annotate customer support tickets for machine learning tasks.

## 🚀 Features
- Text Cleaning
- Spell Correction
- Tokenization
- Stopword Removal
- Lemmatization
- Named Entity Recognition (NER)
- Ticket Category Labeling

## 🛠 Tech Stack
Python, spaCy, NLTK, TextBlob, Pandas

## 📂 Dataset
support_tickets.csv contains raw customer complaints.

## ▶️ How to Run

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
python ticket_preprocessing.py
