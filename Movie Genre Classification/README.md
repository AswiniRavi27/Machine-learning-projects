## Description

The Movie Genre Classification System is a machine learning project aimed at predicting the genre of a movie based on its plot summary or other textual information. By analyzing the movie's description, the model is trained to classify it into one of several predefined genres such as Action, Comedy, Drama, Horror, etc. This system uses various techniques for text preprocessing, feature extraction, and classification, enabling the prediction of movie genres with high accuracy.

## Techniques Used

- **TF-IDF (Term Frequency-Inverse Document Frequency)**: Used for feature extraction, this technique converts the movie plot text into numerical vectors that capture the importance of each word in the context of the entire dataset.
  
- **Word Embeddings**: Advanced techniques like Word2Vec or GloVe (Global Vectors for Word Representation) can be used to represent words as dense vectors based on their meaning, offering better context and semantic understanding.

- **Machine Learning Classifiers**:
  - **Naive Bayes**: A probabilistic classifier based on Bayes' theorem, suitable for text classification problems.
  - **Logistic Regression**: A linear model used for binary and multiclass classification tasks, often applied in text classification problems.
  - **Support Vector Machine (SVM)**: A powerful classifier that works well with high-dimensional spaces, like text data.

## Dataset

The dataset consists of movie plot summaries and their corresponding genres. The data can be sourced from various movie databases such as:
- Kaggle Datasets
- https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

The dataset includes textual plot summaries, movie genres, and other metadata. The movie genres are used as labels, and the plot summaries are the features for training the model.

- **Features**: Movie plot summaries or synopses
- **Target**: Movie genre labels (e.g., Action, Drama, Comedy)

## Key Features

- **Text Processing**: Preprocessing of textual data by cleaning, tokenizing, and removing stop words to prepare it for model training.
- **TF-IDF/Word Embeddings**: Use of TF-IDF or word embeddings to convert text into numerical representations for model input.
- **Multiple Classifiers**: Model training using multiple classifiers (Naive Bayes, Logistic Regression, and SVM) to evaluate performance and select the best model.
- **Model Evaluation**: Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the performance of the model.
- **Prediction**: The system predicts the genre of a movie based on its plot summary.

## Colab Link

https://colab.research.google.com/drive/1sET9SEqYmKp1_ZJMKKjXAZlNejcZixi1?usp=sharing

## Outcome

The Movie Genre Classification System successfully classifies movies into genres based on their plot summaries. By using different machine learning classifiers, the model achieves an accuracy that can be improved with further data augmentation, hyperparameter tuning, or more advanced word embeddings. The project demonstrates the use of natural language processing (NLP) in a real-world application, offering a simple yet powerful way to categorize movies based on text data.
