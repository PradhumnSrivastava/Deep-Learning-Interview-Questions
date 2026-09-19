
2. Why is an Activation Function important in a Neural Network? Ans- An activation function is important because it introduces non-linearity into the neural network. Without activation functions, multiple layers would behave like a single linear transformation, and the network would not be able to learn complex non-linear relationships.

3. What happens if we do not use an Activation Function? Ans- Without an activation function, a neural network containing multiple layers would effectively behave like a linear model. Even with many layers, it would not be able to learn complex non-linear patterns such as XOR.

4. What is the difference between Linear and Non-Linear Activation Functions? Ans- A linear activation function produces an output that is a linear transformation of its input, while a non-linear activation function introduces non-linearity. Linear activation functions are generally used in regression output layers, whereas non-linear functions such as ReLU, Sigmoid, and Tanh are commonly used in neural networks.

5. What is the ReLU Activation Function? Ans- ReLU stands for Rectified Linear Unit. Its mathematical formula is f(x) = max(0, x). It returns 0 for negative values and returns the input value for positive values. ReLU is widely used in hidden layers because it is simple, computationally efficient, and helps neural networks learn non-linear patterns.

6. What is the Sigmoid Activation Function? Ans- The Sigmoid function converts an input value into a value between 0 and 1. Its formula is σ(x) = 1 / (1 + e^(-x)). It is commonly used in the output layer of binary classification problems because its output can be interpreted as a probability.

7. What is the Tanh Activation Function? Ans- Tanh, or Hyperbolic Tangent, is an activation function that converts the input into a value between -1 and 1. Its formula is tanh(x) = (e^x - e^(-x)) / (e^x + e^(-x)). Unlike Sigmoid, Tanh is zero-centered, which can sometimes make optimization easier.

8. What is the Softmax Activation Function? Ans- Softmax converts a set of numerical values into probabilities whose total sum is 1. It is commonly used in the output layer of multi-class classification problems. The class with the highest probability is generally selected as the predicted class.

9. What is the Vanishing Gradient Problem in Activation Functions? Ans- The vanishing gradient problem occurs when gradients become extremely small during backpropagation, making it difficult for earlier layers to learn. Activation functions such as Sigmoid and Tanh can contribute to this problem when their inputs are in saturated regions. ReLU was introduced in part to reduce this issue.

10. How do we choose the right Activation Function? Ans- The choice of activation function depends on the neural network layer and the task. ReLU and its variants are commonly used in hidden layers, Sigmoid is commonly used for binary classification output, Softmax is commonly used for multi-class classification output, and a linear activation function is commonly used for regression output.
