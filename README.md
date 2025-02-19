# Number-Plate-Recognition-System
# 📌 Project Overview
This project detects and recognizes number plates from images or video streams using deep learning and computer vision techniques. It extracts number plates, interprets alphanumeric characters, and handles challenges like varying lighting conditions and camera angles.

# 🚀 Features
- Automatic detection and extraction of number plates.
- Preprocessing techniques for handling low-light or distorted images.
- Works with both static images and real-time video streams.

# 🛠️ Tech Stack
- Programming Language: Python 
- OpenCV (for image processing)
- TensorFlow/Keras  (for deep learning models)
- NumPy, Pandas (for data handling)
  
# 📂 Dataset
Dataset Used: https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

# 🛠 Approach

1️⃣ Data Collection
- Collected a dataset of vehicle images with visible number plates.

2️⃣ Preprocessing
- Converted images to grayscale for improved processing.

3️⃣ Number Plate Detection
- Used  YOLOv8 for detecting number plates.
- Applied edge detection and contour analysis to localize the plate region.

4️⃣ Character Segmentation
- Extracted individual characters from the detected number plate.
- Used contour-based or bounding box methods to separate characters.

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
