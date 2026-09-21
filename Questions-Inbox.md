
3. What is the difference between Loss Function and Cost Function? Ans- A Loss Function usually measures the error for a single training example, while a Cost Function generally represents the average or total loss over the entire training dataset. However, these terms are sometimes used interchangeably in machine learning.

4. What is Mean Squared Error (MSE)? Ans- Mean Squared Error is a regression loss function that calculates the average of the squared differences between actual and predicted values. Its formula is MSE = (1/n) Σ(y - ŷ)². Squaring the errors makes larger errors contribute more strongly to the loss.

5. What is Mean Absolute Error (MAE)? Ans- Mean Absolute Error calculates the average absolute difference between actual and predicted values. Its formula is MAE = (1/n) Σ|y - ŷ|. Compared with MSE, MAE is generally less sensitive to large outliers.

6. What is Binary Cross-Entropy Loss? Ans- Binary Cross-Entropy is commonly used for binary classification problems. It measures the difference between the actual binary labels and predicted probabilities. Its formula is L = -[y log(ŷ) + (1-y) log(1-ŷ)].

7. What is Categorical Cross-Entropy Loss? Ans- Categorical Cross-Entropy is commonly used for multi-class classification when the target labels are represented as one-hot encoded vectors. It measures how different the predicted probability distribution is from the actual class distribution.

8. What is the difference between MSE and MAE? Ans- MSE squares the prediction errors, so large errors receive significantly greater penalty. MAE uses absolute errors, so it is generally less affected by outliers. MSE is often preferred when large errors should be penalized more strongly, while MAE can be more robust to outliers.

9. What is Huber Loss? Ans- Huber Loss combines properties of MSE and MAE. It behaves like squared error for small errors and like absolute error for large errors. Therefore, it can provide a useful balance between sensitivity to errors and robustness to outliers.

10. How does a Loss Function help in training a Neural Network? Ans- During Forward Propagation, the neural network generates predictions. The Loss Function compares these predictions with the actual targets and calculates the error. During Backpropagation, gradients of the loss with respect to the model parameters are calculated, and an optimizer uses these gradients to update the weights and biases to reduce the loss.
