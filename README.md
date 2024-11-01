# Facial Emotion Detection

A deep learning-based emotion detection system that classifies facial expressions into seven distinct emotions using a Convolutional Neural Network (CNN). This project leverages TensorFlow and Keras for model building and training, and OpenCV for image processing. The inspiration for this project is the understanding and identifying emotions as a tool to support mental health. Recognizing that early detection of emotional states—such as indicators of stress, anxiety, or depression—can help provide timely support and foster empathy, improving overall mental wellness.

## Features
- **Automatic Image Processing**: Reads and preprocesses images from Google Drive.
- **CNN Architecture**: Utilizes a deep CNN with multiple convolutional and batch normalization layers to effectively capture facial features.
- **Data Augmentation**: Implements real-time data augmentation to enhance model generalization.
- **Early Stopping & Learning Rate Scheduling**: Prevents overfitting and optimizes training.
- **Real-Time Emotion Prediction**: Captures images via webcam and predicts emotions in real-time.

## Emotions
The model classifies emotions into the following categories:
1. Angry
2. Disgusted
3. Fearful
4. Happy
5. Neutral
6. Sad
7. Surprised
