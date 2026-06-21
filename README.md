# 📩 SMS Spam Detection using Machine Learning

## 🚀 Project Overview

This project focuses on building a Machine Learning model to classify SMS messages as **Spam** or **Ham (Not Spam)**. It uses Natural Language Processing (NLP) techniques and Naive Bayes algorithms to achieve accurate classification.

An interactive **Streamlit web app** is also developed to allow users to test messages in real-time.

---

## 🎯 Objective

* Detect spam messages effectively
* Minimize false positives (important messages marked as spam)
* Improve model performance using feature engineering and tuning

---

## 📂 Dataset

* The dataset consists of labeled SMS messages
* Labels:

  * `0` → Ham (Not Spam)
  * `1` → Spam

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* NLTK (Natural Language Processing)
* Streamlit (for web app)

---

## 🧠 Machine Learning Approach

### 🔹 Data Preprocessing

* Lowercasing text
* Tokenization using NLTK
* Removal of stopwords and punctuation
* Stemming using Porter Stemmer

### 🔹 Feature Extraction

* TF-IDF Vectorization
* Use of n-grams to capture word combinations

### 🔹 Models Used

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

---

## 📊 Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1-score

👉 Special focus was given to **Precision and Recall for Spam detection**

---

## 🔥 Model Improvements

* Removed duplicate data to avoid data leakage
* Tuned **alpha parameter** in MultinomialNB
* Adjusted classification **threshold (0.3)** to improve recall

---

## ✅ Final Model Performance

* High Accuracy (~98%)
* Balanced Precision and Recall
* Improved detection of spam messages

---

## 💻 Streamlit App

### ▶️ Run the app locally:

```bash
streamlit run app.py
```

### 🌐 Features:

* User input for SMS message
* Real-time prediction
* Clean and simple UI

---

## 📁 Project Structure

```
SMS_Spam/
│
├── app.py
├── model_tuned.pkl
├── vectorizer.pkl
├── spam_detection.ipynb
├── requirements.txt
├── README.md
```

---

## ⚠️ Limitations

* May misclassify unseen promotional messages
* Performance depends on dataset vocabulary
* Simple models used (can be improved further)

---

## 🔮 Future Improvements

* Use advanced models (Logistic Regression, Random Forest, Deep Learning)
* Improve feature engineering
* Deploy the app online

---

## 👩‍💻 Author

Pratibha

---

## ⭐ Conclusion

This project demonstrates the complete pipeline of a Machine Learning solution — from data preprocessing and model building to deployment using Streamlit.

---
