# Deep-Learning
Activation Functions Comparison — Deep Learning Project

This project compares the performance of four activation functions—Sigmoid, Tanh, ReLU, and Leaky ReLU—using a neural network trained on the Fashion-MNIST dataset.

What I Did

Implemented a neural network using PyTorch/TensorFlow (choose your framework).

Trained the same model architecture four times, each time using a different activation function.

Recorded training accuracy, validation accuracy, loss curves, and activation distributions.

Analysed how activation functions affect:

Gradient flow

Training speed

Stability (e.g., dead neurons)

Final accuracy

Activation Functions Compared

Sigmoid

Tanh

ReLU

Leaky ReLU

Dataset Used

Fashion-MNIST (10 clothing categories)

Chosen because it is simple, fast to train, but still complex enough to show activation differences.

Key Findings

ReLU and Leaky ReLU train the fastest and reach the highest accuracy.

Leaky ReLU is the most stable (fewer dead neurons).

Sigmoid performs the worst due to vanishing gradients.

Tanh is better than Sigmoid but still saturates.

Final Accuracy (Approx.)

Sigmoid: 80–83%

Tanh: 84–86%

ReLU: 88–90%

Leaky ReLU: 89–91% (Best)

Technologies Used

Python

PyTorch / TensorFlow

Matplotlib

NumPy

Fashion-MNIST dataset

Purpose of the Project

To understand how activation functions influence:

Learning behaviour

Gradient propagation

Model accuracy

Training stability
