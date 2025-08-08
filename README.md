# Real-Time-Emotion-Recognition-system
This project is a deep learning-based real-time facial emotion recognition system. It uses the Mini-XCEPTION convolutional neural network model trained on the FER2013 dataset. The system can detect a person’s face using a webcam, analyze their facial expression, and predict the corresponding emotion live.

## Key Features
Real-Time Emotion Detection via webcam.
Mini-XCEPTION Architecture: Lightweight and efficient deep CNN.
Trained on the FER2013 dataset with 7 emotion categories.
Data Augmentation for better generalization.
Class Balancing using class_weight to reduce bias.
Haar Cascade Classifier for face detection.
Live confidence scores and FPS overlay.

## Dependencies
Python 3.7+, TensorFlow 2.x, OpenCV. NumPy, scikit-learn

## Model: Mini-XCEPTION
Mini-XCEPTION is a reduced version of the Xception architecture designed for facial emotion recognition. It uses:
Separable convolutions
Batch normalization
Global average pooling
Dropout regularization
This makes it fast and suitable for real-time applications, especially on resource-limited machines.

## Emotion Categories
The model predicts one of the following 7 emotions:
- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

##  License
This project is open-source and available under the MIT License.
