Project Description
This notebook demonstrates the process of building a Recurrent Neural Network (RNN) using TensorFlow and Keras for musical instrument sound classification. The project involves:

Data Acquisition: Downloading a dataset of musical instrument sounds from Kaggle.
Data Preprocessing: Loading audio files, extracting MFCC (Mel-Frequency Cepstral Coefficients) features, and preparing the data for training.
Model Definition: Designing an RNN model using Keras with LSTM layers for sequence processing.
Model Training: Compiling and training the model on the prepared dataset.
Prediction: Implementing a function to predict the musical instrument from a new audio file using the trained model.
Steps in the Notebook
Step 1-3: Downloading and extracting the dataset from Kaggle.
Step 4: Installing necessary libraries (librosa, soundfile, tensorflow, pandas).
Step 5: Importing required libraries for data processing, model building, and file handling.
Step 6: Loading the metadata, extracting MFCC features from the audio files, and splitting the data into training and validation sets.
Step 7: Defining, compiling, and training the RNN model.
Step 8: Implementing a function to upload an audio file and predict the instrument class using the trained model.
