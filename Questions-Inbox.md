
8. Why can Sigmoid cause the vanishing gradient problem? Ans- For very large positive or negative inputs, Sigmoid becomes saturated and its derivative becomes very small, causing gradients to shrink during backpropagation.

9. What is the Tanh activation function and how does it differ from Sigmoid? Ans- Tanh maps inputs between -1 and 1 and is zero-centered, whereas Sigmoid maps inputs between 0 and 1 and is not zero-centered.

10. Why is Softmax commonly used in the output layer of multi-class classification? Ans- Softmax converts class scores into probabilities that sum to 1, allowing the model to represent the probability distribution across multiple mutually exclusive classes.
