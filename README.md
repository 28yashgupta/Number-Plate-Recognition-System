# Number-Plate-Recognition-System
# 📌 Project Overview
This project detects and recognizes number plates from images or video streams using deep learning and computer vision techniques. It extracts number plates, interprets alphanumeric characters, and handles challenges like varying lighting conditions and camera angles.

# 🚀 Features
- Automatic detection and extraction of number plates.
- Optical Character Recognition (OCR) for reading alphanumeric characters.
- Preprocessing techniques for handling low-light or distorted images.
- Works with both static images and real-time video streams.
# 🛠️ Tech Stack
- Programming Language: Python 
- OpenCV (for image processing)
- TensorFlow/Keras or PyTorch (for deep learning models)
- NumPy, Pandas (for data handling)
# 📂 Dataset
Dataset Used: https://www.kaggle.com/datasets/andrewmvd/car-plate-detection
# 🔍 Pipeline
- Preprocessing: Convert to grayscale, apply adaptive thresholding, and noise reduction.
- Number Plate Detection: Uses a deep learning model  YOLOV8 to localize plates.
- Post-processing: Apply filtering and formatting to refine predictions.
# 📊 Evaluation Metrics
- Precision, Recall, and F1-score for character recognition accuracy.
- Mean Average Precision (mAP) for number plate detection.
- Inference Speed to measure real-time processing capability.
# 📸 Results
- Achieved high accuracy in various lighting conditions and viewing angles.
- Robust against minor occlusions and distortions.
# 🏗️ Installation & Usage
Prerequisites:
Python 3.x
OpenCV, TensorFlow
