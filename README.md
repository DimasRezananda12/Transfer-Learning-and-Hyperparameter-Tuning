# Transfer-Learning-and-Hyperparameter-Tuning
CIFAR-10 Image Classification: Simple CNN vs Transfer Learning
This project compares two different approaches to image classification using the CIFAR-10 dataset: building a simple CNN architecture from scratch and using transfer learning with the ResNet-18 model.

## Key Features
- Data Preprocessing: Resizing to 224x224 and standard ImageNet normalization.
- Simple CNN: Custom architecture with convolution layers, ReLU, and MaxPool.
- Transfer Learning: Using ResNet-18 (pre-trained weights) with feature extraction techniques (freezing early layers).
- Optimization: Using Adam Optimizer and CrossEntropy Loss Function.

## Technologies Used
- Python
- PyTorch & Torchvision
- Matplotlib & NumPy
- Google Colab

## Experiment Results
This script will train both models for 5 epochs and provide accuracy output on the test set to see a comparison of performance between the custom model and the pre-trained model.
