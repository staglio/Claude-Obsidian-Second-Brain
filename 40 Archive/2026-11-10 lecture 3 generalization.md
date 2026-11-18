lecture 3 - generalization

- what matters = error on NEW data
- train / validation / test. 70/15/15 ish
  - test set = the final exam, you can't look at it while studying
- overfitting = memorizing past exam answers. train err low, val err high
- underfitting = straight line through curved data. both errors high
- bias vs variance. complexity up -> bias down, variance up. (darts picture!)
- regularization: add penalty on weights to the loss
  - L2 ridge = squares, L1 lasso = abs -> some weights exactly 0
  - lambda = how strong, tune on validation
- cross validation k-fold: train k times, average. good with small data

questions:
- how do I choose k in cross-validation? 5? 10?
