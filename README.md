# CodeClauseInternship_Analyze-sentiment-in-movie-reviews
Implementing sentiment analysis and customer segmentation in movie reviews using Natural Language Processing techniques to categorize reviews into positive, negative.
Dataset
The movie_reviews dataset from NLTK is used for training and testing the sentiment analysis model. It includes positive and negative reviews categorized into different classes.
Code Overview
Import Libraries: Import the necessary libraries for data processing, machine learning, and NLP.

Download Dataset: Download the movie_reviews dataset from NLTK. This dataset is used for training and testing the sentiment analysis model.

Load and Preprocess Data: Load the movie reviews, preprocess the text data by removing stopwords and converting words to lowercase. Shuffle the documents for randomness.

Feature Extraction: Extract features (words) and labels (positive/negative) from the preprocessed data.

Train-Test Split: Split the dataset into training and testing sets using scikit-learn's train_test_split.

Feature Extraction Function: Define a function to extract features from a document using word presence as features.

Naive Bayes Classification: Create a Naive Bayes classifier using scikit-learn's CountVectorizer and MultinomialNB within a pipeline.

Model Training and Evaluation: Train the model on the training set and evaluate its performance on the test set. Print accuracy and classification report.
