📝 Sentiment Analysis on Twitter Data using Logistic Regression

📌 Project Overview
This project presents a comprehensive approach to sentiment analysis using the Sentiment140 dataset, with a focus on classifying tweets as either positive or negative. By leveraging the power of Natural Language Processing (NLP) and a Logistic Regression classifier, the solution demonstrates a robust pipeline for handling real-world text data from social media.

This notebook was developed using Google Colab and includes end-to-end steps from data acquisition to model evaluation. It serves as a foundational project for understanding sentiment classification and deploying classical machine learning techniques in NLP workflows.

📊 Dataset Description
Name: Sentiment140

Source: Kaggle Dataset - Sentiment140

Size: 1.6 million tweets

Format: CSV

Labels:

0: Negative sentiment

4: Positive sentiment

Each record includes the tweet text, user information, and a sentiment label. For this project, only the text and sentiment columns are used.

🛠️ Project Workflow
The notebook follows a well-structured machine learning pipeline:

1. Dataset Integration
Utilizes the Kaggle API to programmatically download the Sentiment140 dataset.

Uploaded and configured kaggle.json credentials securely within Colab.

2. Data Preprocessing
Removed irrelevant columns and handled missing values.

Cleaned tweet text by removing punctuation, links, user mentions, and stopwords.

Performed basic tokenization and normalization.

3. Feature Engineering
Transformed textual data into numerical form using CountVectorizer or TF-IDF Vectorizer.

Converted the corpus into a sparse matrix representation suitable for modeling.

4. Model Training
Implemented Logistic Regression, a linear model suitable for binary classification.

Trained on the vectorized features to distinguish between positive and negative sentiments.

5. Model Evaluation
Assessed model performance using:

Accuracy Score

Confusion Matrix

Classification Report

Performed validation on a separate test set to measure generalizability.

🤖 Technologies & Libraries Used
Python

Google Colab

scikit-learn – model training and evaluation

pandas, numpy – data handling

matplotlib, seaborn – data visualization

Kaggle API – dataset acquisition

🚀 Results & Observations
The Logistic Regression model provided a strong baseline for sentiment classification.

Achieved significant accuracy in identifying tweet polarity.

Simple yet effective text preprocessing and classical ML techniques can yield meaningful insights from social media data.

▶️ How to Use
Clone this repository or open the notebook in Google Colab.

Upload your kaggle.json file to enable dataset download.


📌 Future Enhancements
Experiment with advanced models like Naive Bayes, SVM, or deep learning approaches (LSTM, BERT).

Integrate a sentiment dashboard for real-time visualization.

Extend support for neutral sentiment classification.

👩‍💻 Author
Chinmayee Sahithya Guttula
Aspiring AI & Data Science Enthusiast | Passionate about NLP and Machine Learning
