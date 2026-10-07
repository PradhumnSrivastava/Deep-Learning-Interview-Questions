
1. What is underfitting in deep learning? Ans- Underfitting occurs when a deep learning model is too simple or insufficiently trained to learn the underlying patterns in the training data, resulting in poor performance on both training and unseen data.

2. How can you identify underfitting in a deep learning model? Ans- Underfitting is usually identified when both training and validation performance are poor, with high training loss and high validation loss or low accuracy on both datasets.

3. What is the difference between underfitting and overfitting in deep learning? Ans- Underfitting occurs when the model fails to learn important patterns from the data, while overfitting occurs when the model learns the training data too closely and performs poorly on unseen data.

4. Why can an overly simple neural network cause underfitting? Ans- An overly simple network may not have enough layers, neurons, or parameters to represent the complex patterns present in the data, causing it to have high bias and poor performance.

5. How does insufficient training cause underfitting? Ans- If a neural network is trained for too few epochs, its parameters may not have enough time to converge toward useful values, resulting in poor performance on both training and validation data.

6. How can increasing model complexity help reduce underfitting? Ans- Adding appropriate layers, neurons, or model capacity can allow the network to learn more complex patterns and representations that a simpler model could not capture.

7. How can reducing excessive regularization help with underfitting? Ans- Excessive regularization can restrict the model too much and prevent it from learning important patterns. Reducing regularization allows the model greater flexibility to fit the training data.

8. How can the learning rate cause underfitting in deep learning? Ans- An inappropriate learning rate, especially one that is too small, can make optimization extremely slow, so the model may fail to learn sufficiently within the available training time.

9. How can increasing the number of training epochs help overcome underfitting? Ans- Training for more epochs gives the optimizer additional opportunities to update the model parameters and learn the underlying patterns, provided the model has sufficient capacity.

10. What are the common ways to reduce underfitting in deep learning? Ans- Underfitting can be reduced by increasing model capacity, training for more epochs, improving features or data representation, reducing excessive regularization, and tuning the learning rate and optimizer.