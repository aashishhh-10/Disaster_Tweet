# 🌪️ **Disaster Tweet Classification using NLP**

This project focuses on classifying tweets to detect whether they are about **real disasters** or **not**, using Natural Language Processing techniques and machine learning models.

---

## 🧠 **Objective**

To build a robust text classification pipeline that accurately identifies disaster-related tweets using **CountVectorizer**, **TF-IDF**, and regression-based models.

---

## 📂 **Project Structure**

disaster-tweet-classification/ │ ├── nlp-for-tweets-using-regression-countvec-tfidf.ipynb ├── README.md └── requirements.txt

## 📊 **Dataset**

The dataset is sourced from the [Kaggle: NLP with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/data) competition and includes:

- `text`: The tweet content  
- `target`:  
  - `1` → Tweet refers to a disaster  
  - `0` → Tweet does not refer to a disaster

---

## 🚀 **Features**

- ✅ Text cleaning and preprocessing  
- ✅ Feature extraction using:
  - CountVectorizer  
  - TF-IDF Vectorizer  
- ✅ Classification models:
  - Logistic Regression  
  - Ridge Classifier  
  - Lasso Regression  
- ✅ Model evaluation using:
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report

---

## 📈 **Results**
Comparison between CountVectorizer and TF-IDF for feature extraction

Logistic Regression performed best in classification tasks

Evaluation through confusion matrix and classification report shows promising results

## 🔮 **Future Improvements**
🤖 Integrate transformer models like BERT or RoBERTa

🛠️ Add GridSearchCV for hyperparameter tuning

🌐 Deploy with a frontend for real-time tweet classification




