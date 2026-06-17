<div align="center">

# 🧠 ANN-Powered Medical Imaging: Brain Tumor Classification

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-red?style=for-the-badge&logo=keras" />
  <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-green?style=for-the-badge&logo=opencv" />
</p>

<p>
  <strong>Automated Brain Tumor Detection and Classification using Artificial Neural Networks (ANN)</strong>
</p>

</div>

---

## 📖 Overview

Brain tumors are among the most critical neurological disorders, requiring accurate and timely diagnosis for effective treatment. Traditional MRI scan analysis relies heavily on radiologists and can be time-consuming, subjective, and prone to human error.

This project leverages **Artificial Neural Networks (ANNs)** to classify brain tumors from MRI images, providing an automated decision-support system that assists medical professionals in identifying tumor types with high accuracy.

---

## 🎯 Problem Statement

Manual classification of brain tumors from MRI scans presents several challenges:

<ul>
  <li>⏳ Time-consuming diagnostic process</li>
  <li>👨‍⚕️ Dependence on expert radiologists</li>
  <li>⚠️ Potential for human error and misclassification</li>
  <li>🌍 Limited access to specialists in remote regions</li>
  <li>🏥 Delays in treatment due to slow diagnosis</li>
</ul>

An intelligent and automated classification system is needed to improve diagnostic efficiency and accuracy.

---

## 💡 Proposed Solution

The proposed solution uses an **Artificial Neural Network (ANN)** to analyze MRI brain images and classify tumors into different categories.

### 🔄 Workflow

```text
MRI Image Acquisition
        ↓
Image Preprocessing
        ↓
Feature Extraction
        ↓
ANN Training
        ↓
Tumor Classification
        ↓
Performance Evaluation
```

The system acts as a decision-support tool for healthcare professionals, enabling faster and more reliable diagnosis.

---

## 📂 Dataset Description

### 📌 Source

Public MRI Brain Tumor datasets from Kaggle and other open medical imaging repositories.

### 🧬 Tumor Categories

| Category        | Description                       |
| --------------- | --------------------------------- |
| Glioma          | Tumor originating in brain tissue |
| Meningioma      | Tumor arising from meninges       |
| Pituitary Tumor | Tumor affecting pituitary gland   |
| No Tumor        | Healthy MRI scans                 |

### 🛠️ Preprocessing Steps

* Image Resizing
* Normalization
* Noise Reduction
* Tumor Region Segmentation
* Data Augmentation *(Optional)*
* Train-Test Split *(80:20)*

---

## 🧠 Model Architecture

### ANN Structure

| Layer          | Configuration              |
| -------------- | -------------------------- |
| Input Layer    | Flattened MRI Image Pixels |
| Hidden Layer 1 | 512 Neurons (ReLU)         |
| Hidden Layer 2 | 256 Neurons (ReLU)         |
| Hidden Layer 3 | 128 Neurons (ReLU)         |
| Dropout        | 0.3 - 0.5                  |
| Output Layer   | Softmax Activation         |

### ⚙️ Hyperparameters

| Parameter     | Value                     |
| ------------- | ------------------------- |
| Optimizer     | Adam                      |
| Learning Rate | 0.001                     |
| Epochs        | 50 - 100                  |
| Batch Size    | 32 - 64                   |
| Loss Function | Categorical Cross-Entropy |

---

## ⚙️ Implementation Details

### 🛠️ Technologies Used

<p>
Python • TensorFlow • Keras • NumPy • Pandas • Matplotlib • OpenCV • Scikit-Learn
</p>

### 🚀 Training Process

1. Load MRI Image Dataset
2. Perform Preprocessing
3. Build ANN Architecture
4. Compile Model
5. Train Using Training Dataset
6. Validate Using Testing Dataset
7. Evaluate Performance Metrics

### 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📊 Results

The ANN model demonstrates strong performance in classifying brain tumors from MRI scans.

### Expected Outcomes

✅ High Classification Accuracy
✅ Faster Diagnosis Support
✅ Reduced Human Error
✅ Improved Clinical Decision-Making

---

## 🚀 Future Enhancements

* Implement Convolutional Neural Networks (CNNs)
* Apply Transfer Learning Techniques
* Real-Time MRI Image Analysis
* Cloud Deployment for Hospital Access
* Integration with Healthcare Information Systems

---

## 🏥 Applications

| Domain              | Application                       |
| ------------------- | --------------------------------- |
| Hospitals           | Tumor Detection & Diagnosis       |
| Research Institutes | Medical Imaging Studies           |
| Telemedicine        | Remote Consultation Support       |
| Healthcare AI       | Clinical Decision Support Systems |

---

<div align="center">

### 🌟 Advancing Medical Imaging with Artificial Intelligence

*Combining ANN-based classification with MRI imaging to support faster, smarter, and more accurate healthcare decisions.*

</div>
