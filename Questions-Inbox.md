
18. What is the difference between Backpropagation and Gradient Descent? Ans- Backpropagation is used to calculate the gradients of the loss with respect to the model parameters, while Gradient Descent is an optimization method that uses those gradients to update the parameters. In simple terms, Backpropagation calculates the direction of change, and Gradient Descent uses that information to update the parameters.

19. What is the difference between a Backward Pass and a Forward Pass? Ans- The Forward Pass calculates the outputs of the neural network and stores intermediate values needed for gradient computation. The Backward Pass uses the calculated loss and these intermediate values to compute gradients from the output layer toward the earlier layers.

20. Why are intermediate values stored during Forward Propagation for Backpropagation? Ans- Intermediate values such as inputs, weighted sums, and activation outputs are required to calculate derivatives during the backward pass. Storing these values avoids recomputing the forward calculations and makes gradient computation more efficient.
