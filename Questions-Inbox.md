
19. What is the difference between a Backward Pass and a Forward Pass? Ans- The Forward Pass calculates the outputs of the neural network and stores intermediate values needed for gradient computation. The Backward Pass uses the calculated loss and these intermediate values to compute gradients from the output layer toward the earlier layers.

20. Why are intermediate values stored during Forward Propagation for Backpropagation? Ans- Intermediate values such as inputs, weighted sums, and activation outputs are required to calculate derivatives during the backward pass. Storing these values avoids recomputing the forward calculations and makes gradient computation more efficient.
