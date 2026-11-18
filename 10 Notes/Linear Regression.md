---
type: note
aliases: []
source: "[[Lecture 02 - Linear Models]]"
map: "[[ML Fundamentals]]"
created: 2026-11-03
created_by: claude
status: seedling
---
Predict a number as a weighted sum of the features plus a bias: `ŷ = w·x + b`. Training means finding the weights `w` and bias `b` that make the predictions as close as possible to the real values.

## Key points
- "Closeness" is measured with [[Mean Squared Error]].
- The weights can be found with [[Gradient Descent]] (the lecture also mentioned a closed-form solution, the normal equation, that works for small problems).
- Each weight says how much the prediction changes when that feature goes up by one.

## Connections
- It is the simplest regression model in [[Supervised Learning]].
- [[Logistic Regression]] reuses the same weighted sum but passes it through a [[Sigmoid Function]] to do classification.
