# 🤟 Sign Language Video Recognition using Deep Learning

This repository contains the source code, documentation, and resources for the major project titled **"Language Translation: End-to-End Deep Learning for Sign Language Video Recognition"**, submitted by **M. Chinnari (21C91A6637)** in partial fulfillment of the B.Tech degree in **Computer Science and Engineering (Artificial Intelligence & Machine Learning)** at **Holy Mary Institute of Technology & Science**.

## 📌 Project Overview

This project aims to develop a real-time system that translates Indian Sign Language (ISL) gestures into text using deep learning. It leverages Convolutional Neural Networks (CNNs) and transfer learning to recognize hand gestures from video input, promoting inclusive communication for the deaf and hard-of-hearing community.

## 🎯 Objectives

- Build an end-to-end deep learning model for sign language recognition.
- Use webcam input to capture and classify ISL gestures.
- Apply CNNs and LSTMs to extract spatial and temporal features.
- Ensure high accuracy even with limited datasets.
- Promote accessibility and inclusion through AI.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- CNN + LSTM architecture
- Webcam or Microsoft Kinect (optional)

## 📁 Repository Structure
sign-language-recognition/ 

├── dataset/ # ISL gesture images or video samples 

├── models/ # Trained model files (.h5)

├── src/ # Source code for training and inference │

├── data_preprocessing.py │

├── train_model.py │

├── predict_sign.py │

└── webcam_inference.py 

├── snapshots/ # Screenshots of model predictions

├── requirements.txt # Python dependencies 

├── README.md # Project overview 

└── LICENSE # Open-source license

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sign-language-recognition.git
   cd sign-language-recognition

pip install -r requirements.txt

python src/webcam_inference.py

📸 Sample Output
Input: ISL gesture for "HOW OLD YOU"
Output: "How old are you?"





























