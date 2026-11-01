# Computational Mathematics for Space Applications

**Numerical Optimization · Scientific Computing · Optimal Control**

This repository explores the application of computational mathematics to simplified problems in space science and engineering.

The main objective is to study, implement, and evaluate mathematical and numerical methods for solving optimization, dynamical systems, and trajectory-planning problems.

Rather than focusing on aerospace hardware or engineering design, this portfolio emphasizes the mathematical foundations behind computational solutions, including algorithm development, numerical analysis, mathematical modeling, and optimization.

## Research Interests

The repository focuses on three interconnected areas:

- **Numerical Optimization:** Gradient-based and quasi-Newton methods, convergence analysis, and constrained optimization.
- **Scientific Computing:** Numerical solutions of ordinary differential equations, numerical stability, accuracy, and error analysis.
- **Optimal Control:** Mathematical formulation and numerical optimization of dynamical systems and spacecraft trajectories.

## Project Roadmap

### Project 1 — Numerical Optimization Algorithms

**Objective:** Implement and compare numerical optimization algorithms, with particular attention to their convergence behavior on nonlinear and non-convex problems.

Methods:
- Gradient Descent
- Newton's Method
- BFGS
- L-BFGS

Benchmark functions:
- Rosenbrock function
- Himmelblau's function
- Rastrigin function

Research questions:
- How do different optimization algorithms behave on non-convex functions?
- How does the initial point affect convergence?
- What are the trade-offs between convergence speed, accuracy, and computational cost?

### Project 2 — Numerical Orbit Simulation

**Objective:** Investigate numerical methods for simulating satellite motion using simplified orbital dynamics.

Methods:
- Euler Method
- Second-Order Runge–Kutta (RK2)
- Fourth-Order Runge–Kutta (RK4)

Topics:
- Two-body orbital dynamics
- Numerical integration
- Local and global truncation errors
- Numerical stability
- Energy conservation

Research question:

How do different numerical integration methods affect the accuracy and long-term stability of satellite orbit simulations?

### Project 3 — Spacecraft Trajectory Optimization

**Objective:** Formulate and solve simplified spacecraft trajectory optimization problems using numerical optimization and optimal control techniques.

Topics:
- Mathematical modeling of spacecraft dynamics
- Objective functions and constraints
- Constrained nonlinear optimization
- Initial conditions and solver sensitivity
- Numerical optimal control

Tools:
- SciPy
- CasADi

Research question:

How can numerical optimization methods be used to determine efficient spacecraft trajectories under dynamical and operational constraints?

## Mathematical Foundations

The projects build on concepts from:

- Nonlinear and numerical optimization
- Linear algebra
- Numerical analysis
- Ordinary differential equations
- Dynamical systems
- Mathematical modeling
- Optimal control theory
- Computational methods

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Scientific programming |
| NumPy | Numerical computations |
| SciPy | Optimization and numerical methods |
| Matplotlib | Visualization |
| Pandas | Data analysis |
| Jupyter Notebook | Computational experiments |
| CasADi | Optimization and optimal control |

## Repository Structure

```text
computational-mathematics-for-space-applications/
│
├── README.md
│
├── project_01_numerical_optimization/
│
├── project_02_orbit_simulation/
│
├── project_03_trajectory_optimization/
│
└── references/
```

Each project will contain its mathematical formulation, implementation, computational experiments, results, and references.

## Current Status

This repository is under development.

The first project will focus on implementing and benchmarking classical numerical optimization algorithms. Subsequent projects will extend these methods to dynamical systems and spacecraft trajectory optimization.

## Author

**Fatemeh Khawari**

MSc in Applied Mathematics

Research interests: Numerical Optimization, Scientific Computing, Mathematical Modeling, and Optimal Control.

---

*The purpose of this portfolio is to explore how mathematical theory and computational methods can be translated into practical solutions for problems arising in space applications.*
