<div align="center">

# Data Programming: PyTorch Study Materials

Created by **Prof. Yoontae Hwang** (Pusan National University)

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch 2.x](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

<br/>

## Overview

This repository contains study materials and hands-on Jupyter notebooks for students learning PyTorch. The focus here is not just on writing code that runs, but on understanding how to write efficient, optimized, and scalable deep learning code for research and production environments. 

Standard tutorials often overlook the system-level details of PyTorch. These modules are designed to help you practice vectorizing loops into tensor operations, designing distributed training workflows even on basic hardware, and implementing core architectural components from scratch.

<br/>

## Study Modules

*Note: Modules 3, 4, and 5 are currently being updated for the latest semester.*

| Module | Topic | Status | Key Contents |
| :--- | :--- | :---: | :--- |
| **Module 1** | **Data Pipelines** | ✅ | Designing Custom Datasets/DataLoaders, implementing batch-level augmentations like MixUp and CutMix. |
| **Module 2** | **Time-Series Data** | ✅ | Understanding sliding window logic, train/val splits for temporal data, and implementing TSLib-style dataset structures. |
| **Module 3** | **Equation Optimization** | 🔄 | Replacing Python loops with broadcasting/masking, handling numerical stability (`logsumexp`), and using `torch.compile`. |
| **Module 4** | **Distributed Training** | 🔄 | Designing DDP (DistributedDataParallel) workflows, `torchrun`, and simulating distributed environments on a single CPU. |
| **Module 5** | **Layer Architectures** | 🔄 | Manual assembly of normalization layers (BatchNorm, LayerNorm) and building tiny Transformer blocks with positional encoding. |

<br/>

## Who is this for?

These materials are intended for students and researchers who already have a basic understanding of PyTorch (`Tensor`, `nn.Module`, basic training loops) but want to level up their programming skills. If you want to stop copy-pasting models and start understanding the underlying mechanics of high-performance code, this study guide is for you.

<br/>

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/[YOUR_ID]/[REPO_NAME].git
cd [REPO_NAME]
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
We recommend starting with Module 1 and working your way through the notebooks sequentially.

<br/>

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
