# Machine Learning Chatbot

A simple intent-based chatbot built using Python and TensorFlow.  
It classifies user messages and responds accordingly using a trained neural network.

## Features
- Intent classification chatbot
- Built using TensorFlow and Keras
- Tokenization and label encoding
- Command-line chat interface

## Tech Stack
- Python
- TensorFlow
- Scikit-learn
- Numpy

## Installation

```bash
pip install -r requirements.txt

## Project Structure
chatbot-ml/
│
├── intents.json
├── train.py
├── chat.py
├── tokenizer.pickle
├── label_encoder.pickle
├── chat_model.keras
├── requirements.txt
└── README.md

## Train the model
python train.py

## Run the chatbot
python chat.py

Type quit to exit the chatbot.
Save the file.

----
