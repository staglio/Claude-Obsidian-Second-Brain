---
type: note
aliases: [L1 Regularization, L2 Regularization, Ridge, Lasso]
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: claude
status: seedling
---
Add a penalty for large weights to the [[Loss Function]], so the model prefers simpler solutions.

## Key points
- **L2 (ridge)**: penalty = λ · sum of squared weights → keeps all weights small.
- **L1 (lasso)**: penalty = λ · sum of absolute weights → can push some weights to exactly zero (feature selection).
- λ is a hyperparameter: bigger λ = simpler model.

## Connections
- The main tool against [[Overfitting]]; too much of it causes [[Underfitting]].
- λ is chosen on the validation set — see [[Train Validation Test Split]].
