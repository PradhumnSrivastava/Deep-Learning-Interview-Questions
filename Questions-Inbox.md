
14. What are fan-in and fan-out in weight initialization? Ans- Fan-in is the number of input connections to a neuron, while fan-out is the number of output connections. Initialization methods use these values to determine an appropriate scale for the weights.

15. How does weight initialization affect the variance of activations? Ans- If weights are too large, activation variance can grow across layers; if they are too small, activation variance can shrink. Good initialization attempts to maintain a relatively stable variance throughout the network.

16. How does weight initialization affect the vanishing gradient problem? Ans- If weights are initialized too small, gradients can become progressively smaller as they propagate backward through many layers. Proper initialization helps maintain gradient magnitude and improves gradient flow.

17. How does weight initialization affect the exploding gradient problem? Ans- If weights are initialized too large, gradients can grow rapidly as they propagate backward through layers. Appropriate initialization keeps the gradient scale under control.

18. Why is initialization particularly important in very deep neural networks? Ans- In deep networks, small changes in activation or gradient scale are repeatedly multiplied across many layers. Poor initialization can therefore cause severe vanishing or exploding signals.

19. What is LeCun initialization and when is it useful? Ans- LeCun initialization typically uses a weight variance of approximately 1/fan_in and is associated with activations such as SELU. It is designed to preserve signal variance during forward propagation.

20. Can a good weight initialization completely solve vanishing and exploding gradients? Ans- No. Good initialization significantly improves gradient flow, but it does not completely eliminate these problems. Architecture, activation functions, normalization, optimizers, learning rate, and network depth also affect gradient stability.
