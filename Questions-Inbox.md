
9. Why can a ReLU neuron stop learning? Ans- If its pre-activation remains negative for all training examples, its output and gradient are zero, so gradient-based updates may not reactivate it.

10. What is the main limitation of ReLU? Ans- Its main limitation is that negative inputs have zero gradient, which can cause dying ReLU neurons.

11. Why is ReLU computationally efficient? Ans- ReLU mainly compares its input with zero, requiring fewer computations than exponential-based activation functions such as Sigmoid and Tanh.

12. Is ReLU a linear activation function? Ans- ReLU is nonlinear overall because its behavior changes at zero, although it is linear in each of its negative and positive regions.

13. Why does ReLU help reduce the vanishing gradient problem? Ans- For positive inputs, ReLU has a derivative of 1, so gradients passing through active ReLU units are not reduced by the activation derivative.

14. What is the difference between ReLU and Leaky ReLU? Ans- ReLU outputs zero for negative inputs, whereas Leaky ReLU allows a small negative output by applying a small positive slope to negative inputs.

15. What is the difference between ReLU and Sigmoid? Ans- ReLU outputs non-negative values without an upper bound, whereas Sigmoid outputs values strictly between 0 and 1 for finite inputs.

16. Can ReLU produce negative outputs? Ans- No. Standard ReLU outputs only zero or positive values because negative inputs are mapped to zero.

17. Why can ReLU produce sparse activations? Ans- ReLU maps all negative inputs to zero, so some neurons produce zero activations for a given input.

18. Where is ReLU commonly used in deep learning? Ans- ReLU is commonly used in hidden layers of feedforward neural networks and convolutional neural networks.

19. What is the difference between ReLU and Tanh regarding output range? Ans- ReLU outputs values from 0 to positive infinity, while Tanh outputs values between -1 and 1.

20. How can the dying ReLU problem be reduced? Ans- It can sometimes be reduced by using Leaky ReLU or PReLU, choosing a suitable learning rate, and using appropriate weight initialization.
