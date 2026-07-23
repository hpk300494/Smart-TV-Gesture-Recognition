# Smart TV Gesture Recognition

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Computer%20Vision-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Project Overview

This project develops a deep learning-based gesture recognition system for Smart TVs. The model recognizes five hand gestures captured through webcam video sequences, enabling users to control television functions without a remote.

The project was completed as part of the **PG Diploma in Machine Learning and AI (IIIT Bangalore & upGrad)**.

---

## Problem Statement

The objective is to classify video sequences into one of five gestures:

| Gesture | Action |
|----------|--------|
| 👍 Thumbs Up | Increase Volume |
| 👎 Thumbs Down | Decrease Volume |
| 👈 Left Swipe | Jump Backward |
| 👉 Right Swipe | Jump Forward |
| ✋ Stop | Pause Video |

---

## Dataset

- Training videos
- Validation videos
- Each video contains **30 RGB frames**
- Five gesture classes
- Images of varying resolutions
- Preprocessing includes:
  - Cropping
  - Resizing
  - Normalization
  - Batch generation using a custom generator

---

## Deep Learning Architectures

The project evaluates multiple approaches:

- Conv3D Networks
- CNN + RNN (LSTM/GRU)
- Transfer Learning
- MobileNet Feature Extractor
- Data Augmentation
- Early Stopping
- Batch Normalization
- Dropout

---

## Project Structure

```
Smart-TV-Gesture-Recognition/
│
├── notebooks/
│   └── gesture_recognition.ipynb
│
├── models/
│   └── gesture_recognition_model.h5
│
├── reports/
│   └── gesture_recognition_writeup.docx
│
├── images/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- SciPy

---

## Model Training

The workflow includes:

1. Custom Data Generator
2. Image Preprocessing
3. Batch Generation
4. Model Training
5. Validation
6. Hyperparameter Tuning
7. Performance Evaluation

---

## Results

The final model achieved approximately:

- Training Accuracy: **86%**
- Validation Accuracy: **68%**

---

## Future Improvements

- Vision Transformers
- EfficientNet Backbone
- Attention Mechanisms
- ConvLSTM Networks
- Larger Dataset
- Hyperparameter Optimization

---

## Repository Contents

- Deep Learning Notebook
- Trained Model (.h5)
- Project Report
- Documentation

---

## Author

**Hanaa Parvez Khan**

Machine Learning • Deep Learning • Computer Vision • Data Science

GitHub: https://github.com/hpk300494
