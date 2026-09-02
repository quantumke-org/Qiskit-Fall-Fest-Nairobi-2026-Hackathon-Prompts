# ✊ Challenge 07: Quantum Rock, Paper, Scissors

## Background & Motivation

Rock, Paper, Scissors is a simple game based on random choices.

In this challenge, you'll replace classical randomness with a **quantum random choice**.

## Your Challenge

Build a quantum version of Rock, Paper, Scissors.

You can represent the choices as:

```text
Rock     → 00
Paper    → 01
Scissors → 10
```

This leaves one unused state:

```text
11
```

Your challenge is to decide how to handle it.

## Getting Started

Use quantum superposition and measurement to generate the computer's choice.

Your program should:

1. Generate the computer's quantum choice.
2. Allow the player to select Rock, Paper or Scissors.
3. Determine the winner.
4. Display the result.

## Deeper Questions

* How can you make the three choices equally likely?
* Why is generating three equally probable states more difficult than two?
* What happens if you simply map `11` to one of the choices?
* Could this introduce bias?

## 🚀 Stretch Challenge

Create a complete game with:

* Score tracking
* Multiple rounds
* Player statistics
* Win/loss history

Bonus: investigate how to generate three outcomes without introducing bias.
