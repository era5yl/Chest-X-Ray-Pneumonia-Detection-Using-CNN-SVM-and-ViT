# Chest X-Ray Pneumonia Detection Using CNN, SVM, and ViT

This repository contains the full implementation of a pneumonia detection system using **Convolutional Neural Networks (CNN)**, **Support Vector Machines (SVM)** with CNN feature extraction, and **Vision Transformers (ViT)**.  
The goal of the project is to compare traditional machine learning and modern deep learning approaches for classifying chest X-ray images into **NORMAL** or **PNEUMONIA**.

---

##  Project Overview

Pneumonia is a major cause of respiratory illness, and early detection is crucial for effective clinical diagnosis.  
This project explores three different classification approaches:

- **CNN**: End-to-end deep learning model trained on chest X-ray images  
- **SVM**: Classical ML model trained on CNN-extracted features  
- **ViT**: A state-of-the-art Vision Transformer fine-tuned on the dataset  

The dataset is **balanced**, **stratified**, and split into **70% train**, **15% validation**, and **15% test** to ensure fair and clinically meaningful evaluation.

---

##  Dataset

The dataset used in this project is the **Chest X-Ray Pneumonia Dataset** from Kaggle:

 https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Dataset Processing

The original dataset is **highly imbalanced**.  
We therefore:

1. Merged training, validation, and test sets  
2. Balanced the dataset by undersampling pneumonia cases to match normal cases  
3. Created a **stratified 70/15/15 split**  

---
## Full information can be found in attached report

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/era5yl/Chest-X-Ray-Pneumonia-Detection-Using-CNN-SVM-and-ViT.git
cd Chest-X-Ray-Pneumonia-Detection-Using-CNN-SVM-and-ViT

