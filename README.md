# Deep-learning 
All Deep Learning models like ANN, CNN ,RNN Image classification and object detection and NLP projects are done

## Introduction
Deep learning is a branch of machine learning which is based on artificial neural networks. It is capable of learning complex patterns and relationships within data. In deep learning, we don’t need to explicitly program everything. It has become increasingly popular in recent years due to the advances in processing power and the availability of large datasets. Because it is based on artificial neural networks (ANNs) also known as deep neural networks (DNNs). These neural networks are inspired by the structure and function of the human brain’s biological neurons, and they are designed to learn from large amounts of data.

Deep learning is the branch of machine learning which is based on artificial neural network architecture. An artificial neural network or ANN uses layers of interconnected nodes called neurons that work together to process and learn from the input data.

In a fully connected Deep neural network, there is an input layer and one or more hidden layers connected one after the other. Each neuron receives input from the previous layer neurons or the input layer. The output of one neuron becomes the input to other neurons in the next layer of the network, and this process continues until the final layer produces the output of the network. The layers of the neural network transform the input data through a series of nonlinear transformations, allowing the network to learn complex representations of the input data. For more info you can refer to the above link:- https://www.geeksforgeeks.org/introduction-deep-learning/

## Description
In this repo we have considered small case studies regarding various Deep Learning Architectures like ANN, CNN snd RNN. A neural network is a system of neurons which are analogous to the neurons in our brain which processes and signals information to various parts of our body.

###  An Artificial Neural Network (ANN):-
It is a system of fully dense connected neural network which consists of three layers namely:-
1. Input Layer
2. Hidden Layer
3. Output Layer

#### Input Layer
The input layer consists of teh input data which consists of various features of the dataset which are taken as input and are initialized some randomly assigned weights with each features associated. 

#### Hidden Layer
These weights along with the features are then passed into the hidden layer which may contain many neurons which processes the information passed from the input layer by using some mathematical formulations (activation function) and then passes this adjusted and computed information to the output layer. In a fully connected dense and Deep ANN, it can contain several hidden layers which are used for the information processing and computation. 

#### Output Layer
This layer calculates the output based on the weights passed for each features in the input dataset and applies an activation function over it to produce the final predicted output.

You can refer https://www.geeksforgeeks.org/artificial-neural-networks-and-its-applications/ for more info

### Convolutional Neural Network(CNN):-
A Convolutional Neural Network consists of a Convolution layer which pre-processes the input as various images which contain various pixels of mxn dimensions and a filter of dimension fxf which is applied to the original image and a feature map is created by performing elementary matrix row and column operations. Then the most important feautures are extracted by using Max Pooling layer which consists of a stride layer of 2x2. After the extraction of the image features various feature maps are aggregated into a single layer and is Flattened to convert a multi-dimensional image into a single dimensional array. Then that flattened image layer is passed to the input layer of the ANN and the model is trained and tested on that data.
For more information you can refer here:- https://en.wikipedia.org/wiki/Convolutional_neural_network
