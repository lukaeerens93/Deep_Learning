# Questions and Answers

## 1) Explain why you need biases in each hidden layer
Explanation:
1) Inputs come in, are weighed and then summed
2) Sum is activated (maybe by a sigmoid or something...)
3) Changing input weights, changes steepness of (sigmoid) activation function (like so)
![](images/1.jpg)
4) But what if you want the output to be like 0, when an input is 2 (look at why it can't be the case on image above)
5) Need an ability to translate and offset the activation so that the function can intercept the desired output
![](images/2.jpg)
6) This is what a bias does, which is a crucial ability for successful machine learning
