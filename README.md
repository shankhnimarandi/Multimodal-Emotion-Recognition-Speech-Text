# Multimodal Emotion Recognition System (Speech + Text)

This project predicts human emotions using two types of inputs: speech and text. It uses separate LSTM models for both modalities and then combines their results to produce a final emotion output. The system works in Jupyter Notebook and supports real-time audio recording.

## Features

* Speech emotion recognition using MFCC + LSTM

* Text emotion recognition using LSTM

* Real-time audio recording for predictions

* Clean and simple model training code

* Easy-to-run Notebook for complete workflow

## Datasets

## Speech Dataset – TESS

This project uses the TESS (Toronto Emotional Speech Set) for speech emotion training.
The dataset is too large to upload on GitHub, so here is the official link:

Download TESS Dataset:

https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

## Text Dataset

A labeled text emotion dataset is used for training the text model.

## Technologies Used

* Python

* TensorFlow / Keras

* Librosa

* NumPy

* Scikit-learn

* NLP preprocessing

## How to Run

1. Download the TESS dataset from the link above.

2. Place it in a folder named TESS/ inside the project.

3. Open the Jupyter Notebook.

4. Run the cells step-by-step to train speech and text models.

5. Use your microphone or text input to test the system.
