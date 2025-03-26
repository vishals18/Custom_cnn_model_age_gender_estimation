# 👶🧓 Age & Gender Estimation using Custom CNN & Transfer Learning

This repository contains my dual-approach project on predicting **Age** and classifying **Gender** from facial images. It includes:

- A **Custom CNN model** built from scratch
- A **Transfer Learning model** using VGG16

The project showcases the differences in performance, complexity, and flexibility between these two deep learning approaches.

---

## 📌 Project Overview

### 🎯 Objectives:
- 🔢 Predict **Age** (regression)
- 🚻 Classify **Gender** (binary classification)

### 🧪 Two Models Implemented:
1. **Model A:** Custom CNN architecture built from scratch
2. **Model B:** Fine-tuned VGG16 model (Transfer Learning)

Both models share a **dual-output structure**, meaning they learn to predict age and gender simultaneously.

---

## 🧠 Model Architecture

### 🧩 Custom CNN:
- Multiple Conv2D layers with ReLU and MaxPooling
- Batch Normalization & Dropout for regularization
- Dual output branches:
  - Age regression (linear activation)
  - Gender classification (sigmoid activation)

### 📦 Transfer Learning (VGG16):
- Pretrained VGG16 (ImageNet weights, no top)
- Custom dense layers stacked on top
- Fine-tuned final few layers
- Dual output branches (same as above)
