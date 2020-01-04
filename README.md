# Business Problem

Given a MNIST dataset, we find the best model to this topic: Recognition handwritten digits. 

The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets.

Please see more detail in [1].

**References**

[1] The MNIST database of handwritten digits (http://yann.lecun.com/exdb/mnist/) 

[2] https://github.com/pytorch/examples/blob/master/mnist/main.py

[3] https://scikit-learn.org/stable/auto_examples/linear_model/plot_sparse_logistic_regression_mnist.html#sphx-glr-auto-examples-linear-model-plot-sparse-logistic-regression-mnist-py

[4] https://towardsdatascience.com/unit-testing-and-logging-for-data-science-d7fb8fd5d217

[5] https://github.com/CoreyMSchafer/code_snippets/blob/master/Decorators/decorators.py

[6] https://scikit-learn.org/stable/auto_examples/neural_networks/plot_mnist_filters.html?highlight=mnist

[7] https://nextjournal.com/gkoehler/pytorch-mnist

# Data Setttings

In [1], the authors described the MNIST corpus as follows:

+ train-images-idx3-ubyte.gz:  training set images (9912422 bytes)
+ train-labels-idx1-ubyte.gz:  training set labels (28881 bytes)
+ t10k-images-idx3-ubyte.gz:   test set images (1648877 bytes)
+ t10k-labels-idx1-ubyte.gz:   test set labels (4542 bytes) 

The images are normalized in 28x28, that are preserved the aspect ratio from original black and white images (NIST, 20x20), by computing the center of mass of the pixels and translating the image to position this point at the center of 28x28 field.


# Approach

## Baseline

In this baseline, we choose random result, that is in [0, 9], for each test vector input.

## Traditional Techniques: Logistic Regression, Multilayer Perceptron

In this section, we use unittest to verify the accuracy and confusion matrix of method "Logistic Regression".

## Deep Neural Network: Convolutional Neural Network

# Conclusion

In this project, as you see, we did:

+ How to explore extensions to a baseline model to improve training and predicting capacity.

+ How to use unit tests for the API and the model

+ How to use unit tests for logging

+ Can all of the unit tests be run with a single script and do all of the unit tests pass?

+ How to monitor performance

+ How to compare multiple models

+ How to use visualizations for the EDA investigation
