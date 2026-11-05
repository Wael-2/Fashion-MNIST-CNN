# Fashion-MNIST Classification with PyTorch

A small deep learning project focused on image classification using a Convolutional Neural Network (CNN).

The goal is to train a CNN to recognize different types of clothing from grayscale images.

## Dataset

The project uses the Fashion-MNIST dataset, which contains 70,000 images across 10 categories, including shirts, trousers, shoes and bags.

Each image has a resolution of 28 × 28 pixels.

## Implementation

The model was built using PyTorch and consists of:
- Two convolutional layers
- Two max-pooling layers
- Two fully connected layers
- ReLU activation functions

The training process includes data normalization, data augmentation and stochastic gradient descent (SGD).

## Results

The model was trained for 20 epochs.

- Training Accuracy: 87.95%
- Test Accuracy: 88.32%
- Training Loss: 0.3305
- Test Loss: 0.3200

## Technologies

Python, PyTorch, Torchvision, NumPy, Matplotlib
