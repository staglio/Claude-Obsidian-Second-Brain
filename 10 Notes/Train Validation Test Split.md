---
type: note
aliases: [Train/Test Split, Validation Set, Test Set, Training Set]
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: claude
status: seedling
---
Split the data in three before doing anything:
- **Training set** — the model learns from it.
- **Validation set** — used to compare models and tune hyperparameters.
- **Test set** — used once, at the very end, to report the final score.

> "Test set = the final exam, you can't look at it while studying."

## Key points
- A common split is 70 / 15 / 15.
- If you tune on the test set, the final score is too optimistic.

## Connections
- Hyperparameters such as the [[Learning Rate]] and the strength of [[Regularization]] are chosen on the validation set.
- A big gap between training and validation error is the signature of [[Overfitting]].
- With little data, [[Cross-Validation]] replaces a single validation set.
