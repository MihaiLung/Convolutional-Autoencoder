# Convolutional Autoencoder

This notebook contains a convolutional autoencoder which reduces the dimension of CIFAR-10 images 4-fold then reconstructs them with a high degree of accuracy.

## Results

The model was trained on the CIFAR-10 dataset. 

The original size of the images is 32x32. By encoding them using a convolutional neural network to an encoding vector of 256, we reduced the size of the image 4-fold. We then feed them to the decoder we trained, which is also a convolutional neural network which tries to re-construct the image as accurately as possible.

The below are from the test dataset which the model had not seen in training:

![](https://raw.githubusercontent.com/MihaiLung/Convolutional-Autoencoder/master/Test_Images.PNG)

The reconstructions, after reducing the dimensionality of the input by a factor of 4.

![](https://raw.githubusercontent.com/MihaiLung/Convolutional-Autoencoder/master/Reconstructions.PNG)
