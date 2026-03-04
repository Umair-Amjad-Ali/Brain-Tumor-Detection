# Advanced 3D Brain Tumor Detection and Segmentation using Hybrid Deep Learning

## 📌 Project Overview
This research-oriented project focuses on the automated detection and segmentation of brain tumors from MRI scans. By combining **ResNet-50** for robust classification and **Res U-Net** for precise pixel-level segmentation, the system provides a dual-stage diagnostic tool for clinical decision support.

## 🚀 Live Demo (View Only)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XqiMFu_lvB1ND1E7C-hns-VaaTaDNyut?usp=sharing)
*Click the badge above to view the full implementation, training logs, and 98.09% accuracy results in Google Colab.*

## 📊 Key Performance Results
* **Classification Accuracy**: 98.09%
* **Precision**: 97.4%
* **Recall/Sensitivity**: 98.7%
* **Dice Coefficient**: High-fidelity mask generation for tumor localization.

## 💻 Development Environment
This project was developed and trained entirely on **Google Colab** to leverage its high-performance computing resources.
* **Hardware**: Utilized the **NVIDIA T4 GPU** with 16GB VRAM.
* **Compute**: Cloud-based environment optimized for handling large MRI datasets and deep architectures.

## 🧠 Methodology
1.  **Preprocessing**: Applied **CLAHE** (Contrast Limited Adaptive Histogram Equalization) and normalization to enhance tumor boundaries in low-contrast MRI slices.
2.  **Classification Path**: Utilized **Transfer Learning** with a pre-trained **ResNet-50** backbone for malignancy identification.
3.  **Segmentation Path**: Implemented a **Res U-Net** architecture to map the exact spatial extent of the tumor, overcoming the vanishing gradient problem.

---
**Author**: Umair Amjad  
*BS Software Engineering | The Islamia University of Bahawalpur*
