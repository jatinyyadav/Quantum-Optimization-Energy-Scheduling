# Quantum-Optimization-Energy-Scheduling
A research project developing a quantum-assisted framework for multi-objective optimization of sustainable energy grid


# Quantum-Assisted Multi-Objective Optimization for Sustainable Energy Scheduling

This repository contains the research and code for my paper on using quantum computing to solve a complex, real-world optimization problem: scheduling a sustainable energy grid.

### Problem Statement

Modern power grids must balance three often-competing objectives:
1.  **Minimize Cost:** The operational cost of generating power.
2.  **Minimize Emissions:** The environmental impact, especially from fossil fuels.
3.  **Meet Load Demand:** Ensure grid stability by matching power supply to consumer demand.

This is a multi-objective optimization problem that becomes computationally intractable for classical computers as the grid size increases.

### Proposed Method

We formulate this problem as a **Quadratic Unconstrained Binary Optimization (QUBO)** model. This allows us to map the problem onto a quantum computer's architecture. We then propose using a hybrid quantum-classical algorithm, such as the **Quantum Approximate Optimization Algorithm (QAOA)**, to find Pareto-optimal solutions that represent the best possible trade-offs between our three objectives.

### Current Status

- [✅] Mathematical formulation of the objective functions (Cost, Emissions, Load) is complete.
- [🚧] Code for converting the problem into a QUBO model is in progress.
- [⬜] Implementation of the QAOA solver is the next step.

This project aims to demonstrate the potential of quantum computing to find superior solutions for a critical sustainability challenge.
