# Autoencoder Image Denoising
An autoencoder is a neural network architecture made up of two main components: an encoder and a decoder. The encoder reduces the input data's dimensionality to a lower-dimensional representation, which is then used by the decoder to reconstruct the original input data. This architecture allows the autoencoder to learn efficient representations of input data using unsupervised learning. Denoising is one of the most common applications of autoencoders, in which the network learns to remove noise from input data such as images or signals by reconstructing clean versions of the noisy input.

## Dataset
- Training Data: Noisy images from the MNIST Fashion dataset
- Input Dimension: (28 x 28 x 1)
- Output Dimension: (28 x 28 x 1)

## Model Architecture
Type: Convolutional Autoencoder

Layers:
- Convolutional layers
- MaxPooling layers
- Conv2DTranspose layers
- UpSampling layers

## Training Parameters
- Epochs: 30
- Batch Size: 256
- Optimizer: Adam optimizer
- Loss Function: Binary Crossentropy
- Validation Split: 20%
