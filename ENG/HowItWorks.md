# We have already seen what neural networks are and what they consist of. Now let's see **how they work**:

**Neural networks** operate through a learning process, where the **weights** of the connections between neurons are adjusted to produce **desired outputs** from given inputs.

Let's break down the steps:

**1. Weight Initialization:**

At this stage, the weights of the connections between neurons are initially set randomly or using predefined values. These weights determine the strength of the connection between neurons and are essential for the neural network's operation.

**2. Forward Propagation:**

   - During forward propagation, input data is transmitted through the neural network from the input layer to the output layer.
   - Each neuron in a hidden layer performs a weighted sum of the received inputs. The weighted sum is simply the multiplication of each input by its corresponding weight. Then, a bias is added to this weighted sum to obtain the neuron's output.
   - The result of this operation is passed through an activation function, which determines if the neuron should "activate" and what its output will be.
   - This process is repeated for each layer of the neural network until reaching the output layer, which produces the final prediction.

   [To know more about this step, click here.](/ENG/step2.md)

**3. Loss Calculation:**

   - Once the neural network has generated an output, the difference between the predicted output and the actual output is calculated using a loss function. This loss function quantifies how well the neural network is performing in its predictions.
   - The goal is to minimize this loss function, which involves adjusting the network's weights to reduce the error between the predicted and actual outputs.

**4. Backpropagation:**

   - In this stage, the derivative of the loss function with respect to the network's weights is calculated. This derivative shows how to adjust the weights to minimize the loss.
   - The derivative is propagated backward through the network using the chain rule, calculating the contribution of each weight to the total loss.
   - With this information, the weights are updated using an optimization algorithm, such as gradient descent, to reduce the loss.

   [To know more about this step, click here.](/ENG/step4.md)

**5. Weight Update:**

   - Using the information obtained in backpropagation, the neural network's weights are updated to reduce the loss. This process is done iteratively over several training epochs until the neural network converges to an optimal solution.
   - It is important to adjust the learning rate and other hyperparameters to ensure effective training and avoid overfitting.

![neural-networks](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/8920a051-1826-4185-a2eb-27cf05ccbb6a)

