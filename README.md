# Chatbot Application

This is a chatbot application built using Python and Keras. The chatbot uses a neural network to understand and respond to user input.

## Dependencies

- nltk
- pickle
- numpy
- keras
- json
- tkinter

## Usage

To run the chatbot application, run the `chatbot.py` file. This will open a graphical user interface (GUI) where the user can input messages to the chatbot.

```python
python chatbot.py
```

The application will load a pre-trained neural network model from the chatbot_model.h5 file, as well as the words.pkl and classes.pkl files containing the bag of words vocabulary and intent classes used to train the model.

## Code
The code for the chatbot application is contained in the chatbot.py file. The file contains several functions used to preprocess user input, predict the intent of the input, and generate a response.

The code also includes a graphical user interface (GUI) built using tkinter, which allows the user to input messages and receive responses from the chatbot.
