# Gradient Descent Algorithms : Compariason Through an Example

Most the time when I train Neural Networks on tensorflow I set the optimizer by default to Adam optimizer. I have already look into formula but I have never implemented any of them. Here is some simple code. This repository contains code for gradient descents algorithms : 

## Basic mini-batch gradient descent :
RAS

## SGD + Momentum :
The idea behind Momentum is to gain into speed when we go downhill not to be stuck into a wrong minima (if we gain speed we will be able to pass an other uphill) 



## Nesterov Momentum
 Nesterov Momentum add one little different bit to the momentum calculation. Instead of calculating gradient of the current position, it calculates the gradient at the approximated new position.




## Adagrad
The Adagrad uses a different approach : the learning rate is adaptive per-parameter. We accumulate the sum of squared of all of our parameters’ gradient, and use that to normalize the learning rate alpha



## Adam
Adam tries to combine the best of both world of momentum and adaptive learning rate.



## Conclusions :
Suprisingly ADAM is not always the best choices.... 
