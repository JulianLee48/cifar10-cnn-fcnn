# CIFAR-10 CNN vs FCNN Comparison

This project compares the performance of a **Fully Connected Neural Network (FCNN)** and a **Convolutional Neural Network (CNN)** on the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) using **PyTorch**.

---

## 📓 View the Notebook
You can view the fully rendered notebook here:  
[**Open in nbviewer**](https://nbviewer.org/github/JulianLee48/cifar10-cnn-fcnn/blob/main/cifar10_comparison.ipynb)

---

## 🚀 Project Overview
- **Dataset**: CIFAR-10 (60,000 images, 10 classes)
- **Models Compared**:
  - **Fully Connected Neural Network (FCNN)**
  - **Convolutional Neural Network (CNN)**
- **Framework**: PyTorch  
- **Goal**: Evaluate the impact of convolutional layers on image classification accuracy.

---

## 📊 Results Summary
| Model | Accuracy | Avg Loss |
|-------|----------|----------|
| FCNN  | ~48%     | ~1.48    |
| CNN   | ~71%     | ~0.88    |

CNN significantly outperforms FCNN due to its ability to extract spatial features.

---

## 🛠️ Tech Stack
- Python 3
- PyTorch
- Matplotlib
- NumPy

---
