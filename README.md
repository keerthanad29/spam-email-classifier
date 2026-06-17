<div align="center">

# 📧 Spam Email Classifier

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![NLP](https://img.shields.io/badge/NLP-Text%20Classification-9C27B0?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.nltk.org)

> **Is this email spam or not? Let the machine decide.**
> End-to-end NLP pipeline using TF-IDF and Multinomial Naive Bayes to detect spam with real-time prediction.

</div>

---

## 📌 Problem Statement

Spam emails are a major threat — cluttering inboxes, spreading phishing attacks, and causing financial fraud. This project builds an intelligent **Spam Email Classifier** that automatically detects whether a message is **Spam or Ham (Not Spam)** using NLP text preprocessing and a Naive Bayes classifier.

---

## 🎯 Project Highlights

| What | Detail |
|------|--------|
| 🧠 Algorithm | Multinomial Naive Bayes |
| 🔤 Vectorizer | TF-IDF Vectorization |
| 📦 Dataset | SMS/Email Spam Collection Dataset |
| 🎯 Target | Spam / Ham (Binary Classification) |
| ⚡ Feature | Real-time custom message prediction |

---

## 🗂️ Project Structure

```
spam-email-classifier/
│
├── spam_email_classifier.ipynb   # Jupyter Notebook — full NLP pipeline
├── Email Prediction Examples     # Sample prediction outputs
├── requirements.txt              # Dependencies
├── images/                       # Visualization outputs
└── README.md
```

---

## 🔄 NLP Pipeline

```
Raw Text  →  Preprocessing  →  TF-IDF  →  Naive Bayes  →  Evaluation  →  Live Prediction
```

1. **Load Data** — SMS/Email Spam Collection Dataset
2. **Text Preprocessing** — Remove punctuation, stopwords, special characters, tokenize
3. **TF-IDF Vectorization** — Convert text to numerical features
4. **Train/Test Split** — Split for unbiased evaluation
5. **Train Model** — Multinomial Naive Bayes classifier
6. **Evaluate** — Accuracy, Precision, Recall, F1-Score + Confusion Matrix
7. **Live Prediction** — Input any message → instant Spam/Ham output

---

## 📬 Sample Predictions

| Message | Prediction |
|---------|------------|
| "Congratulations! You won a $500 prize! Click here to claim." | 🔴 Spam |
| "Hello, the report for tomorrow's meeting is attached." | 🟢 Ham |
| "Your bank account is at risk. Confirm your identity immediately." | 🔴 Spam |
| "Your order has been shipped and will arrive tomorrow." | 🟢 Ham |

---

## 📊 Confusion Matrix

> Confusion matrix heatmap available in the `images/` folder and rendered inside the notebook.

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/keerthanad29/spam-email-classifier.git
cd spam-email-classifier

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Jupyter Notebook
jupyter notebook spam_email_classifier.ipynb
```

> Or open directly in **Google Colab** — no setup needed!

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
nltk
matplotlib
seaborn
```

---

## 💡 What I Learned

- Building an end-to-end **NLP text classification** pipeline
- **TF-IDF vectorization** — why it outperforms simple CountVectorizer for spam detection
- Why **Multinomial Naive Bayes** is the go-to algorithm for text classification
- Importance of **precision vs recall** tradeoff in spam detection
- Implementing **real-time prediction** for unseen messages

---

## 🔮 Future Improvements

- [ ] Try LSTM / BERT for improved accuracy
- [ ] Build a real-time web app using Streamlit
- [ ] Add email header analysis for better spam detection
- [ ] Expand dataset to multi-language spam detection
