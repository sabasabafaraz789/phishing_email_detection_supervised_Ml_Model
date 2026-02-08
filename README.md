#  Phishing Email Detection using Supervised Machine Learning

##  Project Overview

This project focuses on building a **Supervised Machine Learning model** to automatically classify emails as:

* ✅ Legitimate (Safe)
* ⚠️ Phishing (Malicious)

The goal is to help improve email security by detecting phishing attempts efficiently.


---

##  Workflow Pipeline

###  Step 1: Data Loading

* Phishing email dataset [Phishing Email Dataset](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset)

###  Step 2: Data Cleaning & Preprocessing

* Remove special characters, punctuation
* Convert text into lowercase
* Remove stopwords
* Tokenization

###  Step 3: Feature Extraction

To convert text into numerical format:

* **TF-IDF Vectorization**
* Bag of Words (CountVectorizer)

---

###  Step 4: Model Training

Train multiple supervised classifiers such as:

* Logistic Regression
* Naive Bayes
* Random Forest
* Support Vector Machine

---

###  Step 5: Model Evaluation

Performance is evaluated using:

* Accuracy Score:  1.00
* Precision: 1.00
* Recall: 1.00
* F1-Score:  1.00
* Confusion Matrix:
[[3453    9]
 [0   4369]]
---

###  Step 6: Real Email Prediction

The pipeline supports prediction on real-world email text:

* Input: Email content
* Output: Phishing or Legitimate

---

##  Results

The trained model successfully detects phishing emails with strong accuracy and classification performance.

---

## 👨‍💻 Author
Developed by **Saba Faraz**  
📧 Email: farazsaba96@gmail.com

---
