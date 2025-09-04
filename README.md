# Artificial Neural Network - Fashion MNIST

A **PyTorch** based fully connected **Artificial Neural Network (ANN)** trained on the [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset.  
The project includes **automated hyperparameter optimization** using **Optuna** to maximize model accuracy.

---

## 📌 Features
- Fully connected feedforward neural network (`nn.Linear` layers with BatchNorm, ReLU, and Dropout).
- Trained on **Fashion-MNIST** (grayscale 28×28 clothing images, 10 classes).
- Hyperparameter search with **Optuna**:
  - Hidden layers
  - Neurons per layer
  - Epochs
  - Learning rate
  - Dropout rate
  - Batch size
  - Optimizer type (Adam, SGD, RMSprop)
  - Weight decay
- Device-aware (CPU, CUDA GPU, or Apple MPS if available).

---

## 📂 Project Structure
