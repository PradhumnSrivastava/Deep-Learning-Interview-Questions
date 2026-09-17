

---

## Interview Question

### What is an Artificial Neural Network (ANN)?

**Answer:** An Artificial Neural Network is a computational model inspired by biological neural networks. It consists of interconnected neurons organized into layers that transform input data through weighted connections, biases, and activation functions to produce predictions.

---

## Interview Question

### What is a neuron in a neural network?

**Answer:** A neuron is the basic computational unit of a neural network. It takes input values, multiplies them by learned weights, adds a bias, applies an activation function, and produces an output.

---

## Interview Question

### What are weights and biases in a neural network?

**Answer:** Weights determine the importance of individual input features, while the bias allows the neuron to shift its activation independently of the input values. Both weights and biases are learned during training.

---

## Interview Question

### What is the role of an activation function in a neural network?

**Answer:** An activation function introduces non-linearity into the network, allowing it to learn complex relationships. Without activation functions, multiple neural network layers would effectively behave like a single linear transformation.

---

## Interview Question

### What is the difference between an input layer, hidden layer, and output layer?

**Answer:** The input layer receives the features from the dataset, hidden layers perform intermediate transformations and learn representations, and the output layer produces the final prediction. A neural network can contain one or many hidden layers.

---

## Interview Question

### What is forward propagation in a neural network?

**Answer:** Forward propagation is the process of passing input data through the network from the input layer to the output layer. Each neuron computes a weighted sum, adds a bias, applies an activation function, and passes the result to the next layer.

---

## Interview Question

### Why are neural networks called deep neural networks when they have multiple hidden layers?

**Answer:** A neural network is generally called deep when it contains multiple layers of learnable transformations between the input and output. Greater depth allows the network to learn hierarchical representations, where deeper layers can build increasingly complex features from simpler ones.

---

## Interview Question

### What is the difference between a shallow neural network and a deep neural network?

**Answer:** A shallow neural network typically contains one or very few hidden layers, while a deep neural network contains many hidden layers. Deep networks can learn more hierarchical and complex representations but are generally more difficult and computationally expensive to train.

---

## Interview Question

### What is the Universal Approximation Theorem?

**Answer:** The Universal Approximation Theorem states that a neural network with at least one hidden layer and a suitable non-linear activation function can approximate a broad class of continuous functions to arbitrary accuracy given sufficient neurons. However, it does not imply that a shallow network will learn the function efficiently or generalize well.

---

## Interview Question

### Why can't a neural network with only linear activation functions learn complex non-linear relationships?

**Answer:** If every layer uses only a linear activation function, the composition of all layers remains a linear transformation. Therefore, adding more layers does not increase the expressive power beyond a single linear layer. Non-linear activation functions are required to model complex relationships.

---

## Interview Question

### Why can a deeper neural network represent some functions more efficiently than a shallow network?

**Answer:** Deeper networks can learn hierarchical representations, where early layers learn simple patterns and later layers combine them into increasingly complex features. For certain classes of functions, representing these hierarchical compositions with depth can require exponentially fewer neurons than representing them with a single very wide layer.

---

## Interview Question

### What is the difference between representational capacity and optimization difficulty in deep neural networks?

**Answer:** Representational capacity refers to the complexity of functions a neural network can represent, while optimization difficulty refers to how easily the training algorithm can find useful parameters. Increasing depth or width can increase representational capacity, but it can simultaneously make optimization harder because of issues such as poor conditioning, vanishing or exploding gradients, and complicated loss landscapes.

---

## Interview Question

### Why can a neural network have low training loss but still perform poorly on unseen data?

**Answer:** A low training loss means the model fits the training data well, but it does not guarantee that it has learned patterns that generalize to unseen data. The model may have overfit noise or training-specific patterns. Generalization depends on factors such as model architecture, dataset size and quality, regularization, optimization, and the distribution of unseen data.
