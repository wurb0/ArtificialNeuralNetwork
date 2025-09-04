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
.
├── fmnist_small.csv # Dataset (Fashion-MNIST subset)
├── ANN.py # Main training & Optuna code
├── requirements.txt # Dependencies
└── README.md # Project documentation

## ⚙️ Setup & Installation
```bash
# Clone repo
git clone https://github.com/your-username/ArtificialNeuralNetwork.git
cd ArtificialNeuralNetwork

# Create virtual environment (recommended)
python3 -m venv ann-env
source ann-env/bin/activate

# Install dependencies
pip install -r requirements.txt

▶️ Usage

Launch Jupyter and open the notebook:
jupyter notebook ANN_FashionMNIST.ipynb


