# SignLanguageConverter
Sem V Mini Project
A practical implementation of sign language estimation using an LSTM NN built on TF Keras.

# About
The project aims to enable real-time gesture recognition for applications like sign language translation or gesture-based control.
The dataset consists of three gestures: "hello," "thanks," and "iloveyou."

# Key Take-aways
1) A gesture recognition system using TensorFlow and MediaPipe.
2) Utilizes a webcam to capture real-time video input, then employs MediaPipe's holistic model to extract key points from face, body, and hand landmarks.
3) These key points are stored as numerical data and used for training a deep learning model.
4) An LSTM neural network is trained on this data to recognize and classify the gestures.
5) The model achieved an accuracy of around 87% on the test data.

# Technical Stack used
- TensorFlow
- MediaPipe
- OpenCV (cv2)
- Keras
- Scikit-learn
- Matplotlib
- OS
