# Bike-Sharing

A project which was a part of the Udacity Deep Learning Nanodegree 2020.

A neural network to predict daily bike rental ridership from the given dataset. Decions made on the data analysis and visualization results.

The network has two layers, a hidden layer and an output layer. The hidden layer will use the sigmoid function for activations. The output layer has only one node and is used for the regression, the output of the node is the same as the input of the node. That is, the activation function is **$f(x)=x$**. 

We work through each layer of our network calculating the outputs for each neuron. All of the outputs from one layer become inputs to the neurons on the next layer. This process is called **forward propagation**.

We use the weights to propagate signals forward from the input to the output layers in a neural network. We use the weights to also propagate error backwards from the output back into the network to update our weights. This is called **backpropagation**.
