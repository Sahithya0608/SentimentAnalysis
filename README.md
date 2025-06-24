Sentiment Analysis on Twitter Dataset
Overview
This project analyzes 1.6 million tweets to classify them as positive or negative using Natural Language Processing (NLP) and Logistic Regression.

Features
Preprocessing: Cleans tweet text (removal of special chars, lowercasing, stemming).

Vectorization: Converts text to numerical form using TF-IDF.

Modeling: Trains a Logistic Regression classifier.

Evaluation: Achieves ~79.87% training and ~77.67% test accuracy.

Prediction: Supports sentiment prediction on new tweets.

Dataset
Source: Kaggle - Sentiment140

Format: CSV with tweet ID, date, user, and sentiment (0 = negative, 4 = positive → mapped to 1).

Requirements
bash
Copy
Edit
pip install pandas numpy nltk scikit-learn
Usage
Download the dataset:

bash
Copy
Edit
kaggle datasets download -d kazanova/sentiment140
Run Sentiment_Analysis.ipynb to train and test the model.

Use the saved model (trained_model.sav) to predict sentiment on new data.

Files
Sentiment_Analysis.ipynb: Code notebook.

trained_model.sav: Saved model.

kaggle.json: (User’s Kaggle API credentials – not included).

License
MIT License

Credits
Thanks to Kaggle, scikit-learn, and NLTK communities for resources and tools.
