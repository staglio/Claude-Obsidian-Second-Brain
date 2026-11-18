---
type: note
aliases: []
source: "[[Lecture 01 - What Is Machine Learning]]"
map: "[[ML Fundamentals]]"
created: 2026-10-27
created_by: me
status: growing
---
Learning from examples where we already know the right answer. Every example has [[Features and Labels|features and a label]], and the model learns a function that maps features to the label, so it can predict labels for new examples it has never seen.

## Key points
- **Regression** = predict a number (house price) → [[Linear Regression]]
- **Classification** = predict a category (spam / not spam) → [[Logistic Regression]]
- "Learning" in practice means making a [[Loss Function]] as small as possible on the training examples.

## Connections
- The opposite setting is [[Unsupervised Learning]], where there are no labels at all.
- Because the model only sees training data, the real question is whether it works on new data — see [[Overfitting]].
