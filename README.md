# Real-Time Emotion Detection (2025)

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

## 🛠️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Srishtiaideveloper/real-time-emotion-detector.git
cd real-time-emotion-detector
