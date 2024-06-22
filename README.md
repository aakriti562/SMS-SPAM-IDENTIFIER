# SMS-SPAM-CLASSIFIER

This project is an SMS Spam Classifier that uses machine learning techniques to classify messages as either 'spam' or 'ham' (not spam). The classifier is trained on a labeled dataset of SMS messages and employs natural language processing (NLP) methods to transform text data into features suitable for a machine learning model.


## Features

The features are derived from the SMS text messages using various NLP techniques such as:

- Tokenization
- Stopword removal
- Stemming/Lemmatization
- Bag-of-Words (BoW)
- Term Frequency-Inverse Document Frequency (TF-IDF)




## Installation

1. Clone the repository:

```bash
git clone https://github.com/aakriti562/SMS-SPAM-CLASSIFIER.git

```

2. Create a virtual environment and activate it:

```bash
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

```

3. Install the required dependencies:

```bash
pip install -r requirements.txt

```

## DATASET

The dataset used in this project is a collection of SMS messages labeled as 'spam' or 'ham'. The dataset file *spam.csv* is located in the data/ directory. Each row in the dataset contains a label and the corresponding SMS message.





## Model Training
The model training involves:

- Splitting the data into training and testing sets
- Transforming text data into numerical features
- Training a machine learning model (e.g., Naive Bayes, SVM, or Logistic Regression)
- Hyperparameter tuning using cross-validation

## Evaluation
The performance of the model is evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility

Contributions are welcome! Please follow these steps to contribute:

- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit them (git commit -am 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Create a new Pull Request.
  
## Screenshots

![image](https://github.com/aakriti562/SMS-SPAM-IDENTIFIER/assets/76481840/900154a8-ff53-4544-b6b9-030330f2bda4)



![b66e7476-f2cb-47c6-bea9-10e815a894be](https://github.com/aakriti562/SMS-SPAM-IDENTIFIER/assets/76481840/99d3ba1e-a93f-41df-b143-db970f311eec)

## Deployment 

https://huggingface.co/spaces/aakritim/SMS-SPAM-DETECTION

