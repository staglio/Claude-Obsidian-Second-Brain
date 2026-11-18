---
type: note
aliases: [Features, Labels, Target]
source: "[[Lecture 01 - What Is Machine Learning]]"
map: "[[ML Fundamentals]]"
created: 2026-10-27
created_by: claude
status: seedling
---
**Features** are the inputs that describe an example (size of the house, number of rooms, neighbourhood). The **label** (or target) is what we want to predict (the price). Written as a feature vector `x` and a label `y`.

## Connections
- [[Supervised Learning]] needs both features and labels; [[Unsupervised Learning]] only has features.
- When features live on very different ranges (rooms: 1–5, size: 30–300 m²), training gets harder — see [[Feature Scaling]].
