
31. Why is the previous velocity used in Momentum? Ans- Previous velocity preserves information about earlier gradient directions, allowing consistent directions to accumulate over multiple updates.

32. How does Momentum behave when consecutive gradients point in the same direction? Ans- Their contributions accumulate, increasing the effective movement in that direction, subject to the learning rate and momentum coefficient.

33. How does Momentum behave when consecutive gradients point in opposite directions? Ans- The opposing gradient contributions can partially cancel the accumulated velocity, reducing movement or changing its direction.

34. What is overshooting in Momentum optimization? Ans- Overshooting occurs when accumulated movement carries the parameters past the minimum instead of settling near it, potentially causing repeated oscillations.

35. Can Momentum help optimize deep neural networks? Ans- Yes. It can improve optimization speed and reduce oscillations when training deep neural networks, although it does not eliminate every training difficulty.

36. What is the difference between Momentum and Nesterov Momentum? Ans- Standard Momentum computes the gradient at the current parameters, while Nesterov Momentum estimates the gradient after a look-ahead step based on the accumulated velocity.

37. What is Nesterov Accelerated Gradient (NAG)? Ans- NAG is an optimization method that combines momentum with a look-ahead gradient calculation to adjust updates using information about the anticipated next position.

38. How does Momentum interact with mini-batch Gradient Descent? Ans- Momentum accumulates gradient information across mini-batches, helping smooth noisy updates and maintain progress in consistent directions.

39. Does Momentum remove the need for a learning rate? Ans- No. Momentum still requires a learning rate because the learning rate determines the scale of parameter updates.

40. How can you identify whether Momentum is poorly tuned? Ans- Training loss may oscillate heavily, diverge, or decrease too slowly; adjusting the learning rate and momentum coefficient can help improve stability and convergence.
