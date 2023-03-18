Designed an FNN for MNIST classification. Implemented the model and plot two curves in one figure. Used googlecolab as python interpreter 

# Input layer: The input layer will have 784 neurons, corresponding to the 28x28 pixels in each MNIST image.
# Hidden layer: We used two hidden layers, each with a certain number of neurons 256,128.
# Activation function: We will use the ReLU (Rectified Linear Unit) activation function for the hidden layer.
# Output layer: The output layer will have 10 neurons, corresponding to the 10 possible classes (digits 0 to 9). 
                We will use the softmax activation function for the output layer.
# Loss function: We will use the categorical_crossentropy loss function.
# Optimization algorithm: We will use the adam optimization algorithm.

# The input image of size (28, 28) is flattened to a 1D vector of length 784. Then, the first hidden layer with 256 neurons and ReLU activation is applied. 
# The output of the first hidden layer is passed through the second hidden layer with 128 neurons and ReLU activation. 
# Finally, the output of the second hidden layer is passed through the output layer with 10 neurons and softmax activation to obtain the predicted class probabilities.
