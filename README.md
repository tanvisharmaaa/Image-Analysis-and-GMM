# Image Analysis and Gaussian Mixture Models (GMM) from Scratch

This project demonstrates statistical image analysis and the implementation of Gaussian Mixture Models (GMM) from scratch using Python. It includes:

1. Statistical comparison of grayscale image distributions using metrics such as Kolmogorov-Smirnov, Cross-Entropy, KL Divergence, and JS Divergence.
2. Implementation of GMM with Expectation-Maximization (EM) algorithm, along with visualization of the clustering process.

---

## Overview

### Task 1: Statistical Image Analysis
- **Goal**: Compare grayscale image distributions.
- **Methods Used**:
  - Kolmogorov-Smirnov Test
  - Cross-Entropy
  - KL Divergence
  - JS Divergence
- **Results**: The analysis indicates a close similarity between the images based on divergence metrics.

### Task 2: Gaussian Mixture Models (GMM)
- **Goal**: Implement GMM using the Expectation-Maximization algorithm.
- **Approach**:
  - Generate a synthetic 3D dataset with close clusters.
  - Implement E-step and M-step for iterative optimization.
  - Visualize clusters over iterations.
- **Outcome**: Successfully identified clusters and improved convergence over multiple iterations.

---

## Key Features
- Implementation of GMM from scratch without using ML libraries.
- Statistical comparison of image distributions with in-depth analysis.
- Visualization of clustering results.

---

## Files
- `Image_Analysis.ipynb`: Jupyter Notebook containing the code for both tasks.
- `Images for Analysis/`: Example datasets used in the project.

---

## Getting Started

### Prerequisites
- Python 3.9
- Libraries: `numpy`, `scipy`, `matplotlib`

### Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/tanvisharmaaa/Image-Analysis-and-GMM.git

