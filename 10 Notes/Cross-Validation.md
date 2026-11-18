---
type: note
aliases: [K-Fold Cross-Validation, CV]
source: "[[Lecture 03 - Generalization]]"
map: "[[Generalization]]"
created: 2026-11-10
created_by: claude
status: seedling
---
Split the training data into `k` folds. Train `k` times, each time holding out a different fold for validation, then average the `k` scores.

## Key points
- Gives a more reliable estimate than a single validation set, especially with little data.
- Costs `k` times the training time.

## Connections
- A replacement for the single validation set in [[Train Validation Test Split]] — the test set still stays untouched.
- Useful for picking the strength of [[Regularization]].
