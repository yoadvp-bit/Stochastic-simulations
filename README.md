# Discrete Event Simulation for Queueing Systems

This repository implements **Discrete Event Simulation (DES)** to analyze queueing systems and evaluate the impact of various factors such as scheduling strategies, service time distributions, and traffic intensity on queue performance.

---

## Table of Contents

1. [Overview](#overview)  
2. [Simulation Details](#simulation-details)  
   - [Queueing Configurations](#queueing-configurations)  
   - [Objectives](#objectives)  
3. [Requirements](#requirements)  
4. [License](#license)  

---

## Overview

Queueing theory provides a framework for analyzing waiting lines and system performance. In this project, we use **Discrete Event Simulation (DES)** to study:

1. **Queue Configurations**:  
   - Single-server M/M/1 and multi-server M/M/n systems.  
   - Deterministic M/D/n and hyperexponential M/H2/n service times.  

2. **Scheduling Strategies**:  
   - **FIFO (First-In, First-Out)**: Jobs are processed in the order they arrive.  
   - **SJF (Shortest Job First)**: Shorter jobs are prioritized.  

3. **Traffic Intensity ($\rho$)**:  
   The ratio of arrival rate ($\lambda$) to service rate ($\mu$), which directly impacts performance.

4. **Performance Metrics**:  
   - Average waiting time.  
   - Server utilization.  
   - Queue length distribution.  

---

## Simulation Details

### Queueing Configurations

We simulate the following scenarios:
- **M/M/1 vs. M/M/n**: Single vs. multi-server systems to explore the impact of adding servers on waiting times.
- **FIFO vs. SJF Scheduling**: Comparing job scheduling strategies under identical conditions.
- **M/D/n vs. M/H2/n**: Impact of deterministic vs. hyperexponential service times on system performance.

### Objectives

The primary goals of the simulation are:
1. Validate queueing theory predictions for average waiting times in M/M/1 and M/M/n systems.
2. Assess the performance of FIFO vs. SJF scheduling strategies.
3. Evaluate how deterministic M/D/n and hyperexponential M/H2/n service times affect performance metrics.
4. Understand how traffic intensity ($\rho$) influences system behavior.

## Requirements

The project requires the following Python packages:

- `Simpy`
- `numpy`
- `matplotlib`
- `scipy`
- `random`

Install dependencies using:

```bash
pip install simpy numpy matplotlib scipy random
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

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
