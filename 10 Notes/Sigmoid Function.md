---
type: note
aliases: [Logistic Function, Sigmoid]
source: "[[Lecture 02 - Linear Models]]"
map: "[[ML Fundamentals]]"
created: 2026-11-03
created_by: claude
status: seedling
---
`σ(z) = 1 / (1 + e^(-z))`. An S-shaped curve that squashes any number into the range (0, 1): big positive numbers go close to 1, big negative numbers close to 0, and 0 maps to exactly 0.5.

## Key points
- Useful when the output should be read as a probability.
- The curve is almost flat at both ends.

## Connections
- It is what turns [[Linear Regression]]'s weighted sum into [[Logistic Regression]].
