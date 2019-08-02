# Sequence Modelling Q&A

##### Write the equation describing a dynamical system. Can you unfold it? Now, can you use this to describe a RNN? (include hidden, input, output, etc.)
##### What determines the size of an unfolded graph?
##### What are the advantages of an unfolded graph? 
- arbitrary sequence length, parameter sharing, and illustrate information flow during forward and backward pass

##### What does the output of the hidden layer of a RNN at any arbitrary time t represent?
##### Are the output of hidden layers of RNNs lossless? If not, why?
##### RNNs are used for various tasks. From a RNNs point of view, what tasks are more demanding than others?
##### Discuss some examples of important design patterns of classical RNNs.
##### Write the equations for a classical RNN where hidden layer has recurrence. How would you define the loss in this case? What problems you might face while training it? (Discuss runtime)
##### What is backpropagation through time? (BPTT)
##### Consider a RNN that has only output to hidden layer recurrence. What are its advantages or disadvantages compared to a RNNhaving only hidden to hidden recurrence?
##### What is Teacher forcing? Compare and contrast with BPTT.
##### What is the disadvantage of using a strict teacher forcing technique? How to solve this?
##### Explain the vanishing/exploding gradient phenomenon for recurrent neural networks. (use scalar and vector input scenarios)
##### Why don't we see the vanishing/exploding gradient phenomenon in feedforward networks? (weights are different in different layers - Random block intialization paper)
##### What is the key difference in architecture of LSTMs/GRUs compared to traditional RNNs? (Additive update instead of multiplicative)
##### What is the difference between LSTM and GRU?
##### Explain Gradient Clipping.
##### Adam and RMSProp adjust the size of gradients based on previously seen gradients. Do they inherently perform gradient clipping? If no, why?
##### Discuss RNNs in the context of Bayesian Machine Learning.
##### Can we do Batch Normalization in RNNs? If not, what is the alternative? 
- BNorm would need future data; Layer Norm
