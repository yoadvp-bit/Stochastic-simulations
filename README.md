# Mandelbrot Set Area Estimation

This repository provides Python code for computing and visualizing the Mandelbrot set and estimating its area using various sampling techniques. These methods include Monte Carlo random sampling, Latin Hypercube Sampling (LHS), Orthogonal Sampling, and Importance Sampling with Antithetic Variates. The project also compares the accuracy and efficiency of these methods.

---

## Table of Contents

1. [Overview](#overview)  
2. [Requirements](#requirements)  
3. [License](#license)  

---

## Overview

The Mandelbrot set is a famous fractal defined in the complex plane. Its area estimation poses a challenge because the fractal boundary is infinitely complex. This project implements:

1. Recursive visualization of the Mandelbrot set.  
2. Estimation of the Mandelbrot set area using:  
   - **Monte Carlo Sampling**  
   - **Latin Hypercube Sampling (LHS)**  
   - **Orthogonal Sampling**  
   - **Importance Sampling with Antithetic Variates**  
3. Comparison of performance (variance, time, confidence intervals) between these methods.

---

## Requirements

The project requires the following Python packages:

- `numpy`
- `PIL` (Python Imaging Library)
- `matplotlib`
- `scipy`
- `smt` (for LHS sampling)

Install dependencies using:

```bash
pip install numpy matplotlib scipy pillow smt
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.
