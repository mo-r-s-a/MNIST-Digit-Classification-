# **MNIST Digit Classification**

This project is a deep learning-based application that classifies handwritten digits (0–9) using the MNIST dataset and a Convolutional Neural Network (CNN) model. The goal is to accurately predict digits from 28x28 grayscale images.

---

## 📊 Dataset

- **Source**: Built-in MNIST dataset from `tensorflow.keras.datasets`
- **Data Format**:
  - 60,000 training images
  - 10,000 test images
  - Grayscale 28x28 pixel handwritten digits
- **Classes**: 10 (Digits from 0 to 9)

---

## 🔁 Project Workflow

1. **Data Loading and Normalization**
2. **Label Encoding using One-Hot Encoding**
3. **Model Building with CNN (Conv2D, MaxPooling, Dropout, etc.)**
4. **Model Training & Evaluation**
5. **Classification Report & Accuracy Metrics**
6. *(Optional)* **Image Upload & Prediction** using PIL

---
## Model Gradio view




![Image](https://github.com/user-attachments/assets/80007fd6-f5f2-4a9a-9be3-9ffb37dbb6bd)




---
## 🏆 Results

- 🧠 **Best Performing Model**: Custom CNN
- ✅ **Achieved Accuracy**: Over **98%** on test data
- 📈 Model Evaluation:
  - Used `classification_report` from scikit-learn
  - Optimized with `Adam`
  - Loss Function: `CategoricalCrossentropy`

---

## 🧪 Requirements

To run this project, install the required libraries:

```bash
pip install tensorflow keras pillow scikit-learn matplotlib
