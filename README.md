
# Persian Speech Emotion Detection using CNN and LSTM

## Overview
This project is designed to build a deep learning model that detects emotions in Persian speech using the Shemo Persian Speech Emotion Detection Database.
 The model is based on a combination of convolutional neural networks (CNNs) and long short-term memory networks (LSTMs) for robust feature extraction and classification. The code leverages popular machine learning libraries such as TensorFlow, Keras, and Librosa to preprocess audio data and train the model.

## Dataset

 
The Shemo Persian Speech Emotion Detection Database, available on Kaggle, is used in this project. The dataset contains speech samples from male and female speakers, each labeled with different emotions. The dataset is downloaded directly from Kaggle using the Kaggle API.  (https://www.kaggle.com/datasets/mansourehk/shemo-persian-speech-emotion-detection-database)

## Features
- Audio Augmentation: Augments the audio with pitch shifting, time stretching, and noise injection to enhance the dataset and improve generalization.
- Feature Extraction: Extracts both Mel-frequency cepstral coefficients (MFCCs) and chroma features from audio files.
- CNN + LSTM Architecture: Combines CNN layers for local feature extraction and LSTM layers for sequential data modeling to classify the emotions.
- Class Imbalance Handling: Utilizes class weights to handle imbalanced data.
- Evaluation: The model is evaluated based on accuracy and loss for both training and testing datasets, and predictions are displayed for random samples.

## Contributing
Feel free to fork this repository and submit pull requests.

