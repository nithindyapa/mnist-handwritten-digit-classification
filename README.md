# MNIST Handwritten Digit Classification using PyTorch

## Project Overview
This project implements a Multi-Layer Perceptron (MLP) using PyTorch to classify handwritten digits from the MNIST dataset.

## Dataset
- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- 10 classes (digits 0–9)

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

## Model Architecture
The neural network consists of:
- Input layer: 784 neurons
- Hidden layer 1: 128 neurons (ReLU)
- Hidden layer 2: 64 neurons (ReLU)
- Output layer: 10 neurons

## Training Configuration
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Learning Rate: 0.001
- Batch Size: 64
- Epochs: 5

## Model Evaluation
The trained model is evaluated using test accuracy on unseen MNIST test images.

**Test Accuracy:** Add your actual test accuracy here.

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install PyTorch and Torchvision if needed.
3. Run all cells sequentially.
4. The MNIST dataset will be downloaded automatically.

## Key Concepts
- Neural Networks and MLP
- Forward Propagation
- Backpropagation
- PyTorch Autograd
- Model Training and Evaluation
