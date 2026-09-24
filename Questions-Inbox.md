
3. What are the main steps of Backpropagation? Ans- The main steps are performing Forward Propagation, calculating the Loss, propagating the error backward through the network using the Chain Rule, calculating gradients for the weights and biases, and updating the parameters using an optimization algorithm such as Gradient Descent.

4. What is the role of the Chain Rule in Backpropagation? Ans- The Chain Rule is used to calculate how the loss changes with respect to parameters in earlier layers. Since the output of one layer becomes the input to another layer, the Chain Rule allows these derivatives to be multiplied together to calculate the final gradient.

5. What is a Gradient in Backpropagation? Ans- A gradient represents the rate at which the loss changes with respect to a model parameter such as a weight or bias. It indicates the direction and magnitude in which a parameter should be changed to reduce the loss.

6. How are weights updated during Backpropagation? Ans- After calculating the gradient of the loss with respect to a weight, the optimizer updates the weight using the gradient. In basic Gradient Descent, the update rule is w_new = w_old - η(∂L/∂w), where η is the learning rate and ∂L/∂w is the gradient of the loss with respect to the weight.

7. What is the difference between Forward Propagation and Backpropagation? Ans- Forward Propagation passes input data from the input layer toward the output layer to generate a prediction and calculate the loss. Backpropagation works in the opposite direction by propagating the error from the output layer backward to calculate gradients used for updating the model parameters.

8. What happens if the learning rate is too high or too low during Backpropagation? Ans- If the learning rate is too high, parameter updates can become too large, causing the training process to overshoot the minimum or become unstable. If the learning rate is too low, training can become very slow and may require many iterations to converge.

9. What are Vanishing and Exploding Gradients in Backpropagation? Ans- Vanishing gradients occur when gradients become extremely small as they are propagated backward through many layers, making earlier layers learn very slowly. Exploding gradients occur when gradients become extremely large, causing unstable parameter updates. Techniques such as suitable activation functions, normalization, careful initialization, and gradient clipping can help address these problems.

10. What is the complete training process involving Backpropagation? Ans- During training, the model first performs Forward Propagation to generate predictions. The Loss Function then calculates the prediction error. Backpropagation calculates the gradients of the loss with respect to the weights and biases using the Chain Rule. Finally, an optimizer uses these gradients to update the parameters, and this process is repeated for multiple batches and epochs until the model learns the underlying patterns.
