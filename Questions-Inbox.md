
36. What is the difference between Momentum and Nesterov Momentum? Ans- Standard Momentum computes the gradient at the current parameters, while Nesterov Momentum estimates the gradient after a look-ahead step based on the accumulated velocity.

37. What is Nesterov Accelerated Gradient (NAG)? Ans- NAG is an optimization method that combines momentum with a look-ahead gradient calculation to adjust updates using information about the anticipated next position.

38. How does Momentum interact with mini-batch Gradient Descent? Ans- Momentum accumulates gradient information across mini-batches, helping smooth noisy updates and maintain progress in consistent directions.

39. Does Momentum remove the need for a learning rate? Ans- No. Momentum still requires a learning rate because the learning rate determines the scale of parameter updates.

40. How can you identify whether Momentum is poorly tuned? Ans- Training loss may oscillate heavily, diverge, or decrease too slowly; adjusting the learning rate and momentum coefficient can help improve stability and convergence.
