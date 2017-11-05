# Logistic Regression

I wrote two notebooks on logistic regression. One contains the complete
mathematical derivation and one a complete python implementation
from scratch (without the use of any library except numpy).

## Mathematical derivation of Logistic Regression

I have written a complete derivation of the mathematics behind logistic regression. I derived all the equations you may need to implement the algorithm from scratch. Including

Cost and Loss function 
Forward propagation
Backward propagation
Gradient descent
Additionally I derived the equations for one training case, and then I generalise them for many training cases.

A good grasp of linear algebra and calculus is a prerequisites to understand all the details of the calculations. I use (but you don’t need to understand them fully) in a couple of points of the paper concepts that are normally used in the neural network world, like forward and backward propagation and computational graph.

With the equations in the paper you will be able to do a complete implementation of logistic regression without using any pre-existing machine learning library like scikit-learn. The only library you will need is numpy, to be able to implement the vectorized version of the equations and therefore avoid the for-loops. This will greatly improve the performance of the implementation.

I will post shortly a complete Python version of logistic regression implemented from scratch, using as a basis the equations I derived.

You can find everything on github at this address: [GIT HUB Link](https://github.com/michelucci/Logistic-Regression-Explained/blob/master/Logistic%20Regression%20from%20scratch.ipynb)

Feedback is welcome and can be left as a comment here, or as an issue on github. In case you don’t know how to create an issue you can [read this](https://help.github.com/articles/creating-an-issue/).

## Python implementation from scratch of Logistic Regression

In this notebook I develop a complete version of Logistic Regression from scratch, without using any library (except numpy). I apply the model to a subset of MNIST data containing only the digits 1 and 2 (see the data preparation part to see how to do it) to do binary classification. For the equations and the mathematics behind the python code you can refer [to this notebook](http://localhost:8888/notebooks/Documents/Data%20Science/Projects/Logistic-Regression-Explained/Logistic%20Regression%20from%20scratch.ipynb#) where I did a complete derivation of the mathematics behind the model. The relevant equations are reported here to make it easier for the reader to follow the code.
NOTE: the formulas are not explained or derived and are reported only to help the reader follow the Python code. For a derivation and justification please refer to the notebook above.
