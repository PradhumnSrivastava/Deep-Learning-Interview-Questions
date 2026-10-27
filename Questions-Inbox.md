1. What is the Sigmoid activation function? Ans- Sigmoid is a nonlinear activation function that converts any real-valued input into a value between 0 and 1.

2. What is the mathematical formula of the Sigmoid function? Ans- The formula is σ(x) = 1 / (1 + e^(-x)), where x is the input and e is Euler's number.

3. What is the output range of the Sigmoid function? Ans- The output range is (0, 1), meaning the output approaches 0 or 1 but never reaches either value for a finite input.

4. What is the output of Sigmoid when the input is 0? Ans- The output is 0.5 because σ(0) = 1 / (1 + e⁰) = 1 / 2.

5. What happens when the input to Sigmoid becomes very large and positive? Ans- The output approaches 1 because e^(-x) approaches 0 as x increases.

6. What happens when the input to Sigmoid becomes very large and negative? Ans- The output approaches 0 because e^(-x) becomes very large as x decreases.

7. Why is Sigmoid used in binary classification? Ans- Sigmoid converts a model's raw score, or logit, into a value between 0 and 1 that can represent the estimated probability of the positive class.

8. Why is Sigmoid commonly used in the output layer of binary classification models? Ans- It produces a single probability-like output that can be compared with a decision threshold to classify an observation.

9. What is the derivative of the Sigmoid function? Ans- Its derivative is σ'(x) = σ(x)(1 − σ(x)), which is used when calculating gradients during backpropagation.

10. What is the maximum value of the Sigmoid derivative? Ans- The maximum derivative is 0.25, occurring at x = 0, where the Sigmoid output is 0.5.

11. What is the vanishing gradient problem in Sigmoid? Ans- When Sigmoid outputs are near 0 or 1, its derivative becomes very small, causing gradients to shrink during backpropagation.

12. Why is Sigmoid less suitable for hidden layers in deep neural networks? Ans- Its saturated regions produce small gradients, which can slow learning in deep networks, especially when many layers contribute to the gradient.

13. What does it mean when the Sigmoid function saturates? Ans- Saturation occurs when the input is strongly positive or negative and the output gets very close to 1 or 0, making the derivative very small.

14. Is the Sigmoid function zero-centered? Ans- No. Its outputs are always positive and lie between 0 and 1, so they are not centered around zero.

15. What is the difference between Sigmoid and Tanh? Ans- Sigmoid outputs values between 0 and 1, while Tanh outputs values between −1 and 1 and is zero-centered.

16. What is the difference between Sigmoid and ReLU? Ans- Sigmoid smoothly maps inputs to values between 0 and 1, while ReLU outputs 0 for negative inputs and the input itself for positive inputs.

17. Why is Sigmoid used with binary cross-entropy loss? Ans- Sigmoid provides a probability for the positive class, and binary cross-entropy measures the mismatch between predicted probabilities and binary labels.

18. What is the role of a threshold when using Sigmoid for classification? Ans- A threshold converts the predicted probability into a class label; 0.5 is a common default, but the threshold can be adjusted for the task.

19. Can Sigmoid produce an exact output of 0 or 1 for a finite input? Ans- No. For any finite real input, its mathematical output lies strictly between 0 and 1, although computer implementations may round extreme values.

20. What is the main limitation of Sigmoid in deep learning? Ans- Its main limitation is the vanishing gradient problem in saturated regions, which can make training deep neural networks slow or difficult.
