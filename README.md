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


🔗 Dataset Link: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset


---

## ⚙️ Technologies & Libraries Used

### 🔹 Deep Learning
- TensorFlow / Keras
- CNN (Convolutional Neural Network)

### 🔹 Data Processing
- NumPy
- Pandas

### 🔹 Computer Vision
- OpenCV
- Haar Cascade Classifier

### 🔹 Utilities
- tqdm (progress bar)
- OS (file handling)
- scikit-learn (Label Encoding)

---

## 🔬 Technical Explanation

### 1. Data Preprocessing
- Images are loaded using `load_img()`
- Converted to grayscale (1 channel)
- Resized to **48×48 pixels**
- Converted into NumPy arrays
- Normalized (scaled from 0–255 → 0–1)

---

### 2. Label Encoding
- Text labels (happy, sad, etc.) are converted into numbers using `LabelEncoder`
- Then transformed into **one-hot encoded vectors** using `to_categorical()`

---

### 3. CNN Architecture

#### 🔹 Feature Extraction Layers
- `Conv2D` → Extract features (edges, shapes, patterns)
- `MaxPooling2D` → Reduce spatial size
- `Dropout` → Prevent overfitting

#### 🔹 Classification Layers
- `Flatten` → Convert 2D feature maps into 1D vector
- `Dense` layers → Learn complex relationships
- `Softmax` → Output probability for each emotion

---

### 4. Model Output
- Final layer has **7 neurons**
- Each neuron represents one emotion
- Output is a probability distribution

---

### 5. Real-Time Detection (OpenCV)

#### 🔹 Haar Cascade
- Used for **face detection**
- Detects faces from webcam frames

#### 🔹 Workflow:
---

## ⚙️ Technologies & Libraries Used

### 🔹 Deep Learning
- TensorFlow / Keras
- CNN (Convolutional Neural Network)

### 🔹 Data Processing
- NumPy
- Pandas

### 🔹 Computer Vision
- OpenCV
- Haar Cascade Classifier

### 🔹 Utilities
- tqdm (progress bar)
- OS (file handling)
- scikit-learn (Label Encoding)

---

## 🔬 Technical Explanation

### 1. Data Preprocessing
- Images are loaded using `load_img()`
- Converted to grayscale (1 channel)
- Resized to **48×48 pixels**
- Converted into NumPy arrays
- Normalized (scaled from 0–255 → 0–1)

---

### 2. Label Encoding
- Text labels (happy, sad, etc.) are converted into numbers using `LabelEncoder`
- Then transformed into **one-hot encoded vectors** using `to_categorical()`

---

### 3. CNN Architecture

#### 🔹 Feature Extraction Layers
- `Conv2D` → Extract features (edges, shapes, patterns)
- `MaxPooling2D` → Reduce spatial size
- `Dropout` → Prevent overfitting

#### 🔹 Classification Layers
- `Flatten` → Convert 2D feature maps into 1D vector
- `Dense` layers → Learn complex relationships
- `Softmax` → Output probability for each emotion

---

### 4. Model Output
- Final layer has **7 neurons**
- Each neuron represents one emotion
- Output is a probability distribution

---

### 5. Real-Time Detection (OpenCV)

#### 🔹 Haar Cascade
- Used for **face detection**
- Detects faces from webcam frames

#### 🔹 Workflow:
---

## ⚙️ Technologies & Libraries Used

### 🔹 Deep Learning
- TensorFlow / Keras
- CNN (Convolutional Neural Network)

### 🔹 Data Processing
- NumPy
- Pandas

### 🔹 Computer Vision
- OpenCV
- Haar Cascade Classifier

### 🔹 Utilities
- tqdm (progress bar)
- OS (file handling)
- scikit-learn (Label Encoding)

---

## 🔬 Technical Explanation

### 1. Data Preprocessing
- Images are loaded using `load_img()`
- Converted to grayscale (1 channel)
- Resized to **48×48 pixels**
- Converted into NumPy arrays
- Normalized (scaled from 0–255 → 0–1)

---

### 2. Label Encoding
- Text labels (happy, sad, etc.) are converted into numbers using `LabelEncoder`
- Then transformed into **one-hot encoded vectors** using `to_categorical()`

---

### 3. CNN Architecture

#### 🔹 Feature Extraction Layers
- `Conv2D` → Extract features (edges, shapes, patterns)
- `MaxPooling2D` → Reduce spatial size
- `Dropout` → Prevent overfitting

#### 🔹 Classification Layers
- `Flatten` → Convert 2D feature maps into 1D vector
- `Dense` layers → Learn complex relationships
- `Softmax` → Output probability for each emotion

---

### 4. Model Output
- Final layer has **7 neurons**
- Each neuron represents one emotion
- Output is a probability distribution

---

### 5. Real-Time Detection (OpenCV)

#### 🔹 Haar Cascade
- Used for **face detection**
- Detects faces from webcam frames

#### 🔹 Workflow: Webcam → Frame Capture → Face Detection → Preprocessing→ Model Prediction → Display Emotion



