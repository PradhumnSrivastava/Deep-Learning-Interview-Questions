
15. How is Backpropagation applied to a hidden layer? Ans- A hidden layer receives the gradient from the layer ahead of it. This gradient is multiplied by the derivative of the hidden layer's activation function to determine the gradient with respect to its weighted input. These gradients are then used to calculate the gradients of the hidden layer's weights and biases.

16. Why are gradients calculated from the output layer toward the input layer? Ans- Gradients are calculated backward because the loss is directly connected to the final output. By starting at the loss and moving backward, Backpropagation can use the Chain Rule to efficiently determine how parameters in each earlier layer contributed to the final error.

17. Why is Backpropagation computationally efficient compared with calculating each parameter's effect separately? Ans- Backpropagation reuses intermediate derivatives and applies the Chain Rule systematically. This allows gradients for many parameters to be calculated efficiently in a single backward pass instead of separately calculating the effect of every parameter on the loss.

18. What is the difference between Backpropagation and Gradient Descent? Ans- Backpropagation is used to calculate the gradients of the loss with respect to the model parameters, while Gradient Descent is an optimization method that uses those gradients to update the parameters. In simple terms, Backpropagation calculates the direction of change, and Gradient Descent uses that information to update the parameters.

19. What is the difference between a Backward Pass and a Forward Pass? Ans- The Forward Pass calculates the outputs of the neural network and stores intermediate values needed for gradient computation. The Backward Pass uses the calculated loss and these intermediate values to compute gradients from the output layer toward the earlier layers.

20. Why are intermediate values stored during Forward Propagation for Backpropagation? Ans- Intermediate values such as inputs, weighted sums, and activation outputs are required to calculate derivatives during the backward pass. Storing these values avoids recomputing the forward calculations and makes gradient computation more efficient.
