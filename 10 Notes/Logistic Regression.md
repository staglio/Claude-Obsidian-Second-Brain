---
type: note
aliases: []
source: "[[Lecture 02 - Linear Models]]"
map: "[[ML Fundamentals]]"
created: 2026-11-03
created_by: claude
status: seedling
---
A **classification** model, despite the name. It computes the same weighted sum as [[Linear Regression]] (`w·x + b`) and then squashes it with a [[Sigmoid Function]] into a probability between 0 and 1. Predict class 1 if the probability is above 0.5.

> "It's called regression but it's for classification — confusing name, remember it!"

## Key points
- The loss is log loss (also called cross-entropy), not [[Mean Squared Error]].
- The decision boundary (where probability = 0.5) is a straight line / plane.

## Connections
- Trained by minimizing its [[Loss Function]] with [[Gradient Descent]], exactly like linear regression.
- One of the two basic models of [[Supervised Learning]].
