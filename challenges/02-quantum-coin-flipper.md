# 🪙 Challenge 02: Quantum Coin Flipper

## Background & Motivation

A coin flip has two possible outcomes: heads or tails.

Quantum mechanics provides a natural way of generating a probabilistic outcome. In this challenge, you'll create a quantum coin using a single qubit.

## Your Challenge

Build a one-qubit circuit that behaves like a fair coin.

Your circuit should produce:

* `0` ≈ 50% of the time
* `1` ≈ 50% of the time

Use an **H-gate** to create the required quantum state.

Convert the results into:

```text
0 → Heads
1 → Tails
```

## Experiment

Run your circuit with different numbers of shots:

* 10
* 100
* 1,000
* 10,000

Record the percentage of heads and tails.

## Deeper Questions

* Why don't you get exactly 50/50 every time?
* What happens if you remove the H-gate?
* Can you create a biased quantum coin?
* Which gates can change the probability of the outcomes?

## 🚀 Stretch Challenge

Create a simple **Quantum Coin Flip Game** where:

1. A player chooses Heads or Tails.
2. The quantum circuit generates the result.
3. The program determines whether the player wins.
4. The program keeps track of the score.

Bonus: allow two players to compete.
