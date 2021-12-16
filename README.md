# Analysis of the Iris dataset.  
Neural networks with different activation functions cope well with the task of classification.  
It was found that for faster training of a neural network, it is advisable to use the activation function real, because with such a subchord, the number of epochs for training is 201. When using sigmoids as an activation function, it is necessary to increase the number of epochs by 401.  
The accuracy in both cases is approximately 87%  

# Results of neural networks   

**neural network**
|params|relu|sigmoid|
|:----------|:-----------|:----------:|
|epochs|201|401|
|alpha|0.002|0.002|
|hidden layer size|7|7|
Percentage of correct answers|93.3|90|

## Analysis of results
Analysis of the results showed that the error most often occurs when the input parameters are Iris-Versicolor. This type of its parameters is similar to Iris-Virginica, which is why the neural network is wrong in some cases.  
The highest correlation is achieved in Iris-Setosa, there were no problems with this type of data when determining
