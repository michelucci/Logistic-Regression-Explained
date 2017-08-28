# Mathematical derivation of Logistic Regression

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
