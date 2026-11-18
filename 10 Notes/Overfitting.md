---
type: note
aliases: []
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: me
status: growing
---
The model memorizes the training data instead of learning the pattern — like a student who memorizes past exam answers and then fails a new exam.

## Key points
- Sign: training error is low, validation error is high.
- Causes: model too complex, too little data, training too long.
- Fixes: more data, a simpler model, [[Regularization]].

## Connections
- It is the high-variance side of the [[Bias-Variance Tradeoff]]; the opposite problem is [[Underfitting]].
- You can only see it if you keep data aside — see [[Train Validation Test Split]].
