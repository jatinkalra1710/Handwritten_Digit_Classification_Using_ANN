# Handwritten_Digit_Classification_Using_ANN
This repository demonstrates a complete pipeline for classifying handwritten digits from the MNIST dataset using an Artificial Neural Network (ANN) built with TensorFlow and Keras. It is a beginner-friendly yet powerful example of applying deep learning to image classification tasks.

## 📘 Overview
The MNIST dataset consists of 70,000 grayscale images of handwritten digits — 60,000 for training and 10,000 for testing.
Each image is 28×28 pixels. The goal is to predict the digit represented in the image.

---

## ⚙️ Technologies Used
- Python 3
- TensorFlow / Keras
- Matplotlib
- Scikit-learn
- NumPy / Pandas

---

## 🏗️ Model Architecture

| Layer Type | Output Shape | Activation | Description |
|-------------|---------------|-------------|--------------|
| Flatten | 784 | – | Converts 28×28 input to 1D |
| Dense | 128 | ReLU | Hidden layer |
| Dense | 32 | ReLU | Hidden layer |
| Dense | 10 | Softmax | Output layer (digit classes) |

---

## 🚀 Training
Trained for 50 epochs using Adam optimizer and sparse categorical crossentropy loss.

---

## 📊 Results

**Test Accuracy:** 97.58%  
**Average Precision / Recall / F1:** ~0.98

---

### 🔢 Confusion Matrix and Classification Report
The model achieved high accuracy across all classes (0–9).

| Metric | Value |
|--------|--------|
| Precision | 0.98 |
| Recall | 0.98 |
| F1-Score | 0.98 |
