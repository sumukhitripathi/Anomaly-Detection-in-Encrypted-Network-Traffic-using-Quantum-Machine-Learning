# Anomaly Detection in Encrypted Network Traffic using Quantum Machine Learning

**Anomaly detection in encrypted network traffic**, leveraging **Quantum Machine Learning (QML)**—implemented via **Variational Quantum Circuits (VQCs)** and hybrid models using **Pennylane** and Qiskit.

---

##  Project Overview

This repository explores **quantum machine learning techniques** for detecting anomalies in encrypted network traffic. 
The primary focus is on applying **quantum classifiers** and **variational circuits** to the domain of network security, experimenting with various quantum architectures.

##  Structure & Notebooks

- `Project details.docx` – Project overview, objectives, code explanations at each stage, problems encountered, etc.
- **Quantum ML Notebooks**:
  - `QML_implementation_qsvc.ipynb`, `qml_qsvc_2.ipynb`
  - `QML_VQC.ipynb`, `VQC_2.ipynb`
  - `pennylane_svc.ipynb`, along with versions `_2`, `_3`, `_4`
  - `pennylane_vqc.ipynb`, and variants `_2`, `_3`, `_4`


Each notebook implements QML models using quantum support vector classifiers (`qsvc`) and variational quantum circuits (`vqc`) using QISKIT and PENNYLANE.

##  Requirements

- Python 3.8 or above
- Required packages (install via pip):
  ```bash
  pip install pennylane pennylane-qiskit qiskit numpy pandas scikit-learn matplotlib
