# Lightweight CNN for CIFAR-10 Classification

Image classification on CIFAR-10 using a LightWeight Convolutional Neural Network, with comparison against classical ML models and ResNet18 transfer learning.

---

## Overview

This project implements a **lightweight CNN (~666K parameters)** which is both efficient and fast-performing. The implemented model is compared against standard ML models:

* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest
* ResNet18 (Transfer Learning)

The results demonstrate the effectiveness of CNNs in learning spatial visual features.

---

## Model Summary

* Input: 32×32 RGB images
* 5 Convolution layers (3 blocks)
* ReLU activation + MaxPooling
* Dropout (0.5) for regularization
* Fully connected classifier
* Parameters: ~666,000

Designed for **speed, memory efficiency and efficient learning**.

---

## Results

| Model                          | Test Accuracy |
| ------------------------------ | ------------- |
| KNN                            | 28.97%        |
| SVM                            | 32.44%        |
| Random Forest                  | 42.16%        |
| **Lightweight CNN (Proposed)** | **77.59%**    |
| ResNet18                       | 89.27%        |

**CNN improves accuracy by +35% over classical ML models like KNN,SVM and Random Forest**

---

## Training Details

* Optimizer: Adam
* Learning Rate: 0.001
* Batch Size: 64
* Epochs: 10
* Hardware: NVIDIA T4 GPU
* Training Time: ~4 minutes

---

## Key Highlights

* Lightweight CNN with only ~666K parameters
* 77.59% accuracy on CIFAR-10
* Fast training (~4 minutes)
* Efficient alternative to large deep networks
* Comparison with classical ML and ResNet18

---

## Authors

**Sree Krishna S**
Sri Sivasubramaniya Nadar College of Engineering

**Sujith M**
Sri Sivasubramaniya Nadar College of Engineering

---

## References

* Krizhevsky, 2009 — CIFAR-10 Dataset
* He et al., 2016 — ResNet

---

This project shows that **well-designed lightweight CNNs can achieve strong performance with minimal computational cost**, making them suitable for real-world deployment.
