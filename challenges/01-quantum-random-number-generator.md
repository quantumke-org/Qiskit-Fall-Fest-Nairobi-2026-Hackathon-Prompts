# 🎲 Challenge 01: Quantum Random Number Generator

## Background & Motivation

Random numbers are important in computing, including simulations, games, security and cryptography.

Classical computers typically generate **pseudo-random** numbers using mathematical algorithms. Quantum systems can provide randomness based on the probabilistic nature of quantum measurement.

Your challenge is to build a **quantum random number generator using Qiskit**.

## Your Challenge

Create a quantum circuit that generates a random number with `n` possible outcomes.

Your circuit should:

1. Choose an appropriate number of qubits.
2. Use **H-gates** to create an equal superposition.
3. Measure the qubits.
4. Convert the measured binary state into a numerical value.
5. Return the generated random number.

### Think About

How many possible states can you represent with:

* 1 qubit?
* 2 qubits?
* 3 qubits?
* `n` qubits?

How does the number of possible states scale as you add qubits?

## Tips

Use **shots** to run your circuit multiple times.

With enough shots, you should see the possible states appearing approximately equally often.

Try:

* 10 shots
* 100 shots
* 1,000 shots
* 10,000 shots

Compare the results.

## Deeper Questions

* Why don't all outcomes appear exactly equally often?
* How does statistical variation affect your results?
* What happens when you run the circuit on real quantum hardware?
* How does quantum noise affect the distribution?
* How could you make the generator more statistically fair?

## 🚀 Stretch Challenge

Create a function such as:

```python
quantum_random(min_value, max_value)
```

that generates a random integer within any specified range.

Bonus: investigate whether your generator remains fair when the range is not a power of two.
