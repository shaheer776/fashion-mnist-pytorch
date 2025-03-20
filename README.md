# Fashion MNIST Classification with PyTorch

## Overview

This repository provides a PyTorch-based deep learning model for classifying images from the Fashion MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images, each belonging to one of 10 fashion categories.

## Features

- Data loading and preprocessing using `torchvision`
- Neural network implementation using `torch.nn`
- Training and evaluation scripts
- Visualization of results

## Requirements

Ensure you have the following installed:

- Python 3.x
- PyTorch
- Torchvision
- Matplotlib (for visualization)
- NumPy

Install dependencies using:

```sh
pip install torch torchvision matplotlib numpy
```

## Dataset

The Fashion MNIST dataset can be downloaded from Kaggle: [Fashion MNIST Dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist?select=fashion-mnist_test.csv). Alternatively, it will be automatically downloaded by `torchvision.datasets.FashionMNIST`. It consists of grayscale images (28x28 pixels) belonging to 10 classes:

1. **T-shirt/top**
2. **Trouser**
3. **Pullover**
4. **Dress**
5. **Coat**
6. **Sandal**
7. **Shirt**
8. **Sneaker**
9. **Bag**
10. **Ankle boot**

## **Usage**

### **Training the Model**

**Run the training script:**

```sh
python train.py
```

### **Evaluating the Model**

**Run the evaluation script:**

```sh
python evaluate.py
```

### **Visualizing Predictions**

**Run the visualization script:**

```sh
python visualize.py
```

## **File Structure**

```
├── fashion_mnist_pytorch/
│   ├── dataset/  # Folder containing dataset files
│   │   ├── fashion-mnist-train.csv  # Training dataset file
│   ├── train.py  # Training script
│   ├── evaluate.py  # Evaluation script
│   ├── visualize.py  # Visualization script
│   ├── README.md  # Project documentation
```

## **Acknowledgments**

- [**PyTorch Documentation**](https://pytorch.org/)
- [**Fashion MNIST Dataset**](https://github.com/zalandoresearch/fashion-mnist)

## **License**

**This project is licensed under the MIT License.**

