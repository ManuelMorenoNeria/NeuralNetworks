**How Neural Networks Work: Step by Step**

Neural networks operate through a learning process where the weights of the connections between neurons are adjusted to produce desired outputs from given inputs. This process can be broken down into several steps:

**1. Weight Initialization:**
   - In this stage, the weights of the connections between neurons are initially set either randomly or using predefined values. These weights determine the strength of the connection between neurons and are essential for the functioning of the neural network.

**2. Forward Propagation:**
   - During forward propagation, input data is transmitted through the neural network from the input layer to the output layer.
   - Each neuron in a hidden layer performs a weighted sum of the received inputs, multiplying each input by its corresponding weight and summing the results. Then, a bias is added to this weighted sum.
   - The result of this operation is passed through an activation function, which determines whether the neuron should "fire" and what its output will be.
   - This process is repeated for each layer of the neural network until reaching the output layer, which produces the final prediction.

**3. Loss Calculation:**
   - Once the neural network has generated an output, the difference between the predicted output and the actual output is calculated using a loss function. This loss function quantifies how well the neural network is performing in its predictions.
   - The goal is to minimize this loss function, which involves adjusting the weights of the neural network to reduce the error between the predicted and actual outputs.

**4. Backpropagation:**
   - In this stage, the optimization algorithm calculates the derivative of the loss function with respect to the weights of the neural network. This derivative indicates how the weights should be adjusted to minimize the loss.
   - Using the chain rule, this derivative is propagated backward through the neural network, allowing the calculation of the contribution of each weight to the total loss.
   - With this information, the weights of the neural network are updated using an optimization algorithm, such as gradient descent, with the aim of reducing the loss.

**5. Weight Update:**
   - Using the information obtained in backpropagation, the weights of the neural network are updated to reduce the loss. This process is iteratively carried out over several training epochs until the neural network converges to an optimal solution.
   - It is important to adjust the learning rate and other hyperparameters to ensure effective training and prevent overfitting.

![neural-networks](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/8920a051-1826-4185-a2eb-27cf05ccbb6a)

Let's explain step 2:

As we have seen earlier, a neural network is formed by the following elements:
- Inputs
- Weights
- Biases
- Weighted Sum
- Activation Function

These elements work as follows:

**1. We multiply the input parameters by the weights of the first layer.**

**2. We add the bias to the product of the multiplication.**

**3. The result is then passed through the activation function of the next layer.**

**4. The result is sent to the next layer.**

**5. We repeat the process.**

