# ANIME-FACE-GENERATION-USING-GAN
We used DCGAN to train a generator that generated fake images from scratch and random inputs, and a discriminator which distinguished between real data and fake data. 
DCGAN is a Deep Convolutional Generative Adversarial network that uses Deep Conv Nets to have a stable architecture and better results. It uses a Transposed Convolutional network to upsample the images. Here are a couple of guidelines followed, in particular:

Replacing any pooling layers with strided convolutions (discriminator) and fractional-strided convolutions (generator).
Using batchnorm in both the generator and the discriminator.
Removing fully connected hidden layers for deeper architectures.
Using ReLU activation in generator for all layers except for the output, which uses tanh.
Using LeakyReLU activation in the discriminator for all layer.
