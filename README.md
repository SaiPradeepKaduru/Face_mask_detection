🧑‍⚕️ Face Mask Detection using OpenCV & Deep Learning
📌 Project Overview

This project implements a real-time face mask detection system using:

OpenCV for video-based face detection

TensorFlow/Keras for deep learning model training

Jupyter Notebooks for experimentation & documentation

The model classifies faces into two categories:

✅ With Mask

❌ Without Mask

📊 Dataset

The dataset consists of images of people with and without masks.

You can use popular datasets like:

Kaggle Face Mask Detection Dataset

Or your own custom dataset.

🚀 Usage
1. Run Face Detection Notebook
jupyter notebook Face_Detection_Video.ipynb

2. Run Video Detection with OpenCV
jupyter notebook Video_based_detection_using_openCV.ipynb

3. Use Pretrained Model
from tensorflow.keras.models import load_model
model = load_model("Mask_detector.keras")

🛠️ Tech Stack

Python 3.8+

TensorFlow / Keras

OpenCV

NumPy, Pandas, Matplotlib

📈 Results

Achieved high accuracy in detecting masked vs. unmasked faces.

Works in real-time with a webcam feed.

📌 Future Improvements

Extend to detect incorrect mask usage.

Deploy as a web app / mobile app.

Optimize model for edge devices (Raspberry Pi, Jetson Nano).
