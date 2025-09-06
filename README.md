# Riemann Sum Approximation of the Beta Function in R

This mini-project demonstrates how to approximate the Beta function \( B(\alpha, \beta) \) using a custom Riemann sum implementation in R. It compares the results to R's built-in `beta()` function to evaluate accuracy.

## Features

- Defines a reusable `mybeta()` function for approximation via Riemann sums
- Compares outputs of `mybeta()` and `beta()` for:
  - α = 3, β = 5
  - α = 0.5, β = 0.5 (which should equal π)
- Discusses numerical issues such as divergence for non-integrable cases

## Key Concepts

- Numerical integration
- Riemann sums
- Special functions (Beta function)
- Floating-point precision in R

This is a helpful exercise for understanding both **numerical methods** and **limitations of integration techniques** in practice.
