# Cyclic learning rate
Implementation of cyclic learning rate from the paper: [Smith, Leslie N. "Cyclical learning rates for training neural networks." 2017.](https://arxiv.org/pdf/1506.01186.pdf)

## What is CLR?
CLR is used to enhance the way the learning rate is scheduled during training, to provide better convergence and help in regularizing deep learning models.
It eliminates the need to experimentally find the best values for the global learning rate. Allowing the learning rate to cyclically vary between lower and upper boundary values.
The idea is to divide the training process into cycles determined by a stepsize parameter, which defines the number of iterations in half a cycle.
