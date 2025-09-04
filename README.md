# Stochastic Graph Simulations and Monte Carlo Experiments

## Overview
This repository contains a Python project that implements Dijkstra's algorithm to find the shortest path between two nodes in a graph, with a focus on **stochastic edge weights**. The project explores two scenarios:

1. Randomized weights on edges.  
2. Edge weights that evolve over time according to a Geometric Brownian Motion (GBM) model.

## Features
- Compute shortest distance using Dijkstra's algorithm.  
- Use Monte Carlo simulations to estimate expected shortest path lengths.  
- Simulate dynamic edge weights using Geometric Brownian Motion.  
- Visualize the evolution of the shortest path over time.

## Installation
```bash
git clone https://github.com/thdnder/stochastic_shortest_path.git
cd stochastic_shortest_path
pip install numpy matplotlib networkx
