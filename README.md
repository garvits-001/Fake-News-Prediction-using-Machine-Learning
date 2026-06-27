# 📰 Fake News Prediction using Machine Learning

A **Machine Learning-based Fake News Detection System** developed using **Python**, **Natural Language Processing (NLP)**, and **Scikit-learn**. The model classifies news articles as **Real** or **Fake** by analyzing their textual content.
The project uses **TF-IDF Vectorization** for text feature extraction and a **Logistic Regression** classifier to identify misinformation with high accuracy.

---

# 📰 Overview

Fake news has become a major challenge in today's digital world. This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to automatically classify news articles as **Real** or **Fake**.

The system processes news text, converts it into numerical features using **TF-IDF Vectorization**, and predicts the authenticity of the news using a trained **Logistic Regression** model.

---

# ✨ Features

* 📰 Detects Fake News
* ✅ Classifies news as Real or Fake
* 🔤 Text preprocessing using NLP
* 📖 Stopword removal and stemming
* 📊 TF-IDF Vectorization
* 🤖 Logistic Regression classifier
* ⚡ Fast and accurate predictions
* 📓 Jupyter Notebook implementation

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Regular Expressions (re)
* TF-IDF Vectorizer
* Logistic Regression
* Jupyter Notebook 
---

# 📊 Dataset

The project uses a labeled news dataset containing:

* News Title
* Author
* News Text
* Label

### Target Labels

| Label | Meaning   |
| ----- | --------- |
| **0** | Real News |
| **1** | Fake News |

---

# 🔤 Text Preprocessing

The following Natural Language Processing (NLP) techniques are applied before training:

* Handling missing values
* Combining **Author** and **Title**
* Converting text to lowercase
* Removing punctuation and special characters
* Removing English stopwords
* Porter Stemming
* TF-IDF Vectorization

---

# 🤖 Machine Learning Model

The project uses the following algorithm:

| Model               | Purpose                  |
| ------------------- | ------------------------ |
| Logistic Regression | Fake News Classification |

The text data is converted into numerical vectors using **TF-IDF Vectorizer**, then classified using **Logistic Regression**.

---

# 🔄 Project Workflow

```text
News Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
      │
      ▼
Stopword Removal
      │
      ▼
Porter Stemming
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Train-Test Split
      │
      ▼
Logistic Regression Model
      │
      ▼
Prediction
```

---

# 📚 Model Training

The notebook includes the following steps:

* Importing required libraries
* Loading the dataset
* Data preprocessing
* Handling missing values
* Text cleaning
* Stemming using Porter Stemmer
* TF-IDF feature extraction
* Train-Test Split
* Logistic Regression model training
* Model evaluation
* Fake news prediction

---

# 📈 Model Evaluation

Evaluation is performed using:

* Training Accuracy
* Testing Accuracy
* Accuracy Score

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.

---

