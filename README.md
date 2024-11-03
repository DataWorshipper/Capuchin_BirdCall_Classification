# Capuchin_BirdCall_Classification

## Project Overview
This project focuses on classifying whether forest recordings, each 3 minutes long, contain Capuchin bird calls. If Capuchin calls are present, the project also counts the number of calls. This project was conducted as part of the Z by HP Unlocked Challenge 3, and it represents my first foray into audio classification.

## Approach
Spectrogram Generation:
Converted audio files into spectrograms to visualize and analyze audio data.
Spectrograms were used as inputs for the Convolutional Neural Network (CNN) model.

## Model Architecture:
Implemented a Convolutional Neural Network (CNN) to classify audio data.
Used TensorFlow's dataset pipeline for efficient data management.
The model was trained on 3-second audio clips of Capuchin and non-Capuchin calls.

## Sliding Window Approach:
Applied a sliding window approach on 3-minute audio recordings to detect Capuchin calls.
Each 3-second frame of the recording was analyzed to determine the presence of Capuchin calls.
Counted the number of Capuchin calls in each 3-second frame.

## Key Components
Data Pipeline: Efficiently managed audio data using TensorFlow's dataset pipeline.
Model Training: Used spectrograms of 3-second clips for training the CNN.
Inference: Applied the trained model to 3-minute recordings using a sliding window approach to classify and count Capuchin calls.
Results
Successfully classified and counted Capuchin bird calls in 3-minute forest recordings.
Demonstrated effective use of CNNs for audio classification and a sliding window technique for continuous audio analysis.
