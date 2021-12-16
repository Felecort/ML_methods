# Description of the neural network 
The constructed neural networks work according to the following algorithm:
1. The data is submitted to the input after
2. They are multiplied by weight coefficients and pass into the hidden layer of the neural network
3. A nonlinear activation function is applied to the results obtained
4. The new data is multiplied by the weights again and fed to the output.
5. The result obtained is compared with the correct one and the error for the two layers is calculated
6. The error is multiplied by the results obtained on the hidden and output layers.
7. Also, the change in weights is multiplied by the alpha coefficient to avoid learning problems
8. After changing the weights, new data is submitted to the input and the neural network continues its training

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
