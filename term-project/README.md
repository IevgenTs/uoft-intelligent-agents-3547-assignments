# Intelligent Agents Term Project – Software Release Planning Agent

This directory contains artifacts from the individual term project completed as part of  
**SCS 3547 – Intelligent Agents** at the **University of Toronto School of Continuing Studies**,  
within the **Artificial Intelligence Certificate Program**.

---

## Project Overview

The goal of this project is to design an **intelligent agent for software release planning**, where the agent selects an optimal subset of backlog items to include in a release under multiple constraints.

The problem is formulated as a **combinatorial optimization task**, balancing factors such as:
- Feature value
- Development cost
- Dependencies between features
- Limited release capacity

Given the size of the search space and the presence of constraints, the solution is implemented using a **Genetic Algorithm (GA)**.

---

## Approach

The release planning agent is modeled using evolutionary computation techniques:

- Candidate releases are encoded as binary chromosomes
- A fitness function evaluates solution quality based on total value and constraint satisfaction
- Genetic operators (selection, crossover, mutation) are applied to evolve better solutions over generations
- Constraint violations are handled through penalty mechanisms

This approach allows the agent to efficiently explore a large and complex search space and converge toward high-quality release plans.

---

## Implementation Highlights

- Custom chromosome representation for backlog items
- Fitness function incorporating value, cost, and penalties
- Configurable GA parameters (population size, mutation rate, number of generations)
- Empirical evaluation of convergence behavior and solution quality

---

## Contents

- `slides/`  
  Final project presentation summarizing problem formulation, approach, experiments, and results.

- `agent-implementation/`  
  Notebook containing the full implementation of the genetic-algorithm-based release planning agent.

---

## Notes

This project was completed **individually**.  
All code and analysis included in this directory were authored by me.

The focus of the project is on **agent design and decision-making**, rather than on UI or production deployment.
