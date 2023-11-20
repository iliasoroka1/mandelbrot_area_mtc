# Documentation

# Project Dependencies Documentation

This document provides a detailed list of external libraries and modules used in the project. Each dependency is accompanied by a brief description of its purpose and functionality.

## List of Dependencies

### 1. numpy
- **Description**: A package for scientific computing in Python.
- **Installation**: `pip install numpy`

### 2. matplotlib
- **Description**: A plotting library for Python and its numerical mathematics extension NumPy.
- **Installation**: `pip install matplotlib`

### 3. joblib
- **Description**: Provides tools for lightweight pipelining in Python.
- **Installation**: `pip install joblib`

### 4. numexpr
- **Description**: A fast numerical expression evaluator for NumPy, designed to improve performance by using multiple cores and minimizing memory usage.
- **Installation**: `pip install numexpr`

### 5. jax
- **Description**: An open-source library for high-performance machine learning research. Known for its numpy-like API and efficient computation of gradients.
- **Installation**: `pip install jax`

## Installation of Dependencies

Most dependencies can be installed using pip, Python's package installer. Example:

```bash
pip install numpy matplotlib joblib numexpr jax

## Introduction

This project focuses on the estimation of the Mandelbrot set area, a classic problem in computational mathematics and fractal geometry. The Mandelbrot set, named after mathematician Benoît Mandelbrot, is a complex and visually striking set of points that shows that simple rules can create complex structures.

## Methodology

The project employs various sampling techniques within the Monte Carlo framework. Each technique offers a unique approach to sampling, influencing both the accuracy and efficiency of the estimation process. The techniques used include:

- **Latin Hypercube Sampling (LHC)**

- **Orthogonal Sampling**

- **Stratified Sampling**

- **Pure Random Sampling**

- **Antithetic Variates**


