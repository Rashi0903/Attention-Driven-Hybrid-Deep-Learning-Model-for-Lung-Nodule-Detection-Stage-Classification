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
<img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/3c0cd514-dad8-4211-8abe-4b008742520c" />

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
```
---

## 🚀 Key Features
✅ Automated Lung Nodule Detection

✅ High-Accuracy Segmentation with U-Net + Attention

✅ Stage Classification (I to IV) with Hybrid CNNs

✅ Optimized for Real-Time Use

✅ End-to-End Deep Learning Pipeline

---
## 🖼️ Visualizations

🔄 Augmented CT Scan Samples
<img width="940" height="205" alt="image" src="https://github.com/user-attachments/assets/2b9fb961-ca11-465f-8a4b-02580485d54e" />

📦 YOLOv5 Bounding Boxes
<img width="685" height="350" alt="image" src="https://github.com/user-attachments/assets/05de4b31-5f70-413f-a34a-c8e51834b1b0" />

📈 Confusion Matrix for Classification
<img width="940" height="874" alt="image" src="https://github.com/user-attachments/assets/c3af61a3-92c4-4644-be0d-2613c575e21a" />

📍 Cancerous Region Overlays with Stage Labels
<img width="940" height="323" alt="image" src="https://github.com/user-attachments/assets/c268f243-26dc-4ee7-8851-756b7ac73299" />
<img width="940" height="326" alt="image" src="https://github.com/user-attachments/assets/b1d51d82-1c15-4826-a813-93c60bbc93b0" />

---

## 📊 Results & Performance

| **Metric**                | **Score**                        |
|---------------------------|----------------------------------|
| Stage Classification      | 95.6%                            |
| F1 Score                  | 0.97                             |
| Segmentation Accuracy     | High IoU & Dice Coefficient      |
| Detection Speed           | Fast Inference (YOLOv5)          |

> 💡 **Note:** Model performs robustly even on **low-contrast**, **noisy**, or **complex** CT scans.

