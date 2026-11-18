---
type: note
aliases: [Step Size]
source: "[[Lecture 02 - Linear Models]]"
map: "[[Optimization]]"
created: 2026-11-03
created_by: claude
status: seedling
---
How big a step [[Gradient Descent]] takes at each update.

> "Hyperparameter: we choose it, the model doesn't learn it."

## Key points
- Too large → the loss jumps around or even explodes (overshoots the minimum).
- Too small → training is painfully slow.

## Connections
- It is one of the hyperparameters tuned on the validation set — see [[Train Validation Test Split]].
