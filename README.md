# Visualizing-and-Understanding-Convolutional-neural-networks

This is a straight from scratch implementation of paper "Visualizing and Understanding Convolutional neural networks"-Matthew D. Zeiler and Rob Fergus (https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)

This implementation is using keras with tensorflow backend.

The implementation is mainly divided into two parts-
1) Feature visualization with Deconvnet.
2) Occlusion Sensitivity.

**Part 1- Feature visualization with Deconvnet**
 This is described in notebook "Feature visualization using Deconvnets in Keras". Here the term deconvolution refers to transpose           convolution.
 
 Original image -
 
 ![kangaroo](https://user-images.githubusercontent.com/20341653/43394102-2a3ea782-9417-11e8-974f-9b9eee6c1cb5.jpg)
 
 Features detected in feature map 127 of convolutional layer 3 of block 3-
 
![kangarooblock3_conv3_127_all](https://user-images.githubusercontent.com/20341653/43394117-345869a6-9417-11e8-8a40-bb6bf15f611b.png)
 
 
