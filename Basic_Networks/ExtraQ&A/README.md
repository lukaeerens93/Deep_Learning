# Questions and Answers

## 1) Explain why you need biases in each hidden layer
Explanation:
i) Inputs come in, are weighed and then summed
ii) Sum is activated (maybe by a sigmoid or something...)
iii) Changing input weights, changes steepness of (sigmoid) activation function (like so)
![](images/1.jpg)
iv) But what if you want the output to be like 0, when an input is 2 (look at why it can't be the case on image above)
v) Need an ability to translate and offset the activation so that the function can intercept the desired output
![](images/2.jpg)
vi) This is what a bias does and this a crucial ability for successful machine learning
