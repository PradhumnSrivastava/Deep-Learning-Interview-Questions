
17. How does weight initialization affect the exploding gradient problem? Ans- If weights are initialized too large, gradients can grow rapidly as they propagate backward through layers. Appropriate initialization keeps the gradient scale under control.

18. Why is initialization particularly important in very deep neural networks? Ans- In deep networks, small changes in activation or gradient scale are repeatedly multiplied across many layers. Poor initialization can therefore cause severe vanishing or exploding signals.

19. What is LeCun initialization and when is it useful? Ans- LeCun initialization typically uses a weight variance of approximately 1/fan_in and is associated with activations such as SELU. It is designed to preserve signal variance during forward propagation.

20. Can a good weight initialization completely solve vanishing and exploding gradients? Ans- No. Good initialization significantly improves gradient flow, but it does not completely eliminate these problems. Architecture, activation functions, normalization, optimizers, learning rate, and network depth also affect gradient stability.
