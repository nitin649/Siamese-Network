# Siamese-Network

# Question Answering Task using T5 model.

# Description:

## Trained Siamese Network for Handwritten letters Classification.

## The term Siamese means twins.

# Project Structure

1. For the purpose of this blog, we will use the Omniglot dataset which is a collection of 1623 hand drawn characters from 50 different alphabets. 
   For every character there are just 20 examples, each drawn by a different person. Each image is a gray scale image of resolution 105x105

2. Model Training
    - This code is an implementation of the methodology described in this research paper by Gregory Koch et al. 
      Model architecture and hyper-parameters that I have used are all as described in the paper
    - The two Convolutional Neural Networks are not different networks but are two copies of the same network, 
      hence the name Siamese Networks. Basically they share the same parameters.

# Libraries
1.Tensorflow , Keras

   
