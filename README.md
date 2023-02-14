# Basic_TensorFlow

This project uses neural network to accurately classify images of handwritten numbers into their correct values. The accuracy is about 95%. 
Dataset used = mnist- has 60000 training set and 10000 testing sets
Keras API is used to define a neural network which is then buillt by TensorFLow
Within Keras, the sequential and Dense model is used to specify a simple single input-output sequential layer of network in the hidden layer
The Dense model in Keras ensures that the outputs of all the neurons in a layer is being inputted to the next layer 

Activation Function - A function added to obtain the results of non linear inputs
> Ones used here:
>> ReLU- The rectified linear activation function or ReLU for short is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero
>> Softmax - Calculates the probablities of occurances of the output layer and helps in classifying to the max probablity class

3 epochs or iterations are runned in this project
