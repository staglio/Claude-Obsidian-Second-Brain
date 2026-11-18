---
type: note
aliases: [Cost Function, Objective Function]
source: "[[Lecture 02 - Linear Models]]"
map: "[[Optimization]]"
created: 2026-11-03
created_by: claude
status: seedling
---
A single number that measures how wrong the model's predictions are on the training data. Training a model = finding the parameters that make this number as small as possible.

## Key points
- Different tasks use different losses: [[Mean Squared Error]] for regression, log loss for classification.
- The loss is computed on the training set, but what we actually care about is error on new data.

## Connections
- [[Gradient Descent]] is the algorithm that walks downhill on the loss.
- [[Regularization]] adds an extra penalty term to the loss to keep the model simple.
- Low training loss alone can be a trap — see [[Overfitting]].
