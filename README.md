# Fake-News-Detection

The datasets are stored in the zip file, extraxt them to the main folder.

## Project Summary

In today’s digital world, the rapid spread of misinformation—commonly referred to as *fake news*—poses a serious threat to public awareness, safety, and trust. This project aims to tackle this issue by developing a machine learning-based system capable of classifying news articles as **real** or **fake** using Natural Language Processing (NLP) techniques.

The system uses a labeled dataset of real and fake news articles and applies various preprocessing methods (tokenization, stopword removal, TF-IDF vectorization) to transform raw text into structured data. Supervised machine learning models are then trained on this data to learn the patterns of misinformation.

### Key Features
- Text preprocessing using NLP (tokenization, TF-IDF, stopword removal)
- Binary classification of news articles (Real or Fake)
- Multiple ML algorithms implemented and compared:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Evaluation metrics: Accuracy, Precision, Recall, and F1-Score
- User input system for live prediction of news authenticity

### Objectives
- Understand and analyze the impact of fake news
- Preprocess textual data for model training
- Build and evaluate multiple ML models for classification
- Deploy a predictive system to detect fake news in real time

### Tools & Technologies
- **Programming Language**: Python
- **Libraries**:
  - `scikit-learn` (ML models & metrics)
  - `pandas`, `numpy` (data handling)
  - `nltk` or `spaCy` (NLP preprocessing)
- **Feature Extraction**: TF-IDF Vectorizer
- **Development Environment**: Jupyter Notebook

### Results
All models achieved high performance, with **Gradient Boosting Classifier** delivering the best results:
- Accuracy: 99%
- Precision: 1.00 (Real), 0.99 (Fake)
- Recall: 1.00 (Fake)
- F1-Score: 0.99 (Both classes)

This project demonstrates the effectiveness of combining classical machine learning algorithms with natural language processing for tackling the problem of fake news in a scalable and automated way.

---

