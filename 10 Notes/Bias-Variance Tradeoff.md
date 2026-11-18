---
type: note
aliases: [Bias, Variance]
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: me
status: growing
---
- **Bias** = error from wrong assumptions; the model is too simple to fit the pattern.
- **Variance** = error from being too sensitive to the specific training data; the model is too complex.

Making the model more complex lowers bias but raises variance. The goal is the sweet spot in the middle, where validation error is lowest.

My mental picture: darts. High bias = all darts land close together but off-center in the same direction. High variance = darts all over the board.

## Connections
- Too much bias → [[Underfitting]]. Too much variance → [[Overfitting]].
- [[Regularization]] is the knob that moves a model from high variance toward high bias.
