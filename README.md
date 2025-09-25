# Error Mitigation in the NISQ Era: Applying Measurement Error Mitigation Techniques to Enhance Quantum Circuit Performance

[![DOI](https://img.shields.io/badge/DOI-10.3390/math12142235-blue)](https://doi.org/10.3390/math12142235)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## 📄 About
This repository contains the code, data, and figures supporting the publication:  

> **M.U. Khan, M.A. Kamran, W.R. Khan, M.M. Ibrahim, M.U. Ali, S.W. Lee (2024).**  
> *Error Mitigation in the NISQ Era: Applying Measurement Error Mitigation Techniques to Enhance Quantum Circuit Performance.*  
> Mathematics, 12(14), 2235.  
> DOI: [10.3390/math12142235](https://doi.org/10.3390/math12142235)

The work explores error mitigation techniques (Dynamic Decoupling, T-REx, Zero-Noise Extrapolation) on **IBM Kyoto**, **IBM Osaka**, and **QASM simulator**, focusing on **Trotterized Quantum Circuits (QTCs)**.

---

## 📂 Repository Structure
```
Error-Mitigation-NISQ/
│── README.md                # Main documentation
│── LICENSE                  # CC BY 4.0 or MIT
│── requirements.txt         # Python dependencies
│── notebooks/               # Jupyter notebooks
│   ├── error_mitigation_graphs.ipynb
│   ├── Error_mitigation_graphs_python_codes.ipynb
│   ├── error_mitigation_ibm_kyoto(127bit)_qasm_simulator.ipynb
│   ├── error_mitigation_ibm_osaka_ibmq(127bit)_qasm_simulator.ipynb
│── data/                    # Calibration and raw data
│   ├── ibm_kyoto_calibrations_2024-07-07.csv
│   ├── ibm_osaka_calibrations_2024-07-05.csv
│── figures/                 # Figures for results
│   ├── CaseA-1.png
│   ├── CaseA-2.png
│── paper/                   # Reference to published paper
│   ├── mathematics-12-02235-v2.pdf
```

---

## ⚙️ Requirements
- Python 3.9+  
- Qiskit  
- NumPy, SciPy, Matplotlib, Pandas, Seaborn  

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## ▶️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/mishaurooj/Quantum-Error-Mitigation-in-the-NISQ-Era.git
   cd Error-Mitigation-NISQ
   ```
2. Open the notebooks in `notebooks/` to reproduce the experiments.  
3. Figures will be generated in the `figures/` directory.  

---

## 📊 Results
- Error mitigation significantly improved expectation values and variances across IBM Kyoto and Osaka.  
- Example improvements:  
  - **IBM Kyoto (T-REx):** Expectation values improved from **0.09 → 0.35**  
  - **IBM Osaka (Dynamic Decoupling):** Expectation values improved from **0.2492 → 0.3788**  
- Results aligned closer with **QASM simulator** baselines.

---

## 📜 License
This repository follows the **Creative Commons Attribution (CC BY 4.0)** license — consistent with the MDPI publication license.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---
