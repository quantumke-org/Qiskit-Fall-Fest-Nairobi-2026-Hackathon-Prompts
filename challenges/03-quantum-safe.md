# 🔐 Challenge 03: Quantum Safe

## Background & Motivation

You've discovered a mysterious **Quantum Safe**.

The safe will only open if you create the correct quantum state.

You are given a target measurement distribution and must reverse-engineer a circuit capable of producing it.

## Your Challenge

Create a quantum circuit that produces the required target distribution.

For example:

```text
00 → 50%
11 → 50%
```

Your circuit should produce approximately this distribution when measured.

You may experiment with:

* H-gates
* X-gates
* Z-gates
* CNOT gates
* Measurement

## Getting Started

Start with two qubits.

Try putting one qubit into superposition and then connecting the qubits with a CNOT gate.

Measure the circuit multiple times and observe the results.

## Deeper Questions

* Why do some states appear while others don't?
* What happens if you remove the CNOT?
* What happens if you change the order of the gates?
* Why are the two qubits correlated?

## 🚀 Stretch Challenge

Create multiple different circuits that produce the same target distribution.

Bonus: design your own "safe" with a custom target distribution and create a circuit capable of unlocking it.
