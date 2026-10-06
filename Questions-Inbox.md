
3. How can you identify overfitting in a deep learning model? Ans- Overfitting can be identified when training loss continues to decrease while validation loss starts increasing, or when training accuracy becomes much higher than validation or test accuracy.

4. What is the difference between training loss and validation loss during overfitting? Ans- During overfitting, training loss generally keeps decreasing, while validation loss stops improving and may start increasing because the model is becoming specialized to the training data.

5. How does increasing the amount of training data help reduce overfitting? Ans- More diverse and representative training data gives the model more examples of the underlying patterns, making it harder for the model to simply memorize the training data.

6. How does data augmentation help prevent overfitting in deep learning? Ans- Data augmentation creates varied versions of training samples, such as rotated or cropped images, increasing effective data diversity and encouraging the model to learn more general features.

7. How does dropout help reduce overfitting in deep neural networks? Ans- Dropout randomly deactivates a fraction of neurons during training, preventing the network from relying too heavily on specific neurons and encouraging more robust feature representations.

8. How does regularization reduce overfitting in deep learning? Ans- Regularization adds a penalty to the loss function for overly large weights, encouraging simpler models and reducing the tendency to memorize training data.

9. How does early stopping help prevent overfitting? Ans- Early stopping monitors validation performance and stops training when the model stops improving on validation data, preventing unnecessary training that could lead to overfitting.

10. How can model complexity be reduced to control overfitting in deep learning? Ans- Model complexity can be reduced by using fewer layers or neurons, applying regularization, using dropout, simplifying the architecture, or stopping training earlier.
