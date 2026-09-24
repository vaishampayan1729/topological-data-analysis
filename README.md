# Topological Data Analysis

A computational laboratory for learning **Topological Data Analysis (TDA)** through mathematical concepts, implementations, experiments, and applications.

The goal of this repository is to study TDA **in action**: each mathematical idea will be accompanied by computational experiments that make the construction visible and testable.

## Topics

The repository will develop through the following progression:

1. Metric spaces and point clouds
2. Simplicial complexes
3. Chains, cycles, and boundaries
4. Homology
5. Vietoris–Rips complexes
6. Čech complexes
7. Filtrations
8. Persistent homology
9. Persistence diagrams and barcodes
10. Distances between persistence diagrams
11. Representations of persistence
12. TDA and machine learning

## Computational Tools

The main Python libraries used in this repository are:

- **Ripser** — persistent homology, especially for point-cloud data
- **Persim** — persistence diagrams, distances, and visualizations
- **GUDHI** — computational topology and a broader collection of complexes and filtrations

## Philosophy

The guiding principle is:

> Learn the mathematics by doing the mathematics.

The notebooks will therefore emphasize:

- concrete examples
- computational experiments
- visualizations
- comparison between mathematical expectations and computation
- experiments with noise and different parameters
- connections between topology and data

For important definitions, we will use examples and non-examples whenever appropriate.

## Repository Structure

```text
topological-data-analysis/
├── README.md
├── requirements.txt
├── environment.yml
├── .gitignore
│
├── notebooks/
│   ├── ripser/
│   ├── persim/
│   └── gudhi/
│
├── code/
├── figures/
├── examples/
└── projects/
```

## Learning Path

The notebooks will be developed progressively rather than all at once.

The mathematical development will come first, followed by increasingly sophisticated computational experiments using Ripser, Persim, and GUDHI.

Eventually, the repository will also explore applications of TDA to data analysis and machine learning.
