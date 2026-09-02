# 🗺️ Challenge 06: Quantum Treasure Hunt

## Background & Motivation

Imagine a treasure hidden somewhere in a collection of possible locations.

A classical computer may need to check locations one by one.

Quantum computing provides algorithms that can search certain unstructured spaces more efficiently.

One example is **Grover's algorithm**.

Your mission is to use Qiskit to find the hidden treasure.

## Your Challenge

Consider four possible locations:

```text
00
01
10
11
```

Only one contains the treasure.

Build a circuit that increases the probability of measuring the correct location.

## Getting Started

First, create a circuit where all four states are equally likely.

Then investigate how **Grover's algorithm** changes the probability distribution.

Your solution should:

1. Create the search space.
2. Define a target state.
3. Mark the target.
4. Amplify its probability.
5. Measure the result.

## Deeper Questions

* Why isn't superposition alone enough?
* What does the oracle do?
* What is amplitude amplification?
* What happens when you increase the search space?
* How many Grover iterations should you use?

## 🚀 Stretch Challenge

Allow the user to choose the treasure location and automatically generate the appropriate circuit.

Bonus: compare the number of searches required classically versus using Grover's algorithm.
