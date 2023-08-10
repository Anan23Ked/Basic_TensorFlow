# Basic_TensorFlow

This project uses a neural network to classify images of handwritten numbers into their correct values accurately. The accuracy is about 95%. 

The dataset used = MNIST  (Modified National Institute of Standards and Technology database) has 60000 training sets and 10000 testing sets.

Keras API is used to define a neural network which is then built by TensorFlow.

Within Keras, the sequential and Dense model is used to specify a simple single input-output sequential layer of the network in the hidden layer
The Dense model in Keras ensures that the outputs of all the neurons in a layer are being inputted to the next layer 

Activation Function - A function added to obtain the results of non-linear inputs
> Ones used here:
>> ReLU- The rectified linear activation function or ReLU for short is a piecewise linear function that will output the input directly if it is positive, otherwise, it will output zero
>> Softmax - Calculates the probabilities of occurrences of the output layer and helps in classifying to the max probability class

3 epochs or iterations are run in this project
