# Convolutional Neural Network - TensorFlow 2.0 

[![Tensorflow](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT7b9ZDD7lMdkByT-f_RCAqSQYqnq_CpgD16IFrwfmUwWCmdt7H)](https://colab.research.google.com/github/JohnAntonusMaximus/convolutional-neural-network/blob/master/Convolutional_Neural_Network_TensorFlow_2_0_.ipynb)

[![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/JohnAntonusMaximus/convolutional-neural-network/blob/master/Convolutional_Neural_Network_TensorFlow_2_0_.ipynb)

## Background

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.  

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

The original dataset can be found here:
https://www.cs.toronto.edu/~kriz/cifar.html


## Labels (Clothing Types)

Each training and test example is assigned to one of the following labels:

airplane										
automobile										
bird										
cat										
deer										
dog										
frog										
horse										
ship										
truck										



## Approach

In this example, I'm using a convolutional neural network with Tensorflow 2.0 consisting of two convolutional layers, each one followed by a max pooling layer. The results of the final pooling layer are flattened and then passed into an artificial neural network consitently of two layers, one with 128 neurons and the other with 128 neurons, each having dropout of 20-40% to prevent overfitting. 

On the training set, I was able to achieve about 96% accuracy, however the test set maxed out at 70% which suggests there is some overfitting on the training data. Work in progress, but more or less to just get some more practice with TF-2.0. 


# Links

* [KaizenTek](http://www.kaizentek.io) - IT Consulting & Cloud Professional Services  



