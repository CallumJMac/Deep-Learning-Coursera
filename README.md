# Deep-Learning-Coursera
Contains all assessed work for Coursera course.

## Course 1 - Neural Networks and Deep Learning
### Week 2 - Logistic_Regression_with_a_Neural_Network_mindset_v6a
In this jupyter notebook, I built a logistic regression classifier to recognize images of cats. This network was created by defining functions using the equations that underpin this method.


### Week 3 - (Shallow neural networks) - Planar_data_classification_with_onehidden_layer_v6c
Tasks completed:
* Implement a 2-class classification neural network with a single hidden layer
* Use units with a non-linear activation function, such as tanh
* Compute the cross entropy loss
* Implement forward and backward propagation

Packages used:
* numpy
* sklearn
* matplotlib
* testCases
* planar_utils

### Week 4 - Deep neural networks
#### Building a Deep Neural Network: Step by Step
Tasks completed:
- Initialize the parameters for a two-layer network and for an $L$-layer neural network.
- Implement the forward propagation module (shown in purple in the figure below).
     - Complete the LINEAR part of a layer's forward propagation step (resulting in $Z^{[l]}$).
     - We give you the ACTIVATION function (relu/sigmoid).
     - Combine the previous two steps into a new [LINEAR->ACTIVATION] forward function.
     - Stack the [LINEAR->RELU] forward function L-1 time (for layers 1 through L-1) and add a [LINEAR->SIGMOID] at the end (for the final layer $L$). This gives you a new L_model_forward function.
- Compute the loss.
- Implement the backward propagation module (denoted in red in the figure below).
    - Complete the LINEAR part of a layer's backward propagation step.
    - We give you the gradient of the ACTIVATE function (relu_backward/sigmoid_backward) 
    - Combine the previous two steps into a new [LINEAR->ACTIVATION] backward function.
    - Stack [LINEAR->RELU] backward L-1 times and add [LINEAR->SIGMOID] backward in a new L_model_backward function
- Finally update the parameters.

Packages used:
- [numpy](www.numpy.org) is the main package for scientific computing with Python.
- [matplotlib](http://matplotlib.org) is a library to plot graphs in Python.
- dnn_utils provides some necessary functions for this notebook.

#### Building a Deep Neural Network for Image Classification: Application
Tasks completed:
- Built a deep network to classify cat vs non-cat images.
- Compared accuracy to logsitic regression model built in week 1.

Packages used:
- [numpy](https://www.numpy.org/) is the fundamental package for scientific computing with Python.
- [matplotlib](http://matplotlib.org) is a library to plot graphs in Python.
- [h5py](http://www.h5py.org) is a common package to interact with a dataset that is stored on an H5 file.
- [PIL](http://www.pythonware.com/products/pil/) and [scipy](https://www.scipy.org/) are used here to test your model with your own picture at the end.
- dnn_app_utils provides the functions implemented in the "Building your Deep Neural Network: Step by Step" assignment to this notebook.
