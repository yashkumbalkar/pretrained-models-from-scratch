# Pre-trained Models Implementation

This repository contains implementations of several popular deep learning models from scratch, including **AlexNet**, **VGG16**, **ResNet**, and **InceptionNet**. These models are commonly used for image classification tasks and have been widely adopted in the computer vision community.

## Models Implemented

1. **AlexNet**: A deep convolutional network that was one of the first to demonstrate the power of deep learning in computer vision, especially on the ImageNet dataset.
2. **VGG16**: A deep neural network architecture consisting of 16 layers, known for its simplicity and high performance in image classification tasks.
3. **ResNet**: A deep residual network that introduced the concept of skip connections, allowing for the training of very deep networks without suffering from vanishing gradients.
4. **InceptionNet**: A network designed to optimize computational efficiency, with a novel architecture that uses convolutional layers with varying kernel sizes in parallel.

## Model Architectures

1. **AlexNet**
AlexNet consists of the following layers:

- Input layer: 224x224 image
- 5 convolutional layers followed by ReLU activations
- 3 fully connected layers
- Dropout for regularization
- Softmax output layer for classification

2. **VGG16**
VGG16 architecture follows a very simple structure with:

- 13 convolutional layers with 3x3 filters
- 3 fully connected layers
- Softmax output layer

3. **ResNet**
The ResNet architecture is composed of:

- Convolutional layers with residual connections
- The depth of the network can vary (e.g., ResNet-18, ResNet-34, ResNet-50, etc.)
- Skip connections that help in training deeper networks effectively

4. **InceptionNet**
InceptionNet uses a unique design that:

- Has multiple parallel convolutional layers with different kernel sizes (1x1, 3x3, 5x5)
- Uses 1x1 convolutions to reduce dimensionality
- Includes a fully connected output layer

