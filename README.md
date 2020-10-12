# Hack-a-thing Two: Learning PyTorch and PySyft

## Short description of what you attempted to build / What I learned
Last hack-a-thing, I became well versed in Tensorflow Federated, the Tensorflow Framework for federated learning. Unfortunately, our group realized that this framework could not at all accomplish the tasks we needed to complete. Another library, PySyft, could. PySyft, however, is built on top of the ML ecosystem, PyTorch, an ecosystem which I was not familiar with, prior to now. So, I completed the following tasks, in order

1. Learned PyTorch - Learned the mechanics of PyTorch through the Tensors in PyTorch notebook and learned how to create Deep Learning models in PyTorch through the Neural Networks in Pytorch notebook
2. Learned about the mechanics of PySyft, through this [Udacity course](https://www.udacity.com/course/secure-and-private-ai--ud185)
3. Learned how to use PySyft by following the tutorial and completing the self-written excercises in the Pysyft Tutorial Notebook (which came with the Udacity course)
4. Followed a final tutorial on how to build a CNN in a federated way (I built a custom CNN in Tensorflow Federated for my last hack-a-thing, and I wanted to see how these two frameworks differed when attempting to complete the same task). This tutorial can be found in the 'CNN Project' notebook
5. Finally, learned how to use PyGrid, a service that allows PySyft models to be deployed in production, and not just merely in local simulations. To learn this, I first used docker container to simulate individual machines and then worked on utilize AWS machines as worker nodes that would engage in training models in a federated way.

## How does this hack-a-thing inspire you or relate to your possible project ideas?
In order to conduct federated learning on a distributed network of devices, we need to be able to utilze, and then build on top of frameworks like this one. PySyft is the leading library for federated learninga and other privacy-centric applications of AI, and we need to understand the library and the concepts that this library is built on top of in order to move forward with our project.

## What didn’t work
Suprisingly, everything seemed to work here. The only hang ups were that installing the PySyft library came with some challenges, and I ran into a number of conflicts. The library also relies on a slightly outdated version of PyTorch, which means that finding the correct documentation on which PySyft functions I should be using was more difficult than usual.