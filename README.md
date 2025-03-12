# ImplementationOfChatBotUsingNLP
This project is a simple chatbot built using Natural Language Processing (NLP) techniques. It utilizes NLTK for text processing, TfidfVectorizer for feature extraction, and LogisticRegression for intent classification. The chatbot is implemented as a web application using Streamlit.

# Features

* Classifies user input into predefined intents.

* Uses a Logistic Regression model for text classification.

* Stores conversation history in a CSV file.

* Provides a simple and interactive UI using Streamlit.

## Installation

# Prerequisites

Ensure you have Python installed (Python 3.7 or later).

# Install Dependencies

Run the following command to install required libraries:
```
pip install nltk streamlit scikit-learn
```
# Usage

# 1. Download NLTK Data

Before running the chatbot, download the necessary NLP datasets:
```
import nltk
nltk.download('punkt')
```
# 2. Run the Chatbot

To start the Streamlit application, navigate to the project folder and run:
```
streamlit run your_script.py
```
Replace ```your_script.py``` with the actual filename of your chatbot script.

# 3. Using the Chatbot

* Enter text in the input field to start a conversation.

* The chatbot will respond based on trained intents.

* Conversation history is saved in ```chat_log.csv```.

## Extending the Project

* Improve the model using deep learning techniques like RNNs or transformers.

* Add more intents and responses to enhance conversation capability.

* Integrate an external database for storing conversation history.
