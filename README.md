# 🧠 Handwritten Digit Recognition using MLP (PyTorch)

An end-to-end Deep Learning project that classifies handwritten digits (0-9) from the famous **MNIST dataset** using a Multi-Layer Perceptron (MLP).

## 🚀 Project Overview
This project demonstrates the fundamental concepts of Deep Learning, including:
- **Data Preprocessing:** Normalizing and flattening image tensors.
- **Architecture:** Building a 3-layer neural network with Dropout.
- **Optimization:** Using Adam optimizer and Cross-Entropy Loss.
- **Evaluation:** Measuring performance on unseen test data.

## 🏗️ Model Architecture
The network is built with the following layers:
1. **Input Layer:** 784 neurons (28x28 flattened pixels).
2. **Hidden Layer 1:** 128 neurons with **ReLU** activation.
3. **Dropout Layer:** 20% probability to prevent overfitting.
4. **Hidden Layer 2:** 64 neurons with **ReLU** activation.
5. **Output Layer:** 10 neurons (representing digits 0-9).



## 📊 Performance
After training for 5 epochs, the model achieves:
- **Training Accuracy:** ~98.5%
- **Test Accuracy:** ~97.8%

## 🛠️ How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SoheilAbdollahii/mnist-mlp-pytorch.git](https://github.com/SoheilAbdollahii/mnist-mlp-pytorch.git)
   cd mnist-mlp-pytorch
