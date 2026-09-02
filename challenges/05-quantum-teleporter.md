# 🚀 Challenge 05: Quantum Teleporter

## Background & Motivation

Quantum teleportation is a real quantum protocol that allows the **state of a qubit** to be transferred to another qubit using entanglement and classical communication.

Nothing physical is teleported.

Your challenge is to implement a simplified quantum teleportation protocol using Qiskit.

## Your Challenge

Build a three-qubit teleportation circuit.

Use:

* Qubit 0 → The state to teleport
* Qubit 1 → Alice's entangled qubit
* Qubit 2 → Bob's qubit

Your goal is to transfer the state of Qubit 0 to Qubit 2.

## Getting Started

Your circuit will need to:

1. Prepare the state to be teleported.
2. Create an entangled pair.
3. Perform Alice's operations.
4. Measure Alice's qubits.
5. Apply corrections to Bob's qubit.
6. Measure Bob's qubit.
7. Compare the original and final states.

## Deeper Questions

* Why does teleportation require entanglement?
* Why are classical measurement results required?
* Is the original quantum state still available after teleportation?
* Does quantum teleportation allow faster-than-light communication?

## 🚀 Stretch Challenge

Instead of teleporting only `|0⟩` or `|1⟩`, experiment with different quantum states.

Compare the original and teleported states.

Bonus: investigate how noise affects teleportation on real quantum hardware.
