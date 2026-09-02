# 🔗 Challenge 04: Entanglement Detector

## Background & Motivation

**Entanglement** is one of the most fascinating phenomena in quantum mechanics.

Entangled qubits can exhibit strong correlations between their measurement outcomes.

Your challenge is to create and investigate an entangled pair of qubits.

## Your Challenge

Create a two-qubit circuit where the measurement results are strongly correlated.

Your ideal results should look approximately like:

```text
00
11
```

while:

```text
01
10
```

should rarely appear in an ideal simulation.

## Getting Started

Experiment with:

1. Two qubits
2. An H-gate
3. A CNOT gate
4. Measurement

Run the circuit multiple times and examine the measurement counts.

## Deeper Questions

Experiment by changing the circuit.

What happens if you:

* Remove the H-gate?
* Remove the CNOT?
* Add an X-gate?
* Change the order of the gates?

Can you explain why the two qubits become correlated?

## 🚀 Stretch Challenge

Create and compare the different **Bell states**.

Document how their circuits and measurement results differ.

Bonus: run your experiment on real quantum hardware and compare the results with an ideal simulator.
