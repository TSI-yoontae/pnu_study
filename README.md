# Data Programming: PyTorch & Convex Optimization Study Materials

Created by **Prof. Yoontae Hwang** (Pusan National University)

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch 2.x](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains study materials and hands-on Jupyter notebooks for students learning PyTorch and Mathematical Optimization. The curriculum focuses on writing efficient, optimized, and scalable code suitable for both research and production environments.

The repository is divided into two independent tracks:
1. **PyTorch Track**: Focuses on system-level deep learning details, from vectorizing tensor operations to designing distributed training workflows.
2. **Convex Optimization Track**: A standalone mathematical optimization course covering theoretical foundations, advanced practical examples, and first-order optimization methods.

---

## Track 1: PyTorch Study Modules

*Note: Modules 3, 4, 5, and 6 are currently being updated for the latest semester.*

| Module | Topic | Status | Key Contents |
| :--- | :--- | :---: | :--- |
| **Module 1** | **Data Pipelines** | ✅ | Custom Datasets/DataLoaders, batch-level augmentations (MixUp/CutMix). |
| **Module 2** | **Time-Series Data** | ✅ | Sliding window logic, temporal train/val splits, and TSLib-style structures. |
| **Module 3** | **Equation Optimization** | 🔄 | Broadcasting/masking, numerical stability (`logsumexp`), and `torch.compile`. |
| **Module 4** | **Distributed Training** | 🔄 | DDP (DistributedDataParallel) workflows and `torchrun` simulations. |
| **Module 5** | **Layer Architectures** | 🔄 | Manual implementation of Norm layers and building Transformer blocks. |
| **Module 6** | **Optimizers** | 🔄 | Analysis of optimization algorithms (SGD, Adam, AdamW) and LR scheduling. |

---

## Track 2: Convex Optimization (Independent Track)

*This track is designed to be self-contained and provides comprehensive code examples for mathematical optimization.*

| Module | Topic | Key Contents |
| :--- | :--- | :--- |
| **Module 1** | **Convex Function** | Definitions, properties, and basic code implementations of convex functions. |
| **Module 2-1** | **Opt. Examples I** | LP (Linear), QP (Quadratic), SDP (Semidefinite), and Robust optimization. |
| **Module 2-2** | **Opt. Examples II** | Portfolio Optimization, Optimal Control, and Logistic Regression. |
| **Module 2-3** | **Opt. Examples III** | Lagrange Duality and theoretical foundations. |
| **Module 3-1** | **First-Order Methods I** | Steepest Descent, Learning Rate Analysis. |
| **Module 3-2** | **First-Order Methods II** | Optimization trajectory and loss landscape Visualization. |
| **Module 3-3** | **First-Order Methods III** | Optimizer Comparison across different objective functions. |
| **Module 3-4** | **Advanced Methods** | Proximal Gradient, Projected Gradient, Frank-Wolfe, Coordinate Descent. |

---

## Target Audience

These materials are intended for students and researchers who have a basic understanding of Python and PyTorch (`Tensor`, `nn.Module`, basic training loops) but want to master high-performance programming, modern AI architectures, and the underlying mathematical mechanics of optimization.

## Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/TSI-yoontae/pnu_study.git](https://github.com/TSI-yoontae/pnu_study.git)
cd pnu_study
