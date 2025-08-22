# The Role of Entanglement in Quantum Reservoir Computing with Coupled Kerr Nonlinear Oscillators

This repository contains the Julia code and scripts used in the paper:  
**"The Role of Entanglement in Quantum Reservoir Computing with Coupled Kerr Nonlinear Oscillators"** (arXiv:2508.11175).

---

## 📌 Overview
We implement a **Quantum Reservoir Computing (QRC) framework** based on **two coupled Kerr nonlinear oscillators** to study time-series prediction tasks.  
The repository reproduces the main results of the paper, including:

- Simulation of Kerr oscillator dynamics under **dissipation and dephasing**  
- Input encoding through coherent drive  
- Linear readout training for prediction tasks  
- Quantification of entanglement via **logarithmic negativity**  
- Performance evaluation using **Normalized Root Mean Square Error (NRMSE)**  
- Analysis of how entanglement correlates with predictive advantage  

---

## 🛠 Requirements
- Julia `>= 1.9`
- Several Julia libraries which are listed in the notebooks.

To install dependencies:
```julia
using Pkg
Pkg.add([
    "QuantumOptics",
    "PyPlot",
    ...
])
```
---
## 📊 Instructions

To reproduce the key results from the paper:  
	-	Fig. 2 and data generation for the whole paper: [Simulation.ipynb](https://github.com/alikauc/Kerr_Coupled_QRC-Paper-/blob/main/Simulation.ipynb)  
	-	Fig. 3-11: Use data from [saved_data.zip](https://github.com/alikauc/Kerr_Coupled_QRC-Paper-/blob/main/saved_data.zip) and run notebook [figs3to11.ipynb](https://github.com/alikauc/Kerr_Coupled_QRC-Paper-/blob/main/figs3to11.ipynb).  
 
---
## Citation
You can cite this code by using this link.
[![DOI](https://img.shields.io/badge/DOI:-10.48550/arXiv.2508.11175-green)](https://doi.org/10.48550/arXiv.2508.11175)
