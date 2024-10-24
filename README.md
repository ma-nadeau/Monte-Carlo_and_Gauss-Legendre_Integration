# Monte Carlo and Gauss-Legendre Integration Methods

This repository contains implementations of two numerical integration techniques using MATLAB: **Monte Carlo Integration** and **Gauss-Legendre Quadrature**.

## Table of Contents
- [Introduction](#introduction)
- [Methods](#methods)
  - [Monte Carlo Integration](#monte-carlo-integration)
  - [Gauss-Legendre Quadrature](#gauss-legendre-quadrature)
- [Content](#content)

## Introduction

Numerical integration is a fundamental technique in applied mathematics and computational sciences. While exact analytical solutions to integrals may not always exist, numerical approaches can provide accurate approximations. This repository demonstrates two popular approaches:

1. **Monte Carlo Integration**: A probabilistic method relying on random sampling.
2. **Gauss-Legendre Quadrature**: A deterministic method using optimized sampling points (roots of Legendre polynomials).

## Methods

### Monte Carlo Integration

[Monte Carlo Integration](https://en.wikipedia.org/wiki/Monte_Carlo_integration) estimates the value of an integral by using random samples. It is particularly useful for higher-dimensional integrals or when the integration domain is irregular.

### Gauss-Legendre Quadrature

[Gauss-Legendre Quadrature](https://en.wikipedia.org/wiki/Gauss%E2%80%93Legendre_quadrature) is a more precise method, especially for integrals over fixed domains. It uses specific sample points and weights derived from the roots of [Legendre polynomials](https://en.wikipedia.org/wiki/Legendre_polynomials) to approximate the integral.

## Content
- `Report/writeup.pdf`: Summarizes the results of the numerical integration methods.
- `src/Monte_Carlo_and_Gauss_Legendre_Integration.mlx`: Contains the MATLAB code implementing the Monte Carlo and Gauss-Legendre integration techniques.


