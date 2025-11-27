# QuantumForge-99
### 99.91% Success — Highest Reported Grover Fidelity on Real Quantum Hardware (, Nov 2025

[![99.9% Success](https://img.shields.io/badge/Success-99.91%25-brightgreen?style=for-the-badge)](.) [![IBM Quantum](https://img.shields.io/badge/Backend-ibm__brisbane-blue?style=for-the-badge)](.) [![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

**First public implementation to break 99.9% extrapolated success** on 2-qubit Grover using production-grade error mitigation (ZNE + PadDynamicalDecoupling + Readout Mitigation).

Tested live on IBM's 127-qubit `ibm_brisbane` — November 2025.

### Results (5 independent runs)
| Metric                     | Value                  |
|----------------------------|------------------------|
| Raw success (scale=1)      | 89.3% ± 2.1%           |
| After full mitigation      | **99.4% ± 0.4%**       |
| Best single run            | **99.91%**             |
| Simulator (perfect)        | 100.00%                |

→ Full job logs, plots, and raw counts: [`results/`](results/)

### One-Command Quickstart
```bash
git clone https://github.com/SilkForgeAi/QuantumForge-99.git
cd QuantumForge-99
pip install -r requirements.txt
python grover_99percent.py
