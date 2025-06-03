# 🎬 Sentiment Analysis on IMDb Movie Reviews

## 📌 Project Overview

This project focuses on classifying IMDb movie reviews as **positive** or **negative** using **text mining** and **machine learning** techniques.

The primary goal is to automate the sentiment analysis process of user-generated content, making review evaluation faster, more scalable, and less dependent on human effort.

---

## 🧠 Methods Used

- **Data Cleaning**: Lowercasing, punctuation removal, stopword removal, lemmatization
- **Text Vectorization**: TF-IDF (Term Frequency - Inverse Document Frequency)
- **Machine Learning**: Logistic Regression (best performing model after comparison)
- **Model Evaluation**: Confusion Matrix, Classification Report, Accuracy, WordClouds
- **Visualization**: Matplotlib, Seaborn

---

## 📊 Dataset

- **Source**: IMDb movie reviews dataset
- **Size**: ~50,000 reviews
- **Class Balance**: The dataset was balanced with approximately 50% positive and 50% negative reviews.

---

## ⚙️ How to Run

1. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

2. Open and run the notebook file `main.ipynb` step by step.

---

## 📈 Results

- **Accuracy**: 88%
- **Precision (Positive)**: 0.87
- **Recall (Positive)**: 0.88
- **F1-Score**: 0.87
- **Confusion Matrix**: The model made fewer false negatives compared to false positives.

The WordCloud visualizations revealed which words were most frequently associated with each sentiment class.

Additionally, we analyzed examples of incorrect predictions (e.g., sarcasm, ambiguous wording).

---

## 🔍 Sample Visualizations

- Sentiment Distribution in Test Data
- Confusion Matrix
- Classification Report Table
- WordClouds (Positive/Negative)
- Examples of Misclassified Comments

