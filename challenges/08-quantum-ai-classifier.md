# 🤖 Challenge 08: Quantum AI Classifier

## Background & Motivation

Quantum Machine Learning combines ideas from quantum computing and machine learning.

For this challenge, you will build a very small **quantum classifier**.

You don't need a large dataset or advanced mathematics.

## Your Challenge

Create a small dataset containing two classes.

For example:

```text
Feature 1 | Feature 2 | Class
-----------------------------
0         | 0         | A
0         | 1         | A
1         | 0         | B
1         | 1         | B
```

Your goal is to create a quantum circuit that attempts to distinguish between the two classes.

## Getting Started

Think about the following pipeline:

```text
Data
  ↓
Quantum Encoding
  ↓
Quantum Circuit
  ↓
Measurement
  ↓
Prediction
```

You can investigate simple quantum feature encoding and parameterized circuits.

## Your Solution Should

1. Prepare your dataset.
2. Encode the data into quantum states.
3. Create a quantum circuit.
4. Produce a prediction.
5. Evaluate how well your classifier performs.

## Deeper Questions

* How does classical data become quantum data?
* Does adding more circuit layers improve performance?
* What happens when the dataset becomes larger?
* How does your quantum classifier compare with a simple classical classifier?

## 🚀 Stretch Challenge

Find a small real-world dataset and adapt your classifier to it.

Bonus: compare your quantum classifier against a classical machine-learning model and discuss the results.
