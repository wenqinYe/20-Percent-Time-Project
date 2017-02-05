# Neural Networks Log

I will log my learning on neural networks in this markdown file; for I travel long distances with empty buckets to fill the well in my mind.



## Perceptron and Sigmoid Perceptrons

_Feb 4 2017_

At the heart of a neural network is the perceptron. The perceptron is a a glorified linear function that takes an input, x, performs a linear calculation and produces an output y.

The linear function at the heart of all neurons is: y = mx + b. However, computer scientists prefer z = wx+b, where _w_ refers to the **weight** and _b_ refers to the **bias** term. If the output is greater than 0 the neuron outputs a 1, else it outputs a 0.

However this simple activation is insufficient for useful applications because it does not allow for small changes in weights and biases to result in a small change in output. Instead the output is forced to be either a zero or a one.

A sigmoid function solves this problem by producing a smooth approximation of the thresholding function.

![Image result for sigmoid](images/main-qimg-05edc1873d0103e36064862a45566dba.gif)



This allows the artist of a neural network to fine tune parameters to fine tuned results in the output.

Combinations of neural networks in layered arrangements are used to solve a variety of problems.

Some terminology: input layer neurons receive inputs, output layer neurons output a value, hidden layer neurons receive and output values to other neurons.



## Backpropagation

_Feb 4 2017_















