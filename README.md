# Email Spam Detection using Python
This GitHub repository contains Python code for email spam detection using a machine learning model built with TensorFlow and Keras. The implementation covers data preprocessing, downsampling for dataset balance, text cleaning, and the creation of a Long Short-Term Memory (LSTM) model for classification.

## Key Features:

### Data Loading and Exploration:

Utilizes Pandas to load the dataset ('spam_ham_dataset.csv') and explore its structure.

### Data Balancing:

Performs downsampling to balance the dataset by selecting a subset of non-spam (ham) messages.

### Text Preprocessing:

Removes unnecessary columns, punctuation, and stopwords to enhance the quality of the text data.

### Word Cloud Visualization:

Generates word clouds to visually represent the most frequent words in both spam and non-spam emails.

### Tokenization and Padding:

Tokenizes and pads the text data for input into the LSTM model.

### LSTM Model Building:

Constructs an LSTM model using TensorFlow and Keras, comprising an embedding layer, LSTM layer, and dense layers for classification.

### Model Training:

Trains the model on the preprocessed and tokenized data, with early stopping and learning rate reduction callbacks.

### Model Evaluation:

Evaluates the trained model on the test dataset and plots the accuracy over epochs.

### Prediction Example:

Provides an example of using the trained model to predict whether a given text is spam or non-spam. 
