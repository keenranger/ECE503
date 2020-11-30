# ECE503: Advanced Pattern Recognition (Homework)

## School of Electrical Engineering, KOREA UNIVERSITY

### Submission due: by (Tue 5 pm) 15 Dec 2020, Hard copy

 

 Objective: Implementation of handwritten number recognition by CNN.

 

This is our 3rd exercise in a series that deal with the MNIST Database (http://yann.lecun.com/exdb/mnist/). The MNIST Database is a collection of samples of handwritten digits from many people, originally collected by the National Institute of Standards and Technology (NIST), and modified to be more easily analyzed computationally.

 

Read: “How to develop a CNN (convolutional neural nets) for handwritten digit classification”.
 (https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/).

Use the MNIST data samples (http://yann.lecun.com/exdb/mnist/) for training and testing.
Develop a code in Python to design a CNN to perform 10 digit classification. 
Experiment with 3 different combination of layers (conv and pooling).
You may use any libraries from Keras, Tensorflow, or Pytorch for developing a Python code.
Summarize the results and report them. Include the code you ran with your report as follows:
Describe what you have done for the homework assignment.
Elucidate and justify your network design and hyperparameters. 
(e.g., filter size,filter numbers,  pooling,  # of layers, # of nodes on each layer, choice of activation functions on each layer, cost function, learning rate, optimizer,  and so on)

MUST include a Learning curve (from an experiment)
MUST include five accuracy and their average from 5-fold cross validation (CV= use 80% for training. 20% training for 5 different partitions of dataset. See https://en.wikipedia.org/wiki/Cross-validation_(statistics) )
Compare the averaged accuracy of CNN with of ANN (HW 2).
Source code file(s)
Must be well organized (comments, indentation, …)
You need to upload the “original python file (*.py)” after changing to “*.py.txt”. For example, “*.py” to “*.py.txt”