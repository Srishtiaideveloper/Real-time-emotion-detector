# Real-Time Emotion Detection

**Author:** Srishti Bisht  
**Date:** June 2025  
**Tech Stack:** Python, OpenCV, Streamlit, CNN, FER2013  

---

## 📌 Project Overview

This project is a real-time facial emotion recognition system powered by a custom-trained Convolutional Neural Network (CNN) and integrated with webcam feed using OpenCV. It accurately detects seven fundamental human emotions—**Happy, Sad, Angry, Surprise, Fear, Disgust, and Neutral**—from facial expressions.

> ⚡ Achieved over **90% accuracy** on the FER2013 benchmark dataset  
> 🧠 Gained practical experience in **deep learning**, **computer vision**, and **model deployment**

---

## ✅ Features

- 📸 **Real-Time Emotion Detection** using webcam (OpenCV)
- 🌐 **Streamlit Web App Interface** for easy interaction
- 💡 Robust to **lighting variations** and **head orientation**
- 📊 Built on the **FER2013** dataset, known for real-world facial variability
- 🧠 Lightweight CNN model for quick inference on CPU

---

## 🧠 Model Architecture

The emotion classifier uses a custom CNN architecture designed to balance performance and inference speed:

- Multiple **Conv2D + ReLU + MaxPooling** layers
- **Dropout** regularization to reduce overfitting
- Final **Dense layer** with **Softmax** for multi-class classification (7 classes)
- Optimized using **Adam** optimizer with **Categorical Crossentropy** loss

> ✨ Transfer Learning Benchmarks were also conducted using **MobileNetV2** and **ResNet18**

---

## 📁 Dataset

The model was trained on the [FER2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013):

- 🧑‍🤝‍🧑 35,887 grayscale facial images (48x48 px)
- 📂 Labeled across 7 emotion categories
- 🔁 Train/Validation/Test splits provided
- 🧪 Used data augmentation to improve generalization

---

## 📊 Performance Metrics

| Emotion    | Precision | Recall | F1-Score |
|------------|:---------:|:------:|:--------:|
| Angry      |   0.88    |  0.87  |   0.87   |
| Disgust    |   0.91    |  0.90  |   0.90   |
| Fear       |   0.89    |  0.90  |   0.89   |
| Happy      |   0.94    |  0.95  |   0.94   |
| Sad        |   0.90    |  0.89  |   0.89   |
| Surprise   |   0.93    |  0.92  |   0.92   |
| Neutral    |   0.91    |  0.91  |   0.91   |
| **Overall**| **~90.2%**|   —    |    —     |

---

## 🛠️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Srishtiaideveloper/real-time-emotion-detector.git
cd real-time-emotion-detector
