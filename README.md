# MNIST Handwritten Digit Classification Using Neural Network

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-Neural%20Network-red)
![MNIST](https://img.shields.io/badge/Dataset-MNIST-green)

## 📌 Project Overview

This project implements a simple neural network using **TensorFlow/Keras** to classify handwritten digits from **0 to 9** using the MNIST dataset.

The project covers the complete machine learning workflow, including:

- Loading the MNIST dataset
- Dataset exploration
- Displaying sample handwritten images
- Data preprocessing and normalization
- Neural network design
- Model training
- Model evaluation
- Training and validation visualization
- Testing five handwritten images
- Actual vs predicted label comparison
- Neural network experiment
- Model performance comparison

---

## 🚀 Open Project in Google Colab

### 👉 [Open MNIST Project in Google Colab](https://colab.research.google.com/drive/1WRpOy1ZD91GfhJ7Y3eXEQeOAZ1sHtkvm?usp=sharing)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WRpOy1ZD91GfhJ7Y3eXEQeOAZ1sHtkvm?usp=sharing)

---

## 📊 Dataset

The **MNIST dataset** contains handwritten digit images from 0 to 9.

| Property | Value |
|---|---|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Image Size | 28 × 28 |
| Image Type | Grayscale |
| Number of Classes | 10 |
| Classes | 0–9 |

Each image contains 784 pixel values after flattening:

**28 × 28 = 784**

---

## 🧠 Neural Network Architecture

The original neural network consists of:

```text
Input Image
    ↓
28 × 28 Pixels
    ↓
Flatten
    ↓
Dense Layer - 128 Neurons
    ↓
Dropout - 20%
    ↓
Dense Layer - 64 Neurons
    ↓
Output Layer - 10 Neurons
    ↓
Digit Prediction (0–9)
