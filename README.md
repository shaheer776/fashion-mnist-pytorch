# Fashion MNIST Classification with PyTorch

## Overview

This repository provides a PyTorch-based deep learning model for classifying images from the Fashion MNIST dataset. The dataset consists of 60,000 images belonging to one of 10 fashion categories.

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

The Fashion MNIST dataset can be downloaded from Kaggle: [Fashion MNIST Dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist?select=fashion-mnist_test.csv). It consists of grayscale images (28x28 pixels) belonging to 10 classes:

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

## **Model Architecture**

![NN_page-0001](https://github.com/user-attachments/assets/0030ed22-a72e-4241-8984-8af3fa9b27d6)



## **Operations Performed**

- Required modules are imported
- Set the device to GPU (if available) and set manual seed
- Visualize the Dataset to observe to get the overview
- The dataset is split between train and test set
- Creation of Dataloaders
- Defining of model architecture
- Setting up of Hyperparameters
- Training of model
- Evaluation of model
- Optimizing the model through addition of batch norm, dropout, and L2 regularization to reduce overfitting
- Plotting Loss curve

  
```
├── fashion_mnist_pytorch/
│   ├── fashion-mnist-pytorch.ipynb  # Training jupyter notebook file
│   ├── README.md  # Project documentation
```

## **Acknowledgments**

- [**PyTorch Documentation**](https://pytorch.org/)
- [**Fashion MNIST Dataset**](https://github.com/zalandoresearch/fashion-mnist)

## **License**

**This project is licensed under the MIT License.**

