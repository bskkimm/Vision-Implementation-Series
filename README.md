# 📚 From Paper to Code: Implementations of Key Computer Vision Papers from Scratch

Welcome to my computer vision model implementation series!  
This repository serves as a central hub for my **Computer Vision Implementation Series** of legendary computer vision models.



---

## 🚀 Introduction

This repository briefly introduces my **Computer Vision Implementation Series**, where I faithfully reimplement influential papers to gain hands-on, in-depth understanding of the techniques driving modern visual AI systems.

---

## 🎯 Motivation

The purpose of this project is twofold:

1. **Develop Practical Proficiency**: To gain end-to-end experience in building deep learning pipelines — from data preparation to training, inference, and deployment — in the domain of computer vision.
2. **Build Foundational Understanding**: To deeply understand the core architectural paradigms of modern vision models, such as **Convolutional Neural Networks (CNNs)** and **Transformers**.

---

## 🔁 Workflow

Each implementation follows a consistent and rigorous pipeline:

![image](https://github.com/user-attachments/assets/c0bb7f29-2b8b-474e-8ce6-7a8fcc2cdee1)

1. **Paper Reading & Understanding**  
   Analyze the original research paper to understand the theoretical backbone of the model.

2. **Data Preparation**  
   Prepare the dataset according to the specific requirements of the model.

3. **Model Building**  
   Implement the architecture from scratch using PyTorch.

4. **Training & Experimentation**  
   Train the model, tune hyperparameters, and analyze performance metrics.

5. **Inference & Deployment**  
   Evaluate the model with test samples and explore basic deployment options.

---

## 🧠 Implemented Models

### 📌 YOLOv1 – You Only Look Once (v1)  
🔗 [GitHub Repository](https://github.com/bskkimm/YOLOv1-from-Scratch) | [Medium Article](https://medium.com/@bskkim2022/yolo-v1-implementation-from-scratch-using-pytorch-d7fa95ff06ea)

YOLOv1 is a real-time object detection model that reframes detection as a single regression problem, directly predicting class probabilities and bounding boxes from full images in one evaluation. It introduced a new paradigm compared to two-stage detectors like R-CNN.

---

### 📌 ViT – Vision Transformer
🔗 [GitHub Repository](https://github.com/bskkimm/ViT-from-Scratch) | [Medium Article](https://medium.com/@bskkim2022/paper-reimplementation-vit-vision-transformer-eed3ad20dfe7)

ViT replaces convolutional layers with pure transformer blocks. It splits the image into patches, flattens them, and feeds them into a standard transformer architecture, achieving state-of-the-art performance with sufficient data.


---

### 📌 DETR – Detection TRansformer
🔗 [GitHub Repository](https://github.com/bskkimm/DETR-from-Scratch) | [Medium Article](https://medium.com/@bskkim2022/detr-implementation-from-scratch-using-pytorch-0f783fe06363)

DETR is a novel object detection model that unifies detection with transformers and bipartite matching. It eliminates the need for many hand-crafted components like anchor boxes or NMS, making detection elegantly simple.

---

### 📌 DETR3D – 3D Object Detection Transformer
🔗 [GitHub Repository](https://github.com/bskkimm/DETR3D-from-Scratch) |
[Medium Article](https://medium.com/@bskkim2022/detr3d-from-scratch-in-pytorch-from-multi-camera-images-to-3d-boxes-0342a1493c23)

DETR3D extends DETR-style object queries to multi-camera 3D object detection, using image features and camera geometry to predict 3D bounding boxes without explicit bird's-eye-view feature construction.

---

### 📌 BEVFormer – Bird's-Eye-View Transformer
🔗 [GitHub Repository](https://github.com/bskkimm/BevFormer_from_scratch)

BEVFormer learns a bird's-eye-view representation from multi-camera images using spatiotemporal transformers. It combines spatial cross-attention across camera views with temporal self-attention across frames to predict 3D bounding boxes, implemented from scratch in PyTorch.

---

## 🤝 Contribution

This is a solo learning project, but feel free to:
- Star ⭐ the repos
- Open issues for suggestions
- Fork and experiment
