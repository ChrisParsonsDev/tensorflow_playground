# TensorFlow Playground

Lots of cool [TensorFlow](https://www.tensorflow.org) demos/general code snippets that may at some point be useful to me.

## Code Samples

1. [Softmax](./code/softmax.py) - Manual implementation of Softmax, the function that squashes logits from a network into probabilities.
2. [notMNIST](./code/notmnist.ipynb) - Not MNIST. Cool exploration of Pickle files, randomising datasets and training linear models.
3. [Fully Connected](./code/fullyconnected.ipynb) - Converting Stochastic Gradient Descent to a 1-hidden layer neural network in TensorFlow.
4. [Regularisation](./code/regularisation.ipynb) - Using dropout and regularisation in TensorFlow.
5. [Convolutions](./code/convolutions.ipynb) - CNN architectures, dropout and pooling.

## Datasets

Working locally the datasets exist in the `./data` directory. To reduce the size of this repository I've added the contents of this folder to the `.gitignore` but you can find links to the data here..

* [notMNIST](https://www.kaggle.com/lubaroli/notmnist) - Like MNIST but harder. Slightly noisier alphabetic dataset A-J. 10 classes, just like MNIST but in a variety of different fonts.
* [Text8](http://mattmahoney.net/dc/textdata) - The first 10^9 bytes of text data from Wikipedia! 
