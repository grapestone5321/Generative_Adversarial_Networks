# Generative_Adversarial_Networks
Udacity Deep Learning Foundation Nanodegree Program



## Autoencoders

In this lesson we're covering autoencoders. These models are used to compress data, as well as image denoising, which you'll be implementing in this lesson. 

The idea here is we'll build a network that tries to generate it's input data, but with a narrow hidden layer that serves as a compressed representation of the input data.

## Generative_Adversarial_Networks

Together with Ian, we've built a notebook that will lead you through building your own GAN and train it on MNIST. 

You'll build the generator and discriminator networks, as well as set up the losses and optimizers which requires something new since we need to train the networks in parallel. 

We've included a notebook with exercises where you'll implement the network and another notebook with solutions.

## Deep Convolutional GANs

In this lesson you'll implement the Deep Convolutional GAN model to generate full color images. The additional complexity of these images requires using convolutional layers in the generator and discriminator. You'll also need to use a technique called batch normalization to get the GAN to train appropriately.

You'll be training your GAN on the Street View House Numbers dataset, a small example is shown above. After training, the generator will be able to create images that are nearly identical to these images.

Note: This lesson will eventually cover semi-supervised learning with GANs. We'll release more content in a few weeks with Ian Goodfellow on this.

## Semi-Supervised Learning
In this lesson, Ian Goodfellow will lead you through implementing a semi-supervised GAN model in TensorFlow. Semi-supervised models are used when you only have a few labeled data points. These perform surprisingly well even though the amount of labeled data you have is relatively tiny.

Here we'll use the SVHN dataset again and attempt to classify the images with a large proportion of the labels dropped.

As a heads up, this material is cutting edge and is more difficult to understand and implement than what you've seen before. But, you'll learn a lot and see some really cool results.
