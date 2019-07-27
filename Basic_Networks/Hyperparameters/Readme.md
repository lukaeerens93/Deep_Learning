# Hyperparameters

## Table of Contents:
Optimizer Hyperparameters
1. [ Learning Rate. ](#lr)
2. [ Minibatch Size. ](#mb)
3. [ Number of Epochs. ](#ne)
4. [ Optimizer Selection. ](#lr)
5. [ Momentum. ](#mo)
6. [ Weight Decay. ](#mo)

Model Hyperparameters
1. [ Number of Hidden Units. ](#nhu)
2. [ Dropout. ](#dr)


<a name="lr"></a>
## 1. Learning Rate

sometext

<a name="usage"></a>
## 2. Usage tips

sometext

# Optimizer Hyperparameters
1) Learning Rate: model will have have thousands of params each with their own error curve. Learning rate has to shepherd all of them
2) Minibatch Size: (recommended 1,2,4,8,16,32,64,128,256) (Typically 32). You don't need overly huge batch to get close enough to dataset mean and variance due to law of large numbers
3) Number of Epochs: Keep an eye on validation accuracy, when it climbs while training accuracy drops, sign of model overexpression of data
4) Dropout: Regularizes model by forcing signal through more neurons away from the strongest activating ones, forcing more participation from other neurons
5) Optimizer: Method of optimizing the model from loss function 

# Model Hyperparameters
1) Number of Hidden Units: For basic NN, no need to go beyond 3 layers. For CNN, the more the better.
2) 

# Links:

1) http://ruder.io/optimizing-gradient-descent/
