

# Image Completion Using Autoencoder

## Overview

In artifical intelligence data compression is a huge task. To perform this task we have a special type of neural network which is called by autoencoder. 

So Basically Autoencoder is an unsupervised artificial neural network that learns how to efficiently compress and encode data then learns how to reconstruct the data back from the reduced encoded representation to a representation that is as close to the original input as possible.

They work by compressing the input into a latent-space representation, and then reconstructing the output from this representation.

## History

According to the history provided in Schmidhuber, ["Deep learning in neural networks: an overview"](https://arxiv.org/abs/1404.7828), Neural Networks (2015), auto-encoders were proposed as a method for unsupervised pre-training in Ballard, "Modular learning in neural networks," Proceedings AAAI (1987). It's not clear if that's the first time auto-encoders were used, however; it's just the first time that they were used for the purpose of pre-training ANNs.

As the introduction to the Schmidhuber article makes clear, it's somewhat difficult to attribute all of the ideas used in ANNs because the literature is diverse and terminology has evolved over time.

## Explanation

In this repo we will learn autoencoders in two parts:

- Part 1 (The basics of autoencoder and working)
- Part 2 (Image completation of pokemon dataset using autoencoder)

## Dependencies

- Keras [Installation guide](https://keras.io/)
