
7. What is the Tanh Activation Function? Ans- Tanh, or Hyperbolic Tangent, is an activation function that converts the input into a value between -1 and 1. Its formula is tanh(x) = (e^x - e^(-x)) / (e^x + e^(-x)). Unlike Sigmoid, Tanh is zero-centered, which can sometimes make optimization easier.

8. What is the Softmax Activation Function? Ans- Softmax converts a set of numerical values into probabilities whose total sum is 1. It is commonly used in the output layer of multi-class classification problems. The class with the highest probability is generally selected as the predicted class.

9. What is the Vanishing Gradient Problem in Activation Functions? Ans- The vanishing gradient problem occurs when gradients become extremely small during backpropagation, making it difficult for earlier layers to learn. Activation functions such as Sigmoid and Tanh can contribute to this problem when their inputs are in saturated regions. ReLU was introduced in part to reduce this issue.

10. How do we choose the right Activation Function? Ans- The choice of activation function depends on the neural network layer and the task. ReLU and its variants are commonly used in hidden layers, Sigmoid is commonly used for binary classification output, Softmax is commonly used for multi-class classification output, and a linear activation function is commonly used for regression output.
