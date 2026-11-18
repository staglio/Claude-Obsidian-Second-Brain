---
type: note
aliases: [Normalization, Standardization]
source: "[[Lecture 02 - Linear Models]]"
map: "[[Optimization]]"
created: 2026-11-03
created_by: claude
status: seedling
---
Putting all features on similar ranges before training.

## Key points
- **Standardization**: `(x − mean) / std` → each feature has mean 0 and std 1.
- **Min-max scaling**: squeeze each feature into [0, 1].
- Compute mean/std on the **training set only**, then apply the same numbers to validation and test data.

## Connections
- Without scaling, one feature measured in thousands dominates the gradient and [[Gradient Descent]] zig-zags slowly toward the minimum.
- The "training set only" rule comes from keeping the test data unseen — see [[Train Validation Test Split]].
- Only matters because features in [[Features and Labels]] come in arbitrary units.
