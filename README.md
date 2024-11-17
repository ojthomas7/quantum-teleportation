# Quantum Circuits: Quantum Teleportation

This repository contains an implementation of quantum teleportation using Qiskit, demonstrating how to transmit a quantum state from one qubit to another using quantum entanglement and classical communication.

### Overview

- Quantum teleportation is a technique for moving quantum states in the absence of communication channels linkning the sender and recipient
- If we want to send information about an arbitrary qubit |ψ⟩, we can do this by its interaction with one half of an EPR pair.
- Based on the interaction and measurement of |ψ⟩ with one half of the EPR pair, by measuring the second half, and knowing the classical results of the first measurement, we may determine the state |ψ⟩.

### The Circuit

Consider an EPR pair in the state $|\Psi$
