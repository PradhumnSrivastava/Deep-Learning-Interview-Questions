
5. What happens if weights are initialized with very large values? Ans- Large initial weights can produce very large activations and gradients, potentially causing exploding gradients, unstable optimization, and numerical overflow.

6. What happens if weights are initialized with extremely small values? Ans- Very small weights can make activations and gradients shrink as they propagate through deep layers, potentially causing vanishing gradients and extremely slow learning.

7. What is random weight initialization? Ans- Random initialization assigns weights using randomly sampled values from a chosen probability distribution. It breaks symmetry between neurons and allows different neurons to learn different features.

8. What is the relationship between weight initialization and gradient flow? Ans- Weight initialization controls the scale of activations and derivatives as they propagate through the network. Poor initialization can cause gradients to exponentially shrink or grow across layers.

9. What is Xavier/Glorot initialization? Ans- Xavier initialization chooses the weight variance based on the number of input and output neurons, approximately maintaining the variance of activations across layers. It is commonly associated with sigmoid and tanh activations.

10. What is the main formula for Xavier initialization? Ans- For a normal distribution, weights are commonly sampled with standard deviation sqrt(2 / (fan_in + fan_out)); for a uniform distribution, the range is typically [-sqrt(6/(fan_in+fan_out)), sqrt(6/(fan_in+fan_out))].

11. What is He initialization? Ans- He initialization, also called Kaiming initialization, is designed primarily for networks using ReLU-like activation functions. It commonly initializes weights with variance approximately equal to 2/fan_in.

12. Why is He initialization preferred with ReLU activation? Ans- ReLU sets negative activations to zero, effectively reducing the variance of activations. He initialization compensates for this effect by using a larger variance, helping maintain stable signal propagation.

13. What is the difference between Xavier and He initialization? Ans- Xavier initialization generally uses variance based on both fan-in and fan-out, while He initialization primarily uses fan-in and a variance of approximately 2/fan_in. He initialization is particularly suitable for ReLU-based networks.

14. What are fan-in and fan-out in weight initialization? Ans- Fan-in is the number of input connections to a neuron, while fan-out is the number of output connections. Initialization methods use these values to determine an appropriate scale for the weights.

15. How does weight initialization affect the variance of activations? Ans- If weights are too large, activation variance can grow across layers; if they are too small, activation variance can shrink. Good initialization attempts to maintain a relatively stable variance throughout the network.

16. How does weight initialization affect the vanishing gradient problem? Ans- If weights are initialized too small, gradients can become progressively smaller as they propagate backward through many layers. Proper initialization helps maintain gradient magnitude and improves gradient flow.

17. How does weight initialization affect the exploding gradient problem? Ans- If weights are initialized too large, gradients can grow rapidly as they propagate backward through layers. Appropriate initialization keeps the gradient scale under control.

18. Why is initialization particularly important in very deep neural networks? Ans- In deep networks, small changes in activation or gradient scale are repeatedly multiplied across many layers. Poor initialization can therefore cause severe vanishing or exploding signals.

19. What is LeCun initialization and when is it useful? Ans- LeCun initialization typically uses a weight variance of approximately 1/fan_in and is associated with activations such as SELU. It is designed to preserve signal variance during forward propagation.

20. Can a good weight initialization completely solve vanishing and exploding gradients? Ans- No. Good initialization significantly improves gradient flow, but it does not completely eliminate these problems. Architecture, activation functions, normalization, optimizers, learning rate, and network depth also affect gradient stability.
