This project purposes to distinguish cyberbullying behaviors on Twitter by classifying tweets into various types of cyberbullying. The program influences machine learning and natural language processing (NLP) techniques to analyze tweet text and expect the type of cyberbullying. The main goal is to provide an automated solution to identify damaging content on social media platforms, contributing to a safer online environment.Methods Used
1. Data Preprocessing
Text Cleaning: Removed URLs, mentions, hashtags, special characters, and stopwords.
Normalization: Lowercased all text and applied stemming.
Vectorization: Used techniques like HashingVectorizer, TfidfVectorizer, and CountVectorizer to convert text into numerical features.
Feature Engineering: Generated word frequency distributions and visualizations (e.g., word clouds).
2. Machine Learning Models
Multiple machine learning models were implemented and evaluated for performance:

Passive Aggressive Classifier,
AdaBoost Classifier,
Multinomial Naive Bayes,
Logistic Regression,
Support Vector Classifier (SVC)
Evaluation Metrics
Accuracy,
Precision,
Recall,
F1-score,
Classification reports and confusion matrices were used for detailed analysis.
4. Visualization
Distribution of cyberbullying types using bar plots and pie charts.
Most frequent words using word clouds.
Sentiment distribution using TextBlob for polarity and subjectivity.
Visual Outputs
Bar charts, pie charts, and word clouds summarizing the data.
Histograms for sentiment analysis.
Model Output
Classification reports summarizing model performance.
Saved trained models as .pkl files for future use
Features
Automated Cyberbullying Detection: Classifies tweets into predefined categories.
Preprocessing Pipeline: Cleans and prepares data for analysis.
Multiple Model Implementations: Supports comparison of various machine learning models.
Sentiment Analysis: Provides insights into the sentiment of tweets.
Visualization: Offers comprehensive visual summaries of the dataset.
