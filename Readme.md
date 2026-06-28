# 🌱 Lightweight Deep Learning Framework for Crop Disease Detection

## 📌 Overview

Crop diseases pose a major challenge to agricultural productivity, food security, and sustainable farming. This project presents an **uncertainty-aware lightweight deep learning framework** for automated crop disease detection from leaf images. The framework is designed for **real-time inference** and optimized for **mobile and edge devices**, enabling practical deployment in resource-constrained agricultural environments.

The project systematically compares multiple lightweight CNN architectures and enhances their performance using **Bayesian MC-Dropout** and **CBAM (Convolutional Block Attention Module)** to improve prediction reliability, robustness, and feature representation.

This work has resulted in an **accepted IEEE conference publication** at **ICSCCC 2026**.

---

# 🚀 Key Features

* 🌿 Automated crop disease detection from leaf images
* 🧠 Comparison of multiple lightweight CNN architectures
* 📈 Bayesian MC-Dropout for uncertainty-aware predictions
* 🎯 CBAM Attention Module for enhanced feature extraction
* 📱 Optimized for mobile, edge, and real-time deployment
* 📊 Comprehensive evaluation using multiple classification metrics

---

# 🧠 Models Implemented

The following pretrained models were fine-tuned and evaluated using transfer learning:

* **SqueezeNet**
* **MobileNetV2**
* **EfficientNet-B0**

Enhancements:

* Bayesian MC-Dropout
* CBAM Attention Module
* Transfer Learning
* Hyperparameter Tuning
* Data Augmentation

---

# 📊 Results

* ✅ Achieved up to **98.11% classification accuracy**
* 🚀 Improved accuracy by **10–13%** after integrating Bayesian MC-Dropout and CBAM
* 📉 Reduced overfitting and improved model generalization
* 🎯 Enhanced prediction reliability through uncertainty estimation
* 📱 Lightweight models suitable for deployment on edge and mobile devices

---

# 🛠 Tech Stack

### Programming Language

* Python

### Deep Learning Frameworks

* PyTorch
* Torchvision

### Models

* SqueezeNet
* MobileNetV2
* EfficientNet-B0

### Computer Vision & Deep Learning

* Transfer Learning
* Bayesian MC-Dropout
* CBAM Attention Module

### Libraries

* OpenCV
* NumPy
* Scikit-learn

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Specificity
* Confusion Matrix

---

# 📁 Dataset

The framework was trained and evaluated using:

* **PlantVillage Dataset**
* **New Plant Diseases Dataset (Augmented)**

The datasets contain thousands of labeled crop leaf images covering multiple disease categories and healthy plant classes. Data preprocessing included image resizing, normalization, and augmentation to improve model generalization.

---

# 📈 Model Evaluation

Performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Specificity
* Confusion Matrix
* Class-wise Performance Analysis

The comparative analysis focuses on both classification performance and computational efficiency for deployment on low-resource devices.

---

# 📚 Research Contribution

This project introduces an uncertainty-aware lightweight framework by combining:

* Lightweight CNN architectures
* Bayesian Deep Learning
* Attention Mechanisms

The resulting work has been accepted for publication at:

**2026 IEEE Fourth International Conference on Secure Cyber Computing and Communication (ICSCCC)**

**Paper:** *A Comparative Study of Lightweight Deep Learning Frameworks for Plant Disease Detection*

---

# 🔮 Future Scope

* 📱 Deploy models on Android, iOS, and edge devices
* 🤖 Integrate Agentic AI for intelligent agricultural assistance
* 🌾 Estimate disease severity and recommend treatments
* 🚁 Enable drone-based crop monitoring
* 🌐 Integrate IoT sensors for smart farming ecosystems
* ☁️ Deploy as a scalable cloud-based web service

---

# 👨‍💻 Authors
* Dr. Jaspal Kaur Saini
* Ishaan Jain
* Khushi Mittal
* Namratha Reddy

