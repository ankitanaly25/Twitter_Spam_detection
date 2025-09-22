# Twitter_Spam_detection
Twitter Spam Detection 🚀

A machine learning project to detect spam vs. non-spam tweets using text preprocessing, feature engineering, and classification models.

📌 Project Overview

The goal of this project is to classify tweets as either spam (bot-generated/irrelevant) or ham (genuine).
This helps improve user experience and maintain platform integrity by filtering unwanted content.

🗂️ Dataset

Source: Twitter dataset (CSV format).

Cleaning steps:

Removed unnecessary columns (Unnamed: 2, Unnamed: 3, Unnamed: 4).

Handled null values.

Preprocessed text (lowercasing, punctuation removal, stopword removal, tokenization).

⚙️ Tech Stack

Programming Language: Python 3

Libraries:

pandas, numpy → Data processing

matplotlib, seaborn → Visualization

nltk → Text preprocessing (stopwords, tokenization)

scikit-learn → ML models (Naive Bayes, Logistic Regression, etc.)

🔑 Features

✔️ Text cleaning & preprocessing (punctuation removal, tokenization, stopword removal)
✔️ Bag-of-Words feature extraction
✔️ Training multiple classification models
✔️ Model evaluation with accuracy and confusion matrix

🏗️ Methodology

Data Preprocessing

Removed null/irrelevant columns

Tokenized text using NLTK

Removed stopwords & punctuation

Feature Engineering

Converted text into numerical vectors (Bag-of-Words, CountVectorizer)

Model Training

Naive Bayes Classifier

Logistic Regression

(Other models depending on your notebook)

Evaluation

Accuracy Score

Confusion Matrix & Classification Report

📊 Results

Achieved strong performance in distinguishing spam vs. non-spam tweets.

Best performing model: (fill in after checking results – e.g., Naive Bayes with 96% accuracy)

🚀 How to Run

Clone the repo:

git clone https://github.com/your-username/twitter-spam-detection.git
cd twitter-spam-detection


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook "Twitter spam detection.ipynb"

📌 Future Scope

Apply advanced models (LSTMs, Transformers) for better accuracy.

Deploy as a web app using Flask/Streamlit.

Integrate real-time Twitter API for live spam detection.

