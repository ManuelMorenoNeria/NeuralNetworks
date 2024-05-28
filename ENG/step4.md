### Backpropagation:

Backpropagation is a crucial process in the training of neural networks. Here is a step-by-step description of how it works:

1. **Calculation of the Derivative of the Loss Function**: 
   - The first step in backpropagation is to calculate the derivative (or gradient) of the loss function with respect to each weight in the neural network. This derivative indicates the direction and magnitude of the change needed in the weights to reduce the loss.

2. **Calculation of Derivatives in the Output Layer**:
   - First, how the loss changes with respect to the weights in the output layer is calculated.

3. **Backward Propagation of Derivatives**:
   - Then, these derivatives are used to calculate how the loss changes with respect to the weights in the previous layer, and so on, until reaching the input layer. This process is performed layer by layer, from the last layer (output) to the first layer (input).

4. **Calculation of Gradients in Each Layer**:
   - In each layer, the gradients of the weights and biases are calculated. This is done by multiplying the gradient of the next layer by the derivative of the activation function of the current neuron.

5. **Weight Update**:
   - Once all the gradients are obtained, the network weights are updated using an optimization algorithm. The most common is gradient descent, which adjusts the weights in the opposite direction of the loss gradient, multiplied by a learning rate.

6. **Iteration and Convergence**:
   - This process is repeated over multiple epochs until the loss function reaches an acceptable minimum value, indicating that the network has learned to make accurate predictions.

![maxresdefault](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/a13ee79a-395a-45f2-8d11-5a7861b33524)
