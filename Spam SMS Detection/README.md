## Description
The Spam SMS Detection System is a machine learning project designed to classify text messages as either spam (unwanted promotional or fraudulent messages) or non-spam (ham). By analyzing the content of SMS messages, the system uses various natural language processing (NLP) techniques and machine learning algorithms to identify patterns and predict the likelihood of a message being spam. This project demonstrates the practical application of NLP in combating spam in messaging systems.


## Techniques Used

- **Text Preprocessing**:   
- **TF-IDF (Term Frequency-Inverse Document Frequency)**:  
- **Word Embeddings**:  
- **Machine Learning Classifiers**:  


## Dataset 
The dataset contains SMS messages labeled as either "spam" or "ham" (non-spam). It is sourced from open repositories such as:    
- Kaggle Datasets
- https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

**Features**: SMS message content  
**Target**: Binary labels: `spam` or `ham`


## Key Features

- **Text Processing**:  
  Preprocessing steps ensure clean and uniform input for training.  

- **Feature Extraction**:  
  Implementation of TF-IDF or word embeddings to transform textual data into numerical formats.  

- **Multiple Classifiers**:  
  Training and comparing models like Naive Bayes, Logistic Regression, and Random Forest to determine the most effective approach.  

- **Model Evaluation**:  
  Performance metrics such as accuracy, precision, recall, F1-score, and confusion matrix are used to assess the models.  

- **Real-Time Prediction**:  
  The system classifies SMS messages as spam or ham based on input text, allowing for real-time applications.  

## Colab Link  
https://colab.research.google.com/drive/1EMifIcauqtvgjdzYxiY2qVEt-iXuMS7E?usp=sharing


## Outcome 
The Spam SMS Detection System accurately classifies messages into spam and non-spam categories, achieving high precision and recall. The project highlights the use of NLP techniques in real-world applications, demonstrating its ability to handle text data effectively. The accuracy of the system can be further enhanced with larger datasets, hyperparameter tuning, and more advanced word embeddings like BERT.
