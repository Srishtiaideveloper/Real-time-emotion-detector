# Real-Time Emotion Detection 

**Author:** Srishti Bisht  
**Date:** June 2025  
**Tech Stack:** Python, OpenCV, Streamlit, CNN, FER2013  

---

## 📌 Project Overview

This project is a real-time facial emotion recognition system that leverages a custom-trained Convolutional Neural Network (CNN) and live webcam feed. It accurately detects seven basic emotions—**Happy, Sad, Angry, Surprise, Fear, Disgust, and Neutral**—directly from human facial expressions using OpenCV and Streamlit.

> ⚡ Achieved over **90% accuracy** on the FER2013 dataset.  
> 🧠 Gained hands-on experience in **deep learning**, **computer vision**, and **model deployment**.

---

## ✅ Features

- 🔍 **Real-Time Webcam Detection** using OpenCV
- 📊 **Streamlit Web App Interface** for user-friendly interaction
- 💡 Handles **lighting variations** and **different head orientations**
- 🧠 Trained on **FER2013**, a robust and diverse facial expression dataset
- 🎯 Optimized CNN architecture for performance and accuracy

---

## 🧠 Model Architecture

A custom CNN with multiple convolutional and pooling layers was trained to extract spatial features from grayscale facial images. The model was fine-tuned using:

- **Dropout** for regularization  
- **Adam optimizer**  
- **ReLU activations**  
- Final layer with **Softmax** over 7 classes  

Optional: Transfer learning experiments were also done using **MobileNetV2** and **ResNet18** for benchmarking.

---

## 📁 Dataset

The model is trained on the [FER2013](https://www.kaggle.com/datasets/msambare/fer2013) dataset which consists of:

- 🧑‍🤝‍🧑 35,887 grayscale facial images (48x48 pixels)  
- 🔍 Labeled with 7 emotion classes  
- 🧪 Split into training, validation, and test sets

---
📊 Model Architecture
The CNN consists of:

Convolutional layers (3x3 filters)

ReLU activations

MaxPooling layers

Fully connected layers

Final softmax output over 7 classes

Loss Function: Categorical Crossentropy
Optimizer: Adam (lr=0.001)
Metrics: Accuracy

##🧪 Performance
Emotion	Precision	Recall	F1-Score
Angry	0.88	0.87	0.87
Disgust	0.91	0.90	0.90
Fear	0.89	0.90	0.89
Happy	0.94	0.95	0.94
Sad	0.90	0.89	0.89
Surprise	0.93	0.92	0.92
Neutral	0.91	0.91	0.91

📌 Overall Accuracy: ~90.2%


## 🛠️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Srishtiaideveloper/real-time-emotion-detector.git
cd real-time-emotion-detector
