---
type: source
kind: lecture
course: Intro to Machine Learning
date: 2026-11-10
raw: "[[2026-11-10 lecture 3 generalization]]"
created_by: claude
---
## Summary
- The goal is low error on *new* data, not on training data.
- Keep a validation set (or use cross-validation) and a test set you only touch once.
- Too simple → underfitting; too complex → overfitting; the bias-variance tradeoff describes the tension.
- Regularization penalizes complexity to fight overfitting.

## Notes from this source
- [[Train Validation Test Split]]
- [[Cross-Validation]]
- [[Overfitting]]
- [[Underfitting]]
- [[Bias-Variance Tradeoff]]
- [[Regularization]]

## Open questions
- how do I choose k in cross-validation? 5? 10?
