# 🔥 Fire Detection Using Transfer Learning (MobileNetV2)

This project uses **Transfer Learning** with a pre-trained **MobileNetV2** model to detect fire in images. It classifies input images as either "Fire" or "No Fire" with the help of custom top layers and a well-preprocessed dataset.

---

## 🧠 Model Overview

- **Base Model**: MobileNetV2 (pre-trained on ImageNet)
- **Custom Layers**:
  - GlobalAveragePooling2D
  - Dense + Dropout Layers
  - Softmax Output Layer (2 classes)
- **Framework**: TensorFlow / Keras
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam

---

## 📦 Dataset

- **Source**: [Fire Detection Dataset on Kaggle](https://www.kaggle.com/datasets/metinmekiabullrahman/fire-detection)
- **Structure**:
  - `Fire/` – Images containing fire
  - `NoFire/` – Images without fire
- Images are resized to 224x224 for model input.

---

## 🚀 How to Run

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
