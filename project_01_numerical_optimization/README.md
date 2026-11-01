# Project 1 — Numerical Optimization Algorithms

## Overview

This project investigates the implementation and numerical performance of classical optimization algorithms, with an emphasis on nonlinear and non-convex optimization problems.

The objective is to understand how different algorithms behave in terms of convergence, computational efficiency, and sensitivity to initial conditions.

## Algorithms

The following methods will be implemented:

1. Gradient Descent
2. Newton's Method
3. BFGS (Broyden–Fletcher–Goldfarb–Shanno)
4. L-BFGS (Limited-memory BFGS)

## Benchmark Functions

The algorithms will be evaluated using:

- Rosenbrock function
- Himmelblau's function
- Rastrigin function

## Evaluation Criteria

- Convergence rate
- Number of iterations
- Final objective function value
- Gradient norm
- Computational time
- Sensitivity to initial conditions

## Mathematical Background

The problem is formulated as an unconstrained optimization problem:

\[
\min_{x\in\mathbb{R}^n} f(x)
\]

where \(f\) is a differentiable objective function.

The algorithms use gradient and, where applicable, Hessian information to iteratively approach a local minimizer.

## Project Structure

```text
project_01_numerical_optimization/
├── README.md
├── src/
├── notebooks/
├── experiments/
└── results/
```

## Current Status

<text>In progress — implementation and testing will begin with Gradient Descent.</text>

## References

References to textbooks, research papers, and relevant numerical optimization literature will be added as the project develops.
