# Chatbot_Using_NLTK_-_Keras

This project demonstrates a simple chatbot using Python, TensorFlow/Keras, and natural language processing (NLP). It includes training a model to classify intents and generating responses based on user input.

## Features
- Train a neural network model using `intents.json`.
- Interactive GUI with Tkinter.
- Customizable intents for various applications.

## Files
- `train_chatbot.py`: Script to train the chatbot model.
- `chatgui.py`: Script to run the chatbot GUI.
- `intents.json`: Intent definitions with patterns and responses.
- `chatbot_model.h5`: Saved trained model.
- `words.pkl` and `classes.pkl`: Preprocessed data for inference.

## Setup and Usage

### Prerequisites
- Python 3.x
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
Train the Model
Run the training script:

```bash
python train_chatbot.py
```
Run the Chatbot
Launch the GUI:

```bash
python chatgui.py
```
