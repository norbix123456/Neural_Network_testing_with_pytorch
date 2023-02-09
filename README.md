# Neural Network testing with pytorch  :bulb:
Experimental model of neural network to classify part of iris dataset.
## Overview 📝
In this project I have decided to create a model of neural network which will take 2 inputs:
 - Sepal length
 - Sepal width

and will give two outputs  which describe the probaility of choosing:
- Setosa
- Versicolor

The neural network consists of one hidden layer with two neurons that have a sigmoid activation function. After the output values were calculated, I applied the softmax function to normalize the parameters.


## Conclusions 📊

After training the dataset I have obtained a model with 5,6% of total loss. To improve this model I would advice to check the different combinations of the parameters such as:
- Learning rate
- Number of epochs
- Different activation functions
- Different configurations of neurons

## Author ✏️
Norbert Nieżorawski


