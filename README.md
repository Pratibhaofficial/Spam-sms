# 📩 SMS Spam Detection using Machine Learning

## 🚀 Project Overview

This project focuses on building a Machine Learning model to classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

An interactive **Streamlit web app** is also developed to allow users to test messages in real-time.

---

## 🎯 Objective

* Detect spam messages effectively
* Reduce misclassification of important messages
* Improve model performance using preprocessing and tuning

---

## 📂 Dataset

* Labeled SMS dataset
* Labels:

  * `0` → Ham (Not Spam)
  * `1` → Spam

---

## ⚙️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* NLTK
* Streamlit

---

## 🧠 Machine Learning Approach

### 🔹 Data Preprocessing

* Lowercasing text
* Tokenization using NLTK
* Removal of stopwords and punctuation
* Stemming using Porter Stemmer

### 🔹 Feature Extraction

* TF-IDF Vectorization
* Use of n-grams (unigrams + bigrams)

---

## 🤖 Models Used

* Gaussian Naive Bayes
* Multinomial Naive Bayes
* Bernoulli Naive Bayes

👉 **Multinomial Naive Bayes** performed the best and was selected as the final model.

---

## 📊 Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1-score

👉 Focus was given to **precision and recall for spam detection**

---

## 🔥 Model Improvements

* Removed duplicate messages to avoid data leakage
* Tuned **alpha parameter** in MultinomialNB
* Adjusted classification **threshold (0.3)** to improve recall

---

## ✅ Final Model Performance

* Accuracy: ~98%
* High precision and improved recall for spam
* Balanced performance using threshold tuning

---

## 💻 Streamlit App

### ▶️ Run locally:

```bash id="7g4gcv"
streamlit run app.py
```

### 🌐 Features:

* Input SMS message
* Real-time prediction (Spam / Not Spam)
* Simple UI

---

## 📁 Project Structure

```id="y8csq1"
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

* May miss spam messages with unseen vocabulary
* Depends on dataset quality
* Uses simple models (scope for improvement)

---

## 🔮 Future Improvements

* Try advanced models (Logistic Regression, Random Forest, Deep Learning)
* Improve feature engineering
* Deploy app online

---

## 👩‍💻 Author

Pratibha

---

## ⭐ Conclusion

This project demonstrates a complete machine learning workflow — from preprocessing and model building to evaluation and deployment using Streamlit.

---
