# alzheimers-symptom-nlp
SYSEN5630-NLP project for detecting Alzheimer's-related symptoms from PubMed abstracts

# Alzheimer's Symptom Detection from PubMed Abstracts

This project applies natural language processing (NLP) techniques to identify mentions of Alzheimer's-related symptoms (such as memory loss, confusion, and cognitive decline) in biomedical literature, specifically PubMed abstracts. The goal is to explore how transformer-based models can be used to assist in early symptom recognition by automatically classifying scientific abstracts based on symptom relevance.

## 📊 Task Description

- **Input**: Abstracts from PubMed related to Alzheimer's disease.
- **Output**: Binary classification — does the abstract mention symptoms (`1`) or not (`0`)?
- **Approach**: We use both traditional machine learning (TF-IDF + Logistic Regression) and transformer-based models (DistilBERT) for classification.

## 🧠 Models Used

- ✅ `TF-IDF + Logistic Regression` (baseline)
- ✅ `DistilBERT` fine-tuned using HuggingFace's `Trainer`
- ✅ Symptom keyword detection using `spaCy` + `EntityRuler`

## 📁 Project Structure

