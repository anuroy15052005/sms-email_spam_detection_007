# 📧 Spam Detection App

A Machine Learning web app that classifies messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) and a Naive Bayes classifier.

---

## 🚀 Live Demo

Run locally using Streamlit (see instructions below).

---

## 📁 Project Structure

```
spam-detection/
├── app.py              ←  Streamlit web app
├── model.pkl           ←  trained Naive Bayes model
├── vectorizer.pkl      ←  TF-IDF vectorizer
├── requirements.txt    ←  required libraries
└── README.md           ←  project documentation
```

---

## 🧠 How It Works

```
User inputs message
        ↓
Text Preprocessing (lowercase, remove punctuation, stopwords)
        ↓
TF-IDF Vectorization (vectorizer.pkl)
        ↓
Naive Bayes Prediction (model.pkl)
        ↓
Output: Spam or Not Spam
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Scikit-learn | TF-IDF Vectorizer + Naive Bayes model |
| NLTK | Text preprocessing + stopwords |
| Streamlit | Web app frontend |
| Pickle | Model persistence |

---

## ⚙️ Installation & Setup

**1. Clone the repository:**
```bash
git clone https://github.com/yourusername/sms-email_spam_detection_007
cd sms-email_spam_detection_007
```

**2. Install dependencies:**
```bash
pip install -r requirements.txt
```

**3. Download NLTK stopwords (automatic on first run):**
```python
import nltk
nltk.download('stopwords')
```

**4. Run the app:**
```bash
streamlit run app.py
```

---

## 📦 Requirements

```
streamlit
scikit-learn
nltk
numpy
pandas
joblib
```

---

## 📊 Model Details

| Component | Detail |
|---|---|
| Algorithm | Multinomial Naive Bayes |
| Vectorizer | TF-IDF (Term Frequency-Inverse Document Frequency) |
| Preprocessing | Lowercase, punctuation removal, stopword removal |
| Persistence | Pickle (.pkl) |

---

## 👨‍💻 Author

**Anu**
- 🎓 Computer Science Undergraduate
- 📍 Noida, India
- 🔗 [GitHub](https://github.com/anuroy15052005)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).