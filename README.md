# 📩 Spam Message Detection using Machine Learning [click here to watch the Project video--->https://siam-afroz-tanmoy.github.io/Project-SpamMessageClassifier/

A Machine Learning-based Spam Detection System that classifies messages as **Spam** or **Ham (Not Spam)** using **TF-IDF Vectorization** and **Multinomial Naive Bayes**. The project evaluates multiple datasets individually, merges them into a larger dataset, and analyzes the impact of dataset integration on classification performance.

---

## 🚀 Project Overview

Spam messages are one of the most common problems in digital communication platforms such as SMS and Email. This project aims to automatically identify spam messages using Natural Language Processing (NLP) and Machine Learning techniques.

The system was trained and evaluated on **four different spam datasets**. Individual dataset performance was measured and later compared with a merged dataset containing all samples.

---

## 🎯 Objectives

* Detect spam and ham messages automatically.
* Compare performance across multiple datasets.
* Analyze the effect of merging datasets.
* Build a real-time spam prediction system.
* Evaluate model performance using standard classification metrics.

---

## 📂 Datasets Used

The project utilizes **four different spam datasets** collected from various sources containing SMS and Email spam messages.

### Dataset Summary

| Dataset            |    Samples |   Accuracy |
| ------------------ | ---------: | ---------: |
| Dataset 1          |      5,171 |     92.56% |
| Dataset 2          |      5,572 |     96.86% |
| Dataset 3          |      5,728 |     88.31% |
| Dataset 4          |     10,961 |     89.42% |
| **Merged Dataset** | **27,432** | **93.15%** |

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* Matplotlib
* Joblib

---

## 🧠 Machine Learning Pipeline

### 1. Data Collection

Collected four different spam datasets.

### 2. Data Preprocessing

* Lowercasing
* Removing special characters
* Tokenization
* Stopword Removal
* Stemming

### 3. Feature Extraction

TF-IDF (Term Frequency – Inverse Document Frequency)

### 4. Model Training

Multinomial Naive Bayes Classifier

### 5. Evaluation

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

### 6. Model Saving

The trained model and TF-IDF vectorizer were saved using Joblib.

---

## 📊 Results

### Individual Dataset Performance

| Dataset   | Accuracy |
| --------- | -------: |
| Dataset 1 |   92.56% |
| Dataset 2 |   96.86% |
| Dataset 3 |   88.31% |
| Dataset 4 |   89.42% |

### Merged Dataset Performance

| Metric           |  Value |
| ---------------- | -----: |
| Accuracy         | 93.15% |
| Precision (Spam) |    94% |
| Recall (Spam)    |    89% |
| F1-Score (Spam)  |    91% |

---

## 📈 Confusion Matrix

Merged Dataset Confusion Matrix:

|             | Predicted Ham | Predicted Spam |
| ----------- | ------------: | -------------: |
| Actual Ham  |          4219 |             72 |
| Actual Spam |           131 |           1065 |

---

## 🖥️ Real-Time Prediction

The system supports real-time spam detection by accepting user input messages and classifying them as:

* 🚨 Spam
* ✅ Ham (Not Spam)

Example:

Input:

Congratulations! You have won $1000. Click here to claim your prize.

Output:

🚨 SPAM MESSAGE

---

## 📁 Generated Files

* `final_spam_classifier.pkl`
* `final_tfidf_vectorizer.pkl`
* `confusion_matrix.png`
* `accuracy_comparison.png`

---

## 📌 Key Findings

* Dataset 2 achieved the highest individual accuracy (**96.86%**).
* The merged dataset achieved **93.15%** accuracy.
* Merging datasets increased data diversity and improved model robustness.
* The final model performs well on both SMS and Email spam detection tasks.

---

## 🔮 Future Improvements

* Logistic Regression Comparison
* Support Vector Machine (SVM)
* Random Forest Classifier
* Deep Learning Approaches (LSTM/BERT)
* Web-Based GUI Deployment
* Real-Time Email Filtering

---

## 📚 References

* Scikit-Learn Documentation
* NLTK Documentation
* SMS Spam Collection Dataset
* Public Email Spam Datasets
* Kaggle Spam Detection Datasets

---

## 👨‍💻 Author

* MD. SIAM AFROZ TANMOY
* ID: 0112230123
* UNITED INTERNATIONAL UNIVERSITY
  
⭐ If you found this project useful, consider giving it a star!
