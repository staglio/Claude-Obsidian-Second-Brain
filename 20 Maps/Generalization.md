---
type: map
created_by: claude
---
A model is only useful if it works on data it has never seen. This map collects how to measure that and how to fix it when it fails.

## Measuring
- [[Train Validation Test Split]] — keep data aside to measure honestly
- [[Cross-Validation]] — a more reliable estimate when data is scarce

## Failure modes
- [[Overfitting]] — memorizes the training data
- [[Underfitting]] — too simple to learn the pattern
- [[Bias-Variance Tradeoff]] — the tension between the two

## Fixes
- [[Regularization]] — penalize complexity

## Related maps
- [[ML Fundamentals]]
- [[Optimization]]
