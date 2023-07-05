# EMNIST digit recognition with Convolutional Neural Network
* The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset. The EMNIST dataset consists of two parts:

1. EMNIST Balanced: This dataset contains a balanced distribution of all 26 letters and 10 digits, for a total of 784 classes.
2. EMNIST Unbalanced: This dataset contains a more realistic distribution of letters and digits, with some classes being more represented than others.

* Here, the digits dataset is used which has 10 classes(0-9). It has 2,40,000 train dataset and 40,000 test dataset.

* The EMNIST digit dataset is used to train a convolutional neural network (CNN) for image classification or digit recognition. A CNN is a type of deep learning model that is well-suited for image classification tasks. CNNs work by learning to extract features from images, and then using these features to classify the images into different categories.

* A convolution is the process of applying a filter (“kernel”) to an image. Max pooling is the process of reducing the size of the image through downsampling.

* In this notebook, convolutional layers is added to the neural network model using the Conv2D layer type in Keras. This layer is similar to the Dense layer, and has weights and biases that need to be tuned to the right values. The Conv2D layer also has kernels (filters) whose values need to be tuned as well. So, in a Conv2D layer the values inside the filter matrix are the variables that get tuned in order to produce the right output.
