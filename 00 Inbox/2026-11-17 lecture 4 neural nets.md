lecture 4 - neural networks (intro)

- perceptron = one neuron. weighted sum of inputs + bias -> same as linear regression basically!!
- then an activation function on top
  - step function (the original perceptron)
  - sigmoid -> output 0..1. one neuron w/ sigmoid = logistic regression?? I think yes
  - ReLU = max(0, x). most used today. ReLU is linear so it's fast
  - why do we need activations at all: without them stacking layers = still one big linear function
- neural network = layers of neurons. input layer -> hidden layers -> output layer
  - "deep" = many hidden layers
- forward pass: compute the output layer by layer
- backpropagation: chain rule to get the gradient of the loss wrt every weight, going backwards from the output. then a normal gradient descent step
- sigmoid in deep nets -> vanishing gradients (flat parts of the S -> gradient ~0 -> early layers stop learning). one reason ReLU won
- loss for classification = cross entropy (same as the log loss of logistic regression)
- nets have LOTS of params -> overfit easily
  - dropout: randomly switch off neurons during training
  - early stopping: stop training when validation loss starts going up

questions:
- why does ReLU work if it's not differentiable at 0??
- how many hidden layers / neurons? prof said "experiment" :(
