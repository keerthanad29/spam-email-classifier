# Spam Email Classifier 📧
> NLP-based classifier that detects spam emails with 97.13% accuracy using Multinomial Naive Bayes.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-009900?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 📌 Objective
Automatically classify emails and SMS messages as Spam or Ham using NLP preprocessing and probabilistic ML.

## 📊 Dataset
- 5,572 messages | Binary classification (Spam / Ham)
- Source: SMS Spam Collection Dataset

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| ✅ Accuracy | 97.13% |
| 🎯 Precision | 85.11% |
| 🔁 Recall | 95.33% |
| 📈 F1 Score | 89.94% |

## 🛠 Tech Stack
- Python | Pandas | NumPy
- Scikit-learn | NLTK
- Matplotlib | Seaborn

## 🔍 Methodology
1. Load & explore SMS Spam Collection dataset
2. Clean text — lowercase, remove punctuation, stopwords
3. Convert text to vectors using **TF-IDF Vectorizer** (bigrams)
4. Train **Multinomial Naive Bayes** classifier
5. Evaluate using Accuracy, Precision, Recall, F1-Score
6. Predict new messages in real time

## 📉 Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

## 🧪 Sample Predictions

| Message | Prediction |
|---------|-----------|
| "Congratulations! You've won a free lottery. Claim now." | 🔴 Spam |
| "Are you coming to office today?" | 🟢 Ham |
| "Free vacation offer only for you!" | 🔴 Spam |

## ▶️ How to Run
```bash
pip install -r requirements.txt
```
Open `Spam_Email_Classifier.ipynb` in Jupyter or Google Colab.

> 📌 Dataset: Download from [Kaggle - SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) and place as `spam.csv`

## 👩‍💻 Author
**Keerthana Dharmaraj** — [GitHub](https://github.com/keerthanad29)
