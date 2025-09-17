**Twitter Sentiment Analysis **

This project demonstrates how to build a Twitter Sentiment Analysis Model using Python and Machine Learning.
The purpose is to analyze public sentiments towards the Pfizer COVID-19 vaccine based on tweets. The analysis classifies tweets into three categories:

✅ Positive

⚠️ Neutral

❌ Negative

We use a publicly available dataset from Kaggle containing Pfizer-related tweets. The project applies various machine learning classifiers to identify the most accurate model for sentiment classification.

🔍 Features

Data preprocessing: text cleaning, stopwords removal, tokenization, stemming.

Sentiment polarity computation using TextBlob.

Visualization of sentiment distribution and word clouds.

Feature extraction with CountVectorizer (n-grams).

Model training and evaluation using:

Logistic Regression

Support Vector Machine (SVM)

Hyperparameter tuning with GridSearchCV.

Confusion matrix and classification report generation for performance evaluation.

📂 Dataset

File: vaccination_tweets.csv

Contains raw tweets related to the Pfizer vaccine.

Fields include tweet text, user metadata, retweets, etc.

Preprocessing focuses only on the text column and sentiment analysis.

⚙️ Installation & Running the Project

Clone the repository:

git clone https://github.com/your-username/twitter-sentiment-pfizer.git
cd twitter-sentiment-pfizer


Install dependencies:

pip install -r requirements.txt


Download the dataset from Kaggle and place it in the data/ folder with filename:

vaccination_tweets.csv


Run the notebook or Python script:

jupyter notebook Twitter sentiment analysis_live.ipynb


OR

python Twitter\ sentiment\ analysis_live.py

📊 Sample Results

Sentiment distribution visualization

Word clouds for positive, negative, and neutral sentiments

Model accuracy for Logistic Regression and SVM classifiers

Best hyperparameters found via GridSearchCV

Final model performance report

🔮 Future Work

Real-time data extraction using Twitter API.

Integration of Deep Learning models (LSTM, Transformers).

Interactive dashboard for live sentiment tracking.

🎥 Video Explanation

Watch the detailed video walkthrough of the project:
Watch Video on YouTube

📜 License

This project is licensed under the MIT License.
