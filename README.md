# Exploring Counterintuitive Quantum Phenomena

This notebook serves as an interactive guide to five counterintuitive phenomena in quantum mechanics, using simulations to illustrate their principles.

## Overview

Quantum mechanics often presents concepts that challenge our everyday intuition. This notebook explores the following phenomena through Python simulations:

1.  **Double-Slit Interference:** Demonstrates the wave-particle duality of matter and the superposition principle. The simulation models how waves passing through two slits create an interference pattern on a screen, a hallmark of wave behavior.

2.  **Quantum Measurements:** Illustrates how measuring a quantum system can affect its state. The simulations show the probabilistic outcomes of measuring a qubit in different bases (Z and X) and highlight the difference between measuring a pure state and a superposition.

3.  **Entanglement Correlations:** Explores the phenomenon of entanglement, where two or more particles become linked in such a way that the measurement of one particle's properties instantaneously influences the properties of the others, regardless of the distance between them. The simulation demonstrates the strong correlations observed when measuring entangled particles in different bases.

4.  **Square-Barrier Transmission:** Simulates quantum tunneling, a phenomenon where a particle can pass through a potential barrier even if it does not have enough classical energy to do so. The simulation calculates the transmission probability of a particle encountering a square potential barrier as a function of its energy.

5.  **Quantum Zeno Effect:** Shows how frequent measurements of a quantum system can inhibit its evolution. The simulation demonstrates that the more often a system is measured, the less likely it is to change its state.

## Simulation Logic

Each section of the notebook includes a Python function that simulates the respective phenomenon. The simulations are based on the mathematical formulations of quantum mechanics, using libraries like `numpy` for numerical calculations and `matplotlib` for visualization. The code aims to provide a simplified yet representative model of each effect, allowing for exploration and understanding through interactive execution and visualization of the results.

## Setup

To run this notebook, you will need to have Python installed along with the following libraries:

-   `numpy`
-   `matplotlib`

You can install them using pip:
