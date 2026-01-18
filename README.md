MATLAB Code for Q-CSCM

This repository contains the source code for the paper:

Operator Spectral Stability Theory and Chebyshev Spectral Collocation Method for Time-Varying Bilateral Quaternion Dynamical Systems
Applied Mathematics and Computation

Quick Start

The code is tested on **MATLAB R2023b**. No additional toolboxes are required.

Run the following main scripts to reproduce the figures and results in the paper:

| Script Name | Reproduces | Description |
| :--- | :--- | :--- |
| **`section1.m`** | **Figure 1** | Convergence analysis (Q-CSCM vs. RK4) and CPU time comparison. |
| **`section2.m`** | **Figure 2, 3** | Parametric Floquet stability analysis and Scalar-Vector separation verification. |
| **`section3_1.m`** | **Figure 4–7** | Nonlinear Riccati oscillator: Phase portraits and perturbation analysis. |
| **`section3_2.m`** | **Figure 8, 9** | **Heteroclinic Continuation**. Also generates the animation (`heteroclinic_slow.gif`). |
| **`section3_3.m`** | **Figure 10, 11** | Solutions for the classical Wilczyński benchmark problem. |

Notes
*   All helper functions (e.g., `cheb_*.m`, `qmult_*.m`) are located in the root directory.
*   Please ensure all files are in the same MATLAB path before running.

Contact
For questions, please contact: **Jianwen Zhou** (jwzhou@ynu.edu.cn)
