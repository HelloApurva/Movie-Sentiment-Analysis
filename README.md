# 🎬 Movie Sentiment Analysis Using NLP & Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Sentiment%20Analysis-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-red?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-yellow?style=for-the-badge&logo=jupyter" />
</p>

---

## 📌 Project Overview

This project focuses on **Movie Review Sentiment Analysis** using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The main objective of this project is to classify movie reviews as **positive** or **negative** based on textual content.

The project demonstrates the complete NLP pipeline including:
- Text preprocessing
- Data cleaning
- Feature extraction
- Machine learning model training
- Performance evaluation
- Accuracy comparison

Multiple machine learning algorithms were implemented and compared to identify the most effective model for sentiment classification.

---

# 🧠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Computation |
| NLTK | NLP Preprocessing |
| TextBlob | Text Processing |
| Scikit-learn | Machine Learning Models |
| XGBoost | Boosting Algorithm |
| Matplotlib & Seaborn | Data Visualization |
| Jupyter Notebook | Project Development |

---

# 📂 Dataset Information

- **Dataset:** IMDb Movie Reviews Dataset
- **Total Reviews:** 50,000
- **Columns:**
  - `review`
  - `sentiment`

- **Sentiment Classes:**
  - Positive
  - Negative

### Dataset Characteristics
- No missing values
- 418 duplicate records removed
- Balanced dataset distribution

---

# ⚙️ NLP Preprocessing Techniques

The following preprocessing techniques were applied to clean and standardize the movie review text:

✅ Lowercasing using `str.lower()`  
✅ HTML Tag Removal using Regex  
✅ URL Removal  
✅ Punctuation Removal  
✅ Chat Word & Slang Conversion  
✅ Emoji Conversion  
✅ Stopword Removal  
✅ Tokenization  
✅ Stemming using PorterStemmer  
✅ Extra Space Removal  
✅ TF-IDF Vectorization  

---

# 🤖 Machine Learning Algorithms Used

## Supervised Learning Models
- Logistic Regression
- Multinomial Naive Bayes
- Decision Tree Classifier
- Random Forest Classifier
- Linear Support Vector Classifier (Linear SVC)
- XGBoost Classifier

---

# 📊 Accuracy Comparison

| Algorithm | Accuracy |
|---|---|
| Logistic Regression | 89.50% |
| Linear SVC | 88.37% |
| Multinomial Naive Bayes | 86.51% |
| XGBoost | 84.66% |
| Random Forest | 84.51% |
| Decision Tree | 72.66% |

---

# 🏆 Best Performing Model

✅ **Logistic Regression** achieved the highest accuracy of **89.50%**, making it the best-performing model for movie review sentiment classification.

---

# 📈 Model Evaluation Techniques

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Accuracy Comparison Graphs

---

# 📁 Project Files Included

| File Name | Description |
|---|---|
| `Movie_Sentiment_Analysis.ipynb` | Complete Jupyter Notebook |
| `Movie Sentiment Review NLP Report File.pdf` | Detailed Project Report |
| `README.md` | Project Documentation |

---

# 🚀 Future Scope

This project can be further improved by implementing:

- Deep Learning Models (LSTM, RNN)
- Transformer-based Models (BERT)
- Multilingual Sentiment Analysis
- Real-time Sentiment Prediction
- Sarcasm Detection
- Web App Deployment using Streamlit

---

# 👩‍💻 Author

## Apoorva Sharma

🎓 B.Sc. (Hons.) Mathematics  
📍 New Delhi, India  
💡 Interested in Data Science, NLP, AI & Machine Learning

---

# 🎬 Final Review

> “Critics rated this project: Positive Sentiment ✔️”

🍿 *Written & Directed by Apoorva Sharma*
