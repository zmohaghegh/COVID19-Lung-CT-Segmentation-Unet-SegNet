# COVID-19 Lung CT Image Segmentation: U-Net vs SegNet

This repository contains the implementation of a deep learning-based medical imaging system designed to detect, segment, and label infected lung tissues in COVID-19 CT scans. 
Medical Image Segmentation on COVID-19 CT scans comparing U-Net and SegNet architectures using TensorFlow/Keras

## 🌟 Key Highlights (From My Research)
- [cite_start]**High Accuracy:** Achieved a mean accuracy of **0.90 with SegNet** and **0.90 with U-Net**[cite: 56].
- [cite_start]**Robust Validation:** Implemented **Five-fold Cross-validation** to ensure model stability and generalizability across limited datasets[cite: 55].
- [cite_start]**Interpretability:** Utilized **Deep Dream** methods to visualize features extracted by the network and understand infection patterns[cite: 56].

## 🚀 Project Overview
[cite_start]The goal is to provide a reliable tool for clinicians to assess disease severity by separating infected areas from healthy lung tissue using automated segmentation[cite: 54].

## 🛠️ Architecture Details
- **U-Net:** Specialized for medical imaging with an encoder-decoder structure and skip connections.
- [cite_start]**SegNet:** Optimized for scene understanding, used here for multi-class infection severity detection[cite: 55].
- **Transfer Learning:** Leveraged pre-trained features to improve convergence on specialized medical data.

## 📊 Technical Features
- [cite_start]**Binary & Multi-class Segmentation:** Capable of differentiating between "Infected vs Healthy" and grading the severity of the infection[cite: 55].
- **Preprocessing:** Includes image normalization and noise reduction tailored for CT scans.
- [cite_start]**Feature Visualization:** Insights into what the "Encoder" part of the model sees using Deep Learning visualization techniques[cite: 56].

## 💻 Technical Stack
- **Framework:** TensorFlow / Keras
- **Libraries:** NumPy, Matplotlib, OpenCV
- **Concepts:** Convolutional Neural Networks (CNN), Encoder-Decoder Architectures, Computer Vision.

---
**Researcher:** Zahra Mohaghegh  
[cite_start]**Specialization:** M.Sc. in Artificial Intelligence & Robotics [cite: 29]
