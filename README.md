# Spam Message Detection Using Naive Bayes

## Project Overview

This project implements a Machine Learning model to classify text messages into two categories: **Spam** and **Not Spam** using the Multinomial Naive Bayes algorithm.

The system analyzes the words present in a message and predicts whether it is unwanted spam content or a normal message.

This project demonstrates the application of Natural Language Processing (NLP) and Machine Learning for text classification.

## Objectives

- Build a spam message classification system.
- Understand text preprocessing and feature extraction.
- Convert text messages into numerical features using CountVectorizer.
- Train a classification model using Multinomial Naive Bayes.
- Evaluate model performance using classification metrics.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- CountVectorizer
- Multinomial Naive Bayes
- Jupyter Notebook

## Dataset Description

The project uses a sample dataset containing 20 text messages.

The dataset consists of two columns:

- **Message:** Contains the text messages.
- **Label:** Identifies each message as Spam or Not Spam.

Dataset distribution:
- Spam: 9 messages
- Not Spam: 11 messages

## Project Workflow

1. Import the required Python libraries.
2. Create the sample dataset using Pandas.
3. Separate input features (X) and target labels (y).
4. Convert text messages into numerical features using CountVectorizer.
5. Split the dataset into training and testing sets (80:20).
6. Train the Multinomial Naive Bayes model.
7. Predict the categories of test messages.
8. Evaluate model performance.

## Machine Learning Algorithm

**Multinomial Naive Bayes**

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem.

It calculates the probability of a message belonging to a particular category based on the words present in the message.

It is commonly used for text classification tasks such as spam detection and sentiment analysis.

## Model Evaluation

The model was evaluated using the following metrics:

| Metric | Score |
|---|---:|
| Accuracy | 75% |
| Spam Precision | 0.67 |
| Spam Recall | 1.00 |
| Spam F1-score | 0.80 |

Note: These results are based on a small test dataset of only four messages. They are preliminary results and do not represent guaranteed real-world performance.

## Libraries Required

```bash
pip install pandas scikit-learn jupyter
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. View the predicted results and evaluation metrics.

## Future Enhancements

- Increase the dataset size using real-world messages.
- Improve text preprocessing.
- Test the model on unseen messages.
- Compare Naive Bayes with other classification algorithms.
- Develop a simple web application for real-time spam detection.

## Conclusion

This project demonstrates how Machine Learning and Natural Language Processing can be used to identify spam messages.

By using CountVectorizer for feature extraction and Multinomial Naive Bayes for classification, the model predicts whether a message is Spam or Not Spam.

The project helped me understand the complete Machine Learning workflow, including data preparation, feature extraction, model training, prediction, and evaluation.

---

**Project Category:** Machine Learning | Natural Language Processing | Text Classification

**Author:** Sivapratha G
