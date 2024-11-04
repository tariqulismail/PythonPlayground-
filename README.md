# PyTorch CNN



### CNN stands for Convolutional Neural Networks. Classification has been a popular application of Machine Learning. CNN models are good at detecting patterns and are therefore employed mostly for problems related to image classification/recognition, such as facial recognition of our smartphones. It detects patterns like edges, circles, bulges etc. and associates them to one of the outputs probabilistically, thereby learning different characteristics of different classes. In this tutorial, learn more about PyTorch CNN.

# Why Convolution Neural Networks?

Convolution Neural Networks, as powerful as they are, are thought to have been inspired by the idea of mimicking the human brain. In fact, from a bird’s eye view, they perform functions similar to a human brain. Scientists in the 20th century proposed that our brain applies some filter to the image perceived by the eye to identify it. It is exactly how a convolution neural network works. However, the exact picture is somewhat different compared to an elementary level.

Another school of thought believes that it owes its popularity to its ability to identify patterns irrespective of the image’s scale or orientation. For example, suppose we train a model to identify a nose. Now, if we give an image of an entire face to our trained model, it will correctly identify the nose as it takes into account all the smaller fragments of the input independent of the remaining parts of the image. This property is also known as the regularisation mechanism of the convolutional neural network.

CNNs are also good at identifying images even when rotated or spatially altered. It is called the property of invariance.

Working of a convolution layer:
In a convolutional network, the hidden layers consist of multiple (not necessarily all) convolutional layers. These layers have some filters to extract information about patterns. It is done by convolving the filter matrix over the input matrix.
