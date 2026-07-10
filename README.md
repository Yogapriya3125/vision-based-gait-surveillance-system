# vision-based-gait-surveillance-system
Vision-based gait surveillance system that classifies normal and suspicious human activities from surveillance videos using Vision Transformer (ViT) feature extraction and XGBoost.
# Vision-Based Gait Surveillance System
<p align="center">
  <img src="images\Picture1.png" width="850">
</p>

## Overview

This project detects suspicious human activities from surveillance videos using gait analysis and deep learning.

The system extracts spatial features from video frames using Vision Transformer (ViT) and classifies activities into:

- Normal
- Suspicious

using an XGBoost classifier.

---
![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-Classifier-green)
![License](https://img.shields.io/badge/License-MIT-orange)
## Features

✔ Automatic video preprocessing

✔ Vision Transformer (ViT) feature extraction

✔ Binary classification

✔ Confusion Matrix

✔ Classification Report

✔ F1 Score

✔ Accuracy Evaluation

---

## Technologies

- Python
- OpenCV
- PyTorch
- Transformers
- Vision Transformer (ViT)
- XGBoost
- Scikit-learn

---

## Dataset

Video Dataset by Daud Shah (Kaggle)

Classes include

Normal Activities

- Walking
- Standing
- Sitting
- Meet
- Clapping

Suspicious Activities

- Fighting
- Robbery
- Assault
- Abuse
- Stealing

---

## Workflow

Dataset
↓

Frame Extraction

↓

Vision Transformer Feature Extraction

↓

Average Pooling

↓

XGBoost Classification

↓

Prediction

---

## Results

Test Accuracy : XX%

F1 Score : XX%

---

## Repository Structure

src/
models/
images/
results/
docs/

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python train.py
```

---

## Prediction

```python
predict_video("sample.mp4")
```

---

## Author

YOGAPRIYA B
