
15. What is the difference between Sigmoid and Tanh? Ans- Sigmoid outputs values between 0 and 1, while Tanh outputs values between −1 and 1 and is zero-centered.

16. What is the difference between Sigmoid and ReLU? Ans- Sigmoid smoothly maps inputs to values between 0 and 1, while ReLU outputs 0 for negative inputs and the input itself for positive inputs.

17. Why is Sigmoid used with binary cross-entropy loss? Ans- Sigmoid provides a probability for the positive class, and binary cross-entropy measures the mismatch between predicted probabilities and binary labels.

18. What is the role of a threshold when using Sigmoid for classification? Ans- A threshold converts the predicted probability into a class label; 0.5 is a common default, but the threshold can be adjusted for the task.

19. Can Sigmoid produce an exact output of 0 or 1 for a finite input? Ans- No. For any finite real input, its mathematical output lies strictly between 0 and 1, although computer implementations may round extreme values.

20. What is the main limitation of Sigmoid in deep learning? Ans- Its main limitation is the vanishing gradient problem in saturated regions, which can make training deep neural networks slow or difficult.
