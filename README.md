# Neural Network C++ Tutorial
This is a C++ implementation of the excellent neural network tutorial by Arthur Arnx.

[Original Link](https://towardsdatascience.com/first-neural-network-for-beginners-explained-with-code-4cfd37e06eaf)

This simple 2 input perceptron trains a neuron to identify whether your input is the logical OR operation, identified by this truth table:

| A | B | Result |
|:-:|:-:|:------:|
| 1 | 1 |    1   |
| 1 | 0 |    1   |
| 0 | 1 |    1   |
| 0 | 0 |    0   |

The Perceptron class can have its constructor parameter set to the two activators, Sigmoid or Relu, for different training.

Playing with the number of steps changes the accuracy of the answer.  The  article stated that if you set this number incorrectly the network may overtrain.
