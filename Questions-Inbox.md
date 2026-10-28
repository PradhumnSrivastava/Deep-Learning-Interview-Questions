
13. What is the difference between Tanh and ReLU? Ans- Tanh produces bounded outputs between -1 and 1, whereas ReLU outputs 0 for negative inputs and the input itself for positive inputs.

14. Why is Tanh a nonlinear activation function? Ans- Tanh applies a nonlinear transformation to its input, enabling neural networks to learn nonlinear relationships.

15. Is Tanh an odd function? Ans- Yes. Tanh satisfies tanh(-x) = -tanh(x), meaning its graph is symmetric about the origin.

16. What happens to the gradient of Tanh when the input is close to zero? Ans- The gradient is close to 1 near zero, allowing gradients to pass through with relatively little attenuation at that activation.

17. Why can Tanh cause slow training in deep neural networks? Ans- When many layers operate in saturated regions, their small derivatives can multiply during backpropagation, causing gradients to shrink.

18. Where is Tanh commonly used in deep learning? Ans- Tanh is used in some hidden layers and recurrent neural network components, including the candidate-state and cell-state update calculations in LSTMs.

19. Can Tanh outputs be interpreted directly as probabilities? Ans- No. Tanh outputs can be negative and do not form a probability distribution; Sigmoid or Softmax is generally used when probability outputs are required.

20. What is the main limitation of the Tanh activation function? Ans- Its main limitation is gradient saturation for large positive or negative inputs, which can cause the vanishing gradient problem.
