---
type: note
aliases: []
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: claude
status: seedling
---
The model is too simple to capture the pattern, so it is bad on both training and validation data. Example from the lecture: fitting a straight line through clearly curved data.

## Key points
- Sign: training error and validation error are **both** high.
- Fixes: a more complex model, better features, less [[Regularization]].

## Connections
- It is the high-bias side of the [[Bias-Variance Tradeoff]]; the opposite of [[Overfitting]].
