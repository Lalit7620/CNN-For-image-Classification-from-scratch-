# 🖼️ CIFAR-10 Image Classification using CNN (PyTorch)

A Convolutional Neural Network (CNN) built from scratch using **PyTorch** to classify images from the **CIFAR-10** dataset.

The project demonstrates the complete deep learning workflow including data preprocessing, CNN architecture design, model training, and evaluation.

---

## 📌 Project Overview

This project implements a custom CNN for multi-class image classification on the CIFAR-10 dataset.

The model consists of multiple convolutional blocks followed by fully connected layers for classification.

---

## 📂 Dataset

**Dataset:** CIFAR-10

- 60,000 RGB images
- Image Size: 32 × 32
- 10 Classes
- 50,000 Training Images
- 10,000 Test Images

Classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## 🧠 CNN Architecture

Input

```
32 × 32 × 3
```

Architecture

```
Conv2D (3 → 32)
↓
ReLU
↓
MaxPool (2×2)

Conv2D (32 → 64)
↓
ReLU
↓
MaxPool (2×2)

Conv2D (64 → 128)
↓
ReLU
↓
MaxPool (2×2)

Flatten

Linear (2048 → 256)

ReLU

Linear (256 → 10)
```

---

## ⚙️ Technologies Used

- Python
- PyTorch
- TorchVision
- NumPy
- Jupyter Notebook

---

## 📊 Model Training

Loss Function

- CrossEntropyLoss

Optimizer

- Adam Optimizer

Activation Function

- ReLU

Pooling

- Max Pooling (2×2)

Epochs

- 10

---

## 📈 Results

**Test Accuracy**

```
74.76%
```

Loss decreased consistently during training, indicating successful learning and convergence.

---

## 📁 Project Structure

```
├── Data/
├── CNN_for_CIFAR10.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/CIFAR10-CNN-PyTorch.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter lab
```

---

## 📚 Concepts Covered

- Convolutional Neural Networks (CNN)
- Convolution Layer
- ReLU Activation
- Max Pooling
- Feature Extraction
- Flatten Layer
- Fully Connected Layer
- Image Classification
- CrossEntropy Loss
- Adam Optimizer
- PyTorch DataLoader
- Model Evaluation

---

## 🎯 Future Improvements

- Data Augmentation
- Batch Normalization
- Dropout Regularization
- Learning Rate Scheduler
- Transfer Learning (ResNet, VGG)
- Hyperparameter Tuning
- Confusion Matrix Visualization

---

## 👨‍💻 Author

**Lalit Kumar Sahoo**

If you found this project helpful, feel free to ⭐ the repository.
