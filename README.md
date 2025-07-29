# 🧠 Attention-Driven Hybrid Deep Learning Model for Lung Nodule Detection & Stage Classification

## 🎯 Objective  
To build an AI-powered deep learning pipeline for automated lung **nodule detection**, **segmentation**, and **stage classification** (Stage I–IV) from CT scan images — assisting radiologists with **faster** and **more accurate** diagnosis of lung cancer.

---

## 🏗️ Architecture Overview

This project leverages a powerful combination of state-of-the-art models and attention mechanisms:

- 🔍 **YOLOv5** — For accurate lung nodule **detection**
- 🩻 **U-Net (with Attention)** — For precise **segmentation**
- 🧠 **EfficientNet + MobileNet Hybrid** — For accurate **stage classification**
- 🧲 **Attention Modules** — To boost feature learning and contextual awareness

---

## ⚙️ Workflow

```text
1. Data Preprocessing  
   ├─ Denoising  
   ├─ Resizing  
   ├─ Normalization  
   └─ Data Augmentation  

2. Detection  
   └─ YOLOv5 for Bounding Box Localization  

3. Segmentation  
   └─ Attention-Driven U-Net for Precise Masking  

4. Classification  
   └─ Hybrid of EfficientNet + MobileNet  

5. Evaluation  
   ├─ Accuracy  
   ├─ Precision & Recall  
   ├─ F1-Score  
   ├─ IoU (Intersection over Union)  
   └─ Dice Coefficient  

🚀 Key Features
✅ Automated Lung Nodule Detection

✅ High-Accuracy Segmentation with U-Net + Attention

✅ Stage Classification (I to IV) with Hybrid CNNs

✅ Optimized for Real-Time Use

✅ End-to-End Deep Learning Pipeline

