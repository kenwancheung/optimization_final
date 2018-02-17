# optimization_final


Background: As computing power and data size have grown exponentially in the past decade there has been a massive improvement in the accuracy and complexity of neural networks. While theorized by Minksy and others in the 60s, it was the breakthrough in the early 1980s by Geoffrey Hinton and his co-authors with the development of “back-propogation” that enabled development of deeper networks. When combined with the improvements in raw computing power and scale of data, we’ve seen neural networks become proficient at a variety of tasks, from image recognition to beating the best human players in the game of Go.

Problem: As neural networks have gotten deeper and more complex, parameter estimation and the relevant optimization methodology is now a critical step to building neural networks.

At a simple level, neural networks could be thought of as a host of regressions set up in m-layers. We must figure out the weights of each one of those connections. In the simple example below with just one set of hidden layers, The number of parameters to be estimated is calculated by the sum of the product of the numbers of nodes in connected layers. Parameters: (3×4)+(4×2)=20. 

We can intuitively see how quickly the parameter estimation process grows. Many of the advances in the past decade have come hand in hand with advances in the optimization methods used to optimize the parameter estimation and improve time to convergence. 

Our goal: Our team will seek to hand-code neural networks while implementing several of the most common optimization methods such as: stochastic gradient descent, Adagrad, ADAM. We will seek to gain a deeper understanding over how they converge by leveraging the age old Francisco™ method: simulation, development of our own functions, and visualization. We will complete this in Python.

