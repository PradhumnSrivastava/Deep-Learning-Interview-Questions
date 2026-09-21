
9. What is Huber Loss? Ans- Huber Loss combines properties of MSE and MAE. It behaves like squared error for small errors and like absolute error for large errors. Therefore, it can provide a useful balance between sensitivity to errors and robustness to outliers.

10. How does a Loss Function help in training a Neural Network? Ans- During Forward Propagation, the neural network generates predictions. The Loss Function compares these predictions with the actual targets and calculates the error. During Backpropagation, gradients of the loss with respect to the model parameters are calculated, and an optimizer uses these gradients to update the weights and biases to reduce the loss.
