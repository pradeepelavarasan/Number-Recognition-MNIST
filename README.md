# Number-Recognition-MNIST
This project explains a basic way of creating a Number Recognition application on MNIST data set using custom CNN model and achieving 99.2% validation accuracy. It also includes basic definitions of CNN (Convolution Neural Networks) Concepts.

# Convolution Neural Networks (CNN) Concepts

## 1.Convolution
It is the process of convolving(scanning) on the input image using a kernel(feature detector) to get an output image. This also helps in sharing of parameters to identify similar things in an image compared to fully connected networks.

## 2.Filters/Kernels
These are set of weights that are used to convolve over an input image to give output image. The values of these weights are updated iteratively during back propagation.

## 3.Epochs
1 epoch is the process of doing forward propagation and backward propagation on the entire training dataset.

## 4.1x1 Convolution
1*1 kernel is used to reduce the no. of channels in input layer without impacting the size (X and Y dimensions) of the layer.

## 5.3x3 Convolution
3*3 kernel is the ideal kernel size used for convolution as it 2*2 will not help to get the symmetry. 3*3 will also optimize the no. of parameters.

## 6.Feature Maps
Feature maps are the outputs of each layer which is the result of convolving kernel over the previous layer. These are used to understand what the CNN model detects at each layer.

## 7.Activation Function
Any non-linear (mostly) mathematical function applied on the product of input and kernel values to give the output values. This helps to establish complex relationships as a non-linear function. 

## 8.Receptive Field
The receptive field at a given layer is the number of pixels that every pixel in that layer has seen and derived its value from the original image (global) or the previous layer (local).


