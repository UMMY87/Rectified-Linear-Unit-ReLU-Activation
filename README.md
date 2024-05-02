# Rectified Linear Unit (ReLU) Activation Function

## 1. ReLU Activation Function

The Rectified Linear Unit (ReLU) is a popular activation function used in artificial neural networks. It is defined mathematically as:

$\[ f(x) = \max(0, x) \]$

In simpler terms, ReLU returns zero for any negative input and returns the input itself for any positive input.
### Explore Non Linear (ReLU) Activation
![Explore-Non-Linear-Activation](https://github.com/UMMY87/Rectified-Linear-Unit-ReLU-Activation/assets/117314436/f1fcf06d-299a-4a4f-8046-3e3b1ca7c21b)

### Why ReLU?

1. **Avoids Vanishing Gradient**:
   ReLU helps mitigate the vanishing gradient problem often encountered in deep neural networks. Unlike sigmoid and tanh functions, ReLU does not saturate in the positive region, allowing for more stable and efficient training.

2. **Non-Linearity**:
   Despite its simplicity, ReLU introduces non-linearity to the network, enabling it to learn complex patterns and relationships in the data.

3. **Sparse Activation**:
   ReLU neurons tend to be more selective in firing, leading to sparse activations. This sparsity can aid in faster convergence and reduce overfitting.

4. **Computational Efficiency**:
   ReLU is computationally efficient to compute compared to other activation functions like sigmoid or tanh.

## 2. Sigmoid Activation Function

The Sigmoid activation function is another commonly used non-linear activation function. It is defined mathematically as:

$\[ f(x) = \frac{1}{1 + e^{-x}} \]$

The sigmoid function squeezes the input into the range [0, 1], making it useful for binary classification tasks where the output represents probabilities.

## 3. Linear Activation Function

The Linear activation function simply outputs the input without any transformation. It is defined as:

$\[ f(x) = x \]$

This activation function is commonly used in the output layer for regression tasks.

## Visualization of Common Activation Function

![Common-Activation-Functions](https://github.com/UMMY87/Rectified-Linear-Unit-ReLU-Activation/assets/117314436/e5d34114-f598-42ab-a7e7-3445b93c4f3f)

## Importance of Non-linear Activation Functions in Deep Learning

Non-linear activation functions like ReLU and Sigmoid introduce non-linearity to the network, allowing it to learn complex relationships in the data. They are essential for modeling the highly non-linear mappings between inputs and outputs in many real-world problems.
