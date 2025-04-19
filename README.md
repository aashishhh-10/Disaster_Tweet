
🌪️ Disaster Tweet Classification using NLP
This project focuses on building a Natural Language Processing (NLP) pipeline to classify tweets as disaster-related or not. It leverages machine learning techniques including CountVectorizer, TF-IDF, and regression models to perform binary classification.

🧠 Objective
To detect whether a given tweet refers to a real disaster or not, by preprocessing text data and training ML models using various feature extraction methods.

📁 Project Structure
cpp
Copy
Edit
disaster-tweet-classification/
│
├── nlp-for-tweets-using-regression-countvec-tfidf.ipynb
├── README.md
└── requirements.txt
📊 Dataset
The dataset consists of tweets labeled with:

text: the tweet content

target: 1 if the tweet refers to a real disaster, 0 otherwise

You can download the dataset from Kaggle: Real or Not? NLP with Disaster Tweets.

🚀 Features
Text preprocessing: cleaning, tokenizing, stopword removal, and vectorization

Feature extraction methods:

CountVectorizer

TF-IDF Vectorizer

Machine Learning models:

Logistic Regression

Ridge Classifier

Lasso Regression (used for classification-like behavior)

Model evaluation using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

📦 Dependencies
Python

pandas

numpy

scikit-learn

matplotlib

seaborn

Install all required packages using:

bash
Copy
Edit
pip install -r requirements.txt
🛠️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/disaster-tweet-classification.git
cd disaster-tweet-classification
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook nlp-for-tweets-using-regression-countvec-tfidf.ipynb
Make sure the dataset CSV file is in the working directory or update the path inside the notebook accordingly.

✅ Results
TF-IDF and CountVectorizer are compared for feature extraction.

Logistic Regression yielded good accuracy on disaster classification.

Visual insights are provided through confusion matrices and classification reports.

🔮 Future Improvements
Use more advanced NLP models (e.g., BERT, RoBERTa)

Perform hyperparameter tuning using GridSearchCV

Add a user interface for tweet classification
