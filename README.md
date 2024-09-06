# What is this

This repository contains notebooks for learning the basics of qiskit, a Python library for quantum computing.

# Summary

The notebooks cover the following topics:

1. [Introduction](notebooks/exercises/01_basics.ipynb) - we cover what's a circuit and how to sample it, as well as the basic quantum gates. 
2. [Deutsch-Josza](notebooks/exercises/02_deutsch_josza.ipynb) - we describe the Deutsch-Josza algorithm, and cover a two-ancilla case to mimic noise effects
3. [Rotation gates](notebooks/exercises/03a_advanced_basics.ipynb) - we talk about parametrized gates and briefly discuss variational quantum algorithms (perhaps it's a bit early but it feels appropriate)
4. [Quantum Fourier Transform](notebooks/exercises/03b_fourier_transform.ipynb) - we present the Quantum Fourier Transform. The exercise here is to implement it by yourself.
5. [Quantum Phase Estimation](notebooks/exercises/04_quantum_phase_estimation.ipynb) - building on the QFT, we go through the phase estimation algorithm. Again, you build the QPE circuit in an exercise.
6. [Grover's algorithm](notebooks/exercises/05_grovers_algorithm.ipynb) - we cover Grover's algorithm to (quantumly) find stuff in a list
7. [Connect to IBMQ](notebooks/exercises/07a_connect_to_ibmq.ipynb) - a rather non-quantum tutorial to connect to IBMQ's free quantum hardware instances.
8. [QPE on quantum hardware](notebooks/exercises/07b_ibm_qpe.ipynb) - connect to IBMQ to get a QPE algorithm to run on real quantum hardware.
