# Artificial Neural Network - Fashion MNIST

This project implements a fully connected artificial neural network (ANN) using PyTorch, trained on the Fashion-MNIST dataset. The model's architecture and hyperparameters are optimized using Optuna to achieve high classification accuracy.

## 📚 Dataset

The model is trained on the Fashion-MNIST dataset, which consists of 28x28 grayscale images representing 10 different clothing categories:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## 🧠 Model Architecture

- **Input Layer:** 784 neurons (28x28 pixels flattened)
- **Hidden Layers:** Configurable via Optuna optimization
- **Activation Functions:** ReLU
- **Regularization:** Dropout and Batch Normalization
- **Output Layer:** 10 neurons (one per class)

## 🔧 Hyperparameter Optimization

Optuna is used to optimize the following hyperparameters:

- Number of hidden layers
- Neurons per layer
- Epochs
- Learning rate
- Dropout rate
- Batch size
- Optimizer type (Adam, SGD, RMSprop)
- Weight decay

## 🚀 Requirements

To run this project, install the required dependencies:

```bash
pip install -r requirements.txt
Clone the repository:
git clone https://github.com/wurb0/ArtificialNeuralNetwork.git
cd ArtificialNeuralNetwork
Open the Jupyter Notebook
Follow the instructions within the notebook to train and evaluate the model.

📈 Results

The notebook includes training and evaluation metrics, such as:

Training and test accuracy

Loss curves

Hyperparameter optimization results
