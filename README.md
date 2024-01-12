# NewsClassifier: Building an Automated News Classification System with NLP Techniques

## Problem Statement:

Building a news classification system involves several steps,Data Cleaning and Preprocessing,
Text Representation,Topic Labeling and model training. 

### Libraries/Modules needed for the project!

- Pandas - (To Clean and maipulate the data)
- matplotlib, Seaborn - (To plot and visualize the data)
- tensorflow,keras
- streamlit

## Solution

The solution includes the following steps:

1. Data Cleaning and Preprocessing:
- Remove irrelevant information, such as HTML tags  or non-text content.
- Tokenize the text (split it into words or subwords) and remove stop words.
- stemming to reduce words to their base form.

2. Text Representation:
- Converting the text data into numerical format suitable for machine learning models. This can
be done using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) and word
embeddings.

3. Classification Model:
- Split the data into training and testing sets.
- Train a supervised machine learning models Naive Bayes, Support Vector Machines,Desicion Tree,Random Forest,MLPClassifier
  and deep learning moel LSTM to predict the topic of a news article.

4. Evaluation:
- Evaluate the performance of  classification models on the testing set using appropriate
  metrics (accuracy, precision, recall, F1-score).
- Fine-tune the model parameters to improve performance.  

## Conclusion
  SVM classifier Gives 

  Accuracy: 0.831 , Precision: 0.844 , Recall: 0.830 , F1-Score: 0.834 .


