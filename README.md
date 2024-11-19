# Quantum Circuits: Quantum Teleportation

This repository contains an implementation of quantum teleportation using Qiskit, demonstrating how to transmit a quantum state from one qubit to another using quantum entanglement and classical communication.

### Overview

- Quantum teleportation is a technique for moving quantum states in the absence of communication channels linkning the sender and recipient
- If we want to send information about an arbitrary qubit $|\Psi⟩$, we can do this by its interaction with one half of an EPR pair.
- Based on the interaction and measurement of $|\Psi⟩$ with one half of the EPR pair, by measuring the second half, and knowing the classical results of the first measurement, we may determine the state $|\Psi⟩$.

### The Circuit

Let some arbitrary quantum state $|\Psi\rangle$ be:

$$|\Psi \rangle = \alpha \0\rangle + \beta |1\rangle$$


Consider an EPR pair in the state

$$|\Psi⟩ = \frac{1}{\sqrt{2}} (|00⟩ + |11⟩)$$
