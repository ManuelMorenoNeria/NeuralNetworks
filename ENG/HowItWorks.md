
We have already seen what neural networks are and what they are made of. Now let's see **how they work**:

**Neural networks** operate through a learning process, where **the weights** of the connections between neurons are adjusted to produce **desired outputs** from given inputs.

Let's break down the steps:

**1. Weight initialization:** The weights of the connections between neurons are initialized randomly or with predefined values.

**2. Forward propagation:** During this stage, the input data is propagated through the neural network from the input layer to the output layer.

**3.Loss calculation:** Once the neural network produces an output, the difference between the predicted output and the actual output is calculated using a loss function

**4. Backpropagation:** In this stage, the optimization algorithm calculates the derivative of the loss function with respect to the weights of the neural network. This derivative indicates how the weights should be adjusted to minimize the loss.

**5.Weights update:** Using the information obtained in backpropagation, the weights of the neural network are updated to reduce the loss. This process is repeated iteratively over several training epochs until the neural network converges to an optimal solution.

![neuronal-networks](https://github.com/ManuelMorenoNeria/NeuralNetworks/assets/114908218/8920a051-1826-4185-a2eb-27cf05ccbb6a)


Let's explain step 2 in more detail:

As we have seen previously, a neural network is composed of the following elements:

- Inputs
- Weights
- Biases
- Weighted Sum
- Activation Function

These elements work as follows:

**1. Multiply the input parameters by the weights of the first layer.**

**2. Add the bias to the product of the multiplication.**

**3. The activation function of the next layer is applied to the previous result**

**4. The result is sent to the next layer.**

**5. Repeat the process.**
