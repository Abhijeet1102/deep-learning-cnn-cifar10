# deep-learning-cnn-cifar10
CNN-based image classification project using PyTorch on CIFAR-10 dataset. Includes model training, evaluation, and performance analysis.

# 🧠 CNN CIFAR-10 Image Classification (PyTorch)

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the CIFAR-10 dataset into 10 different categories.

---

## 🚀 Features

* Built using PyTorch
* CNN architecture with Conv + ReLU + Pooling layers
* Training and testing pipeline
* Accuracy evaluation
* GPU support (optional)

---

## 🗂 Dataset

* Dataset: CIFAR-10
* 60,000 images (32x32)
* 10 classes (airplane, car, bird, cat, deer, dog, frog, horse, ship, truck)

---

## 🧱 Model Architecture

* Conv2D → ReLU → MaxPool
* Conv2D → ReLU → MaxPool
* Conv2D → ReLU → MaxPool
* Flatten
* Fully Connected Layers

---

## ⚙️ Installation

```bash
pip install torch torchvision
```

---

## ▶️ Run the Project

```bash
python your_file_name.py
```

---

## 📊 Results

* Achieved accuracy: ~70-80% (can be improved with tuning)

---

## 🔧 Future Improvements

* Add Dropout for regularization
* Use Data Augmentation
* Improve accuracy with deeper networks
* Hyperparameter tuning

---

## 👨‍💻 Author

**Abhijeet Rai**
