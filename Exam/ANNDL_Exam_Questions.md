# Artificial Neural Networks & Deep Learning:
In this file, I try to find/think of exam questions and try and answer them.

## Machine Learning / Deep Learning
- (19/06/2020) Conceptual difference between Deep Learning and other Machine Learning paradigms (e.g., supervised learning, unsupervised learning, etc.).
    - In traditional Machine Learning, features are typically hand-crafted or manually extracted based on domain knowledge.
    - Deep Learning, on the other hand, automates feature extraction by learning hierarchical representations of data from data. For example: lower layers in a neural network extract simple features (e.g., edges in images), whereas higher layers learn complex patterns (e.g., shapes, objects). 
- (19/06/2020) Example of a classical supervised learning application and its deep learning counterpart.
- (19/06/2020) Example of a classical unsupervised learning application and its deep learning counterpart.
- (03/09/2020) Is data representation learned via deep learning always better than hand-crafted features? Justify.
- (03/09/2020) How data representation is learned via convolutional neural networks.
- (03/09/2020) How data representation is learned via recurrent neural networks.
- (03/09/2020) How data representation is learned via deep autoencoders.

## Neural Networks Training
- (19/06/2020) What relationship is learned in a neural autoencoder, and why?
- (19/06/2020) How to size the embedding of a neural autoencoder.
- (19/06/2020) When to prefer weight decay over early stopping and how to tune the gamma parameter of weight decay.
- (19/06/2020) Advantages and disadvantages of sigmoid, hyperbolic tangent, and ReLU activation functions, including when to use each and their derivatives.
- (03/09/2020) What is overfitting, and what causes it?
- (03/09/2020) What is early stopping, and why does it help with overfitting?
- (03/09/2020) What is weight decay, and why does it help with overfitting?
- (03/09/2020) What is dropout, and why does it help with overfitting?

## Convolutional Neural Networks
- (19/06/2020) Enumerate the building blocks of a given network and compute the number of parameters with formulas.
- (19/06/2020) Describe the network architecture, its rationale, possible tasks, and suitable loss functions.
- (03/09/2020) Detail the building blocks of each layer of a given network, specifying block type, size, and parameter count with formulas.
- (03/09/2020) Training a denoising autoencoder for image restoration: methodology and loss function.

## Other Models and Mechanisms
- (19/06/2020) Provide descriptions and examples for models depicted in an image (not included in the text).
- (19/06/2020) Necessity of an attention mechanism versus Long Short-Term Memory (LSTM).
- (19/06/2020) Necessity of recurrence mechanisms versus attention mechanisms.
- (19/06/2020) Explain the relevance of John R. Firth's quote, "You shall know a word by the company it keeps," its mention in the course, and the associated model.

## Recurrent Neural Networks
- (03/09/2020) Necessity of recurrent neural networks for input data streams versus feed-forward architectures.
- (03/09/2020) Vanishing gradient problem in recurrent networks: definition, causes, and whether it affects only RNNs.
- (03/09/2020) Role of ReLU in mitigating vanishing gradients.
- (03/09/2020) Role of Xavier initialization in mitigating vanishing gradients.
- (03/09/2020) Description and benefits of LSTM in mitigating vanishing gradients.