# 🎙️ Speech Emotion Recognition (SER) Project

## 🧠 Overview

This project implements a **Speech Emotion Recognition (SER)** system using deep learning techniques. The system classifies human speech into **eight emotion categories**:

> `Neutral`, `Calm`, `Happy`, `Sad`, `Angry`, `Fear`, `Disgust`, and `Surprise`.

The model is trained on **four popular speech emotion datasets**:  
📁 **RAVDESS**, **CREMA-D**, **TESS**, and **SAVEE**.

---

## 🔄 Project Workflow

![ser](https://github.com/user-attachments/assets/e1128546-e9ea-4365-97dc-96ab584e3f66)

---

## ✨ Features

✅ Preprocesses and combines multiple speech emotion datasets  
✅ Extracts audio features including **MFCCs**, **chroma**, **mel spectrogram**, etc.  
✅ Applies **data augmentation** techniques:
- Noise injection  
- Time stretching  
- Pitch shifting  

✅ Utilizes a **1D Convolutional Neural Network (CNN)** for emotion classification  
✅ Achieves **high accuracy** in emotion recognition  

---

## 📚 Datasets Used

The model is trained on the following benchmark datasets:

- **RAVDESS**: Ryerson Audio-Visual Database of Emotional Speech and Song  
- **CREMA-D**: Crowd-sourced Emotional Multimodal Actors Dataset  
- **TESS**: Toronto Emotional Speech Set  
- **SAVEE**: Surrey Audio-Visual Expressed Emotion  

---

## 🧱 Model Architecture

The Speech Emotion Recognition model utilizes a **1D Convolutional Neural Network (CNN)** designed for sequential audio feature data. The architecture consists of:

- 🧩 **Three 1D Convolutional Layers** with ReLU activation and Max Pooling
- 🚫 **Dropout Layers** to prevent overfitting and improve generalization
- 🔄 **Flatten Layer** to convert features into a 1D vector
- 🧮 **Fully Connected Dense Layers** for emotion classification

This architecture is optimized to capture local temporal patterns in speech features like MFCCs, chroma, and mel spectrograms.

---

## 📈 Results

The trained model demonstrates strong performance on the combined dataset:

- ✅ **Test Accuracy**: ~85%
- 📊 Detailed **classification report** (precision, recall, F1-score) and **confusion matrix** are available in the training notebook for deeper evaluation.

The model effectively distinguishes between 8 emotion classes and shows robustness across multiple speech datasets.

---

