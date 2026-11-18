lecture 2 - linear models

- linear regression: y_hat = w*x + b. weighted sum of features + bias
- how good? MSE = avg of (pred - real)^2. squared -> big errors punished more, outliers hurt
- normal equation exists (closed form) but prof said nobody uses it for big data
- logistic regression -> it's called regression but it's for classification — confusing name, remember it!
  - same w*x+b then sigmoid 1/(1+e^-z) -> S-shaped curve, output 0..1 = probability
  - threshold 0.5. loss = log loss / cross-entropy, not MSE
- loss function = how wrong the model is. training = minimize it
- gradient descent: hill in the fog, feel the slope, step downhill. repeat
  - w = w - lr * gradient
  - batch / stochastic / mini-batch
- learning rate: hyperparameter: we choose it, the model doesn't learn it. too big = explodes, too small = slow
- feature scaling!! standardize (x-mean)/std or minmax. otherwise GD zigzags. compute stats on TRAIN only

questions:
- why squared error and not absolute error?
- how do you pick the learning rate in practice, just trial and error?
