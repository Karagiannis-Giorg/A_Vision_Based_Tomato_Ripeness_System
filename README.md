# 🍅 Tomato Ripeness Detection for Smart Fridges

An AI-powered system for intelligent fruit monitoring, featuring deep learning models and custom datasets to classify tomatoes based on ripeness stages inside a smart fridge.

---

## 📘 Overview

This project explores a novel approach to **reducing food waste** by integrating **Computer Vision** and **Deep Learning** into smart refrigerator systems.

The system is designed to:
- Detect and classify various fruits.
- Estimate the ripeness stage of detected tomatoes.
- Simulate the core functions of a smart fridge.

It leverages two state-of-the-art object detection models: **YOLOv11** and **Faster R-CNN**.

---

## 🧠 Models Used

- **YOLOv11** – Real-time fruit detection and tomato classification.
- **Faster R-CNN** – High-accuracy ripeness detection.

Both models were trained on **custom-curated datasets**, collected and augmented using Roboflow.

---

## 📂 Dataset

Two custom datasets were created:

1. **Fruit Recognition Dataset**  
   - Fruits: Tomato, Apple, Banana, Pear, Peach, Pomegranate, etc.

2. **Tomato Ripeness Detection Dataset**  
   - Labels: `Unripe`, `Half-ripe`, `Ripe`, `Overripe`

Datasets were annotated and preprocessed for optimal performance using augmentation techniques and bounding box labeling.

Link for the Dataset: [Click Here!](https://app.roboflow.com/realistic-datasets-for-smart-fridge-applications)

---

## 🖥️ System Architecture

- Python 3.x
- PyTorch / TensorFlow
- Roboflow API for dataset generation
- GUI prototype for fridge simulation

---

## 🧊 Smart Fridge Simulation

The smart fridge prototype performs:
- Real-time detection of stored tomatoes
- Ripeness level alerts
- Inventory management recommendations

---
