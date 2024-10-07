# Voice Emotion Recognition using LSTM

## Project Overview
This project aims to accurately classify emotions from voice recordings using a Long Short-Term Memory (LSTM) network. By training on the Sharif Emotional Speech Database, the model learns to detect subtle emotional nuances in speech, enabling applications in areas such as interactive voice response systems and psychological research.

## Technologies Used
- **Python**: Primary programming language.
- **TensorFlow**: For building and training the LSTM model.
- **LibROSA**: For audio signal processing.

## Dataset
The project utilizes the [Sharif Emotional Speech Database](https://github.com/mansourehk/ShEMO), which is a large-scale validated dataset specifically designed for Persian speech emotion detection.
- **Reference**: [A Large-Scale Validated Database for Persian Speech Emotion Detection](https://arxiv.org/abs/1906.01155)

## Model Description
The LSTM model is trained to recognize seven different emotions from voice data. Emotions include happiness, sadness, anger, fear, surprise, disgust, and neutral. The LSTM's ability to maintain long-term dependencies makes it particularly effective for speech-based emotion recognition, where context and intonation play critical roles.
