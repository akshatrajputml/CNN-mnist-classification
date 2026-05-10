# CNN MNIST Digit Classification

## Overview
This project uses a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset.  
The model is trained using Deep Learning techniques and can accurately recognize digits from 0–9.

---

# Problem Statement
Handwritten digit recognition is an important computer vision problem used in:
- Bank cheque processing
- Postal code recognition
- Digitized form reading
- OCR systems

The goal of this project is to build a CNN model that can correctly classify handwritten digits.

---

# Dataset
The project uses the famous **MNIST Dataset** containing:
- 60,000 grayscale images
- Image size: 28x28 pixels
- 10 classes (digits 0–9)

Dataset Source:
- Built into TensorFlow/Keras datasets

---

# Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

---

# Project Workflow

1. Load MNIST Dataset
2. Data Preprocessing
3. Normalize Pixel Values
4. Reshape Images
5. Build CNN Model
6. Train Model
7. Evaluate Accuracy
8. Predict Handwritten Digits

---

# CNN Architecture

The model contains:
- Convolution Layers
- Max Pooling Layers
- Dropout Layers
- Fully Connected Dense Layers
- Softmax Output Layer

---

# Model Performance

| Training Accuracy | 99% |
| Testing Accuracy | 98% |

---

# Sample Output

The model successfully predicts handwritten digits.

