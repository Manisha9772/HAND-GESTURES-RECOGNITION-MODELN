# HAND-GESTURES-RECOGNITION-MODELN
This project implements a deep learning-based model to recognize hand gestures using image or video input. It can be used in applications like Human-Computer Interaction (HCI), sign language interpretation, or smart home controls.

 Features :-
Detects and classifies hand gestures in real-time or from images
Trained on a labeled hand gesture dataset
Built using Python and TensorFlow/Keras (or PyTorch)
Supports webcam/live video input
Easy to integrate with other applications (IoT, robotics, etc.)

Model Architecture :-
Input: 64x64 or 128x128 RGB images
Preprocessing: Grayscale conversion, normalization
CNN layers: 2–4 convolution + pooling layers
Dense layers: Fully connected layers followed by softmax
Output: Gesture classes (e.g., 'Fist', 'Palm', 'Thumbs up', etc.)

Example Gestures :-
Gesture	Label
✊ Fist	0
🖐️ Palm	1
👍 Thumbs Up	2
