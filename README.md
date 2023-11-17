# NeuralNetworks Package

A Python package containing implementations of various neural network components.

## Installation

```bash
pip install neuralnetworks



#Usage
#Activation Functions
python
Copy code
import numpy as np
from neuralnetworks import sigmoid, tanh, relu, leaky_relu, softmax, der_sigmoid

# Example usage
x = np.array([0.5, -0.2, 0.1])
result_sigmoid = sigmoid(x)
result_tanh = tanh(x)
result_relu = relu(x)
result_leaky_relu = leaky_relu(x)
result_softmax = softmax(x)
result_der_sigmoid = der_sigmoid(x)