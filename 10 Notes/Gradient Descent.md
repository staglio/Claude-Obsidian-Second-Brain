---
type: note
aliases: [GD]
source: "[[Lecture 02 - Linear Models]]"
map: "[[Optimization]]"
created: 2026-11-03
created_by: me
status: growing
---
Imagine standing on a hill in thick fog and wanting to get down: you feel the slope under your feet and take a step downhill. Repeat until the ground is flat. That's gradient descent.

The gradient of the [[Loss Function]] points in the direction where the loss *increases* fastest, so we step the other way:

`w ← w − η · ∇L(w)`

where `η` is the [[Learning Rate]].

## Key points
- **Batch GD**: use all training examples for each step (accurate but slow).
- **Stochastic GD (SGD)**: one example per step (fast, noisy).
- **Mini-batch**: a small group per step — what everyone actually uses.

## Connections
- Used to train both [[Linear Regression]] and [[Logistic Regression]].
- Converges much faster when features are on the same scale — see [[Feature Scaling]].
