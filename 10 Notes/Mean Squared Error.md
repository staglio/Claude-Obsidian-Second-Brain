---
type: note
aliases: [MSE]
source: "[[Lecture 02 - Linear Models]]"
map: "[[Optimization]]"
created: 2026-11-03
created_by: claude
status: seedling
---
The average of the squared differences between predictions and true values: `MSE = (1/n) Σ (ŷ − y)²`.

## Key points
- Squaring makes every error positive.
- Squaring also punishes big errors much more than small ones → MSE is sensitive to outliers.

## Connections
- It is the standard [[Loss Function]] for [[Linear Regression]].
