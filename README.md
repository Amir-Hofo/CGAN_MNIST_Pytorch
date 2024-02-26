# CGAN_MNIST_Pytorch
This code implements an example of a CGAN deep learning model using PyTorch.
CGAN actually stands for Conditional Generative Adversarial Net, which is called GAN networks that can determine the type of generator output images (for which of the classes, images should be generated).
The architecture used for the generator and discriminator is MLP (multi layer perceptron) network.
This model is trained with MNIST dataset and finally it can produce images of numbers 0 to 9 according to the label we specify for it.
