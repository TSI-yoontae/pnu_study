# Data Programming: PyTorch Study Materials

Created by **Prof. Yoontae Hwang** (Pusan National University)

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch 2.x](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains study materials and hands-on Jupyter notebooks for students learning PyTorch. The curriculum focuses on writing efficient, optimized, and scalable deep learning code suitable for both research and production environments.

Unlike standard tutorials, these modules emphasize system-level details: vectorizing tensor operations, designing distributed training workflows, and implementing core architectural components from the ground up.

## Study Modules

*Note: Modules 3, 4, and 5 are currently being updated for the latest semester.*

| Module | Topic | Status | Key Contents |
| :--- | :--- | :---: | :--- |
| **Module 1** | **Data Pipelines** | ✅ | Custom Datasets/DataLoaders, batch-level augmentations (MixUp/CutMix). |
| **Module 2** | **Time-Series Data** | ✅ | Sliding window logic, temporal train/val splits, and TSLib-style structures. |
| **Module 3** | **Equation Optimization** | 🔄 | Broadcasting/masking, numerical stability (`logsumexp`), and `torch.compile`. |
| **Module 4** | **Distributed Training** | 🔄 | DDP (DistributedDataParallel) workflows and `torchrun` simulations. |
| **Module 5** | **Layer Architectures** | 🔄 | Manual implementation of Norm layers and building Transformer blocks. |

## Target Audience

These materials are intended for students and researchers who have a basic understanding of PyTorch (`Tensor`, `nn.Module`, basic training loops) but want to master high-performance programming and the underlying mechanics of modern AI models.

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/TSI-yoontae/pnu_lectrue_data_programming.git
cd pnu_lectrue_data_programming
```

### 2. Set up the environment
Python 3.10 or higher and the latest version of PyTorch 2.x are recommended.
```bash
pip install torch torchvision torchaudio numpy pandas matplotlib jupyter
```

### 3. Run the notebooks
```bash
jupyter notebook
```
Modules should be completed sequentially to build a solid foundation.

## License

This project is licensed under the MIT License. 

---
