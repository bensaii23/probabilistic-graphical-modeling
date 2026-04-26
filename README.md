# Probabilistic Graphical Modeling — LDPC Codes

This repository contains two projects completed as part of a course on **Probabilistic Graphical Modeling**.
The projects focus on modeling and decoding **Low-Density Parity-Check (LDPC) codes** using graphical models and inference algorithms.

## Projects

### 1. LDPC Factor Graph Representation
- Construction of LDPC codes from parity-check matrices
- Representation as factor graphs
- Modeling of parity-check constraints
- Integration of Binary Symmetric Channel (BSC) likelihoods
- Visualization of the graphical model
- Analysis of graph structure and treewidth

### 2. LDPC Decoding with Loopy Belief Propagation
- Implementation of Loopy Belief Propagation (message passing)
- Comparison with exact inference (pgmpy)
- Decoding of noisy messages transmitted through a BSC channel
- Bit Error Rate (BER) analysis as a function of noise level
- Large-scale decoding where exact inference is intractable

## Key Concepts

- Probabilistic graphical models
- Factor graphs
- Belief Propagation
- Loopy Belief Propagation
- Approximate inference
- Error-correcting codes
- Binary Symmetric Channel (BSC)
- Treewidth and inference complexity

## Objective

The objective of these projects is to demonstrate how probabilistic graphical models can be used to:

- Represent structured probabilistic dependencies
- Perform inference via message passing
- Solve real-world problems such as error correction in communication systems

## Tools and Libraries

- Python
- NumPy
- Matplotlib
- pgmpy
