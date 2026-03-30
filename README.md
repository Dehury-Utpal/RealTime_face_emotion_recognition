# 🎭 RealTime Facial Emotion Recognition using CNN & OpenCV

## 📌 Project Overview
This project focuses on building a **Facial Emotion Recognition System** using **Convolutional Neural Networks (CNN)** and deploying it for **real-time emotion detection** using a webcam.

The system is capable of identifying human emotions such as:
- Angry  
- Disgust  
- Fear  
- Happy  
- Neutral  
- Sad  
- Surprise  

It combines **deep learning for classification** and **computer vision (OpenCV)** for real-time face detection.

---

## ❓ Problem Statement
Understanding human emotions is a key aspect of human-computer interaction. Traditional systems cannot interpret facial expressions effectively.

👉 The goal of this project is to:
- Automatically detect faces in images/video  
- Classify facial expressions into predefined emotion categories  
- Enable real-time emotion recognition using a webcam  

---

## 🧠 Approach & Solution

The solution is divided into two main parts:

### 1. Image-based Emotion Classification (Deep Learning)
- Train a CNN model on labeled facial expression data
- Convert images into numerical tensors
- Learn patterns like facial features (eyes, mouth, expressions)

### 2. Real-Time Emotion Detection (OpenCV)
- Use webcam feed
- Detect faces using Haar Cascade
- Pass detected face to trained CNN model
- Predict emotion instantly

---

## 🏗️ Project Pipeline
Dataset → Preprocessing → Feature Extraction → Label Encoding
↓
CNN Model Training
↓
Model Prediction
↓
Real-time Detection using OpenCV
