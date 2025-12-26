# smartwatch-sentiment-analyzer
Smartwatch Sentiment Analyzer is a Python-based NLP application that analyzes smartwatch reviews and classifies them as positive, neutral, or negative. It combines a traditional TF-IDF + Naive Bayes model with a transformer-based model to understand context, mixed opinions, and provide sentence-level sentiment insights.
#  Smartwatch Sentiment Analyzer

An end-to-end NLP-based web application that analyzes customer smartwatch reviews and classifies them as **Positive**, **Neutral**, or **Negative** using both **Classical Machine Learning** and **Transformer-based Deep Learning models**.

---

##  Features
- Dual-model sentiment prediction:
  - TF-IDF + Naive Bayes (Fast & interpretable)
  - RoBERTa Transformer (Context-aware & accurate)
- Sentence-level sentiment analysis
- Confidence score for predictions
- Flask-based web interface
- Real-time review analysis

---

##  Models Used
### Classical ML
- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Logistic Regression (baseline)
- Random Forest (comparison)

### Transformer
- RoBERTa (Hugging Face Transformers)

---

## Dataset
- Smartwatch & electronics reviews
- Star ratings converted to sentiment:
  - ⭐⭐ (1–2): Negative
  - ⭐⭐⭐ (3): Neutral
  - ⭐⭐⭐⭐–⭐⭐⭐⭐⭐ (4–5): Positive

---

##  Tech Stack
- Python 3.8+
- NLTK
- scikit-learn
- Hugging Face Transformers
- Flask
- Pandas, NumPy

---

##  Installation

```bash
git clone https://github.com/your-username/smartwatch-sentiment-analyzer.git
cd smartwatch-sentiment-analyzer
pip install -r requirements.txt
