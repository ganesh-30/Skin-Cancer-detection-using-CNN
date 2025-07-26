# 🧠 Skin Cancer Detection using CNN | Multi-Class Image Classification

![Skin Cancer Banner](https://user-images.githubusercontent.com/your-image.png) 

## 📌 Overview

This project focuses on detecting **Skin Cancer** using deep learning by classifying dermatoscopic images into **one of nine possible classes**. The model is trained and evaluated on the publicly available **((https://www.kaggle.com/datasets/jaiahuja/skin-cancer-detection)) dataset**. The goal is to assist dermatologists and health professionals with an AI-based tool for early and accurate skin lesion classification.

---

## 🔍 Problem Statement

Skin cancer is one of the most common types of cancer globally. Early and accurate classification of skin lesions can significantly improve treatment success. This model takes an image as input and classifies it into one of the following **9 classes**:

-Actinic keratosis
-Basal cell carcinoma
-Dermatofibroma
-Melanoma
-Nevus
-Pigmented benign keratosis
-Seborrheic keratosis
-Squamous cell carcinoma
-Vascular lesion

---

## 🧠 Model Architecture

The project uses a **Convolutional Neural Network (CNN)** architecture trained from transfer learning VGG16.

Key features:
- Image preprocessing and augmentation
- Class imbalance handling
- Evaluation metrics: Accuracy, Confusion Matrix

---

## 📈 Results


|----------------|-----------|
| Accuracy       | **62.61%** |


> 📢 Among all Kaggle notebooks using the same dataset, this notebook achieves the **One of the best public leaderboard score** on multiclass classification.


## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/skin-cancer-detector.git
   cd skin-cancer-detector
