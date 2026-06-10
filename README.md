# 🏥 Python for Health Informatics

> A structured, notebook-based curriculum bridging Python programming and real-world health informatics — from core fundamentals to applied clinical data workflows.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Health Informatics](https://img.shields.io/badge/Domain-Health%20Informatics-red)](https://github.com/Angelinamoses/python-for-health-informatics)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen)]()

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Learning Objectives](#learning-objectives)
- [Curriculum Overview](#curriculum-overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Sample Datasets](#sample-datasets)
- [Future Roadmap](#future-roadmap)
- [Contributing](#contributing)
- [License](#license)

---

## 🔬 About the Project

**Python for Health Informatics** is a hands-on, progressive learning resource designed for healthcare professionals, students, and developers who want to apply Python programming to health data problems.

Each notebook is built around **realistic clinical scenarios** — from processing outpatient clinic visit logs to structuring patient records — so you learn Python concepts while thinking like a health informaticist.

**Who is this for?**
- 🎓 Health informatics / biomedical informatics students
- 🏥 Clinical data analysts transitioning to Python
- 💻 Developers entering the healthcare data space
- 🔬 Researchers working with EHR or public health datasets

---

## 🎯 Learning Objectives

By completing this curriculum, you will be able to:

- Write clean, idiomatic Python code applicable to healthcare workflows
- Work with clinical datasets (CSV, structured records) using Python's standard library
- Design reusable functions and classes for patient data processing
- Handle errors gracefully in data pipelines common to health systems
- Read and write structured health data files (CSV, TXT reports)
- Apply object-oriented principles to model clinical entities (patients, visits, diagnoses)

---

## 📚 Curriculum Overview

| # | Notebook | Core Concepts | Health Informatics Application |
|---|----------|---------------|-------------------------------|
| 1 | `n1_python_fundamentals.ipynb` | Variables, types, operators, I/O | Patient demographics, vital signs data entry |
| 2 | `n2_control_flow.ipynb` | `if/else`, loops, conditions | Clinical decision rules, triage logic |
| 3 | `n3_data_structures.ipynb` | Lists, dicts, sets, tuples | Patient records, medication lists, lab results |
| 4 | `n4_functions.ipynb` | Function design, parameters, scope | Reusable clinical calculators (BMI, GFR, risk scores) |
| 5 | `n5_error_handling.ipynb` | `try/except`, custom exceptions | Robust data validation for EHR input |
| 6 | `n6_file_handling.ipynb` | CSV I/O, text files, paths | Reading clinic visit logs, generating reports |
| 7 | `n7_oop.ipynb` | Classes, inheritance, encapsulation | Modeling `Patient`, `Visit`, `Diagnosis` entities |

---

## 📁 Project Structure

```
python-for-health-informatics/
│
├── n1_python_fundamentals.ipynb     # Module 1 — Core Python syntax
├── n2_control_flow.ipynb            # Module 2 — Decision & iteration
├── n3_data_structures.ipynb         # Module 3 — Collections & data modeling
├── n4_functions.ipynb               # Module 4 — Modular programming
├── n5_error_handling.ipynb          # Module 5 — Robust exception management
├── n6_file_handling.ipynb           # Module 6 — File I/O with clinical data
├── n7_oop.ipynb                     # Module 7 — OOP for clinical entities
│
├── clinic_visits.csv                # Sample dataset — outpatient visit records
├── clinic_output.csv                # Generated output from file handling exercises
├── clinic_report.txt                # Sample text report output
│
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or higher
- Jupyter Notebook or JupyterLab

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Angelinamoses/python-for-health-informatics.git
cd python-for-health-informatics

# 2. (Recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install notebook pandas

# 4. Launch Jupyter
jupyter notebook
```

### Running in the Cloud (No Setup Required)

You can run all notebooks instantly via:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Angelinamoses/python-for-health-informatics/)
[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Angelinamoses/python-for-health-informatics/main)

---

## 📊 Sample Datasets

This repository includes a synthetic outpatient clinic dataset to demonstrate real-world data tasks:

| File | Description |
|------|-------------|
| `clinic_visits.csv` | Simulated outpatient visit records (patient ID, date, diagnosis, vitals) |
| `clinic_output.csv` | Processed/cleaned output generated by `n6_file_handling.ipynb` |
| `clinic_report.txt` | Human-readable summary report generated programmatically |

> ⚠️ **Note:** All data is **completely synthetic** and does not represent real patients or clinical encounters.

---

## 🗺️ Future Roadmap

### Phase 2 — Data Analysis & Visualization
- [ ] `n8_pandas_for_ehr.ipynb` — Pandas for structured clinical data (DataFrames, groupby, filtering)
- [ ] `n9_data_visualization.ipynb` — Matplotlib & Seaborn for clinical dashboards and trend charts
- [ ] `n10_numpy_statistics.ipynb` — NumPy for biostatistics and lab value analysis

### Phase 3 — Health Standards & Interoperability
- [ ] `n11_hl7_fhir_basics.ipynb` — Introduction to HL7 FHIR resources with Python's `fhirclient`
- [ ] `n12_icd_snomed_coding.ipynb` — Working with ICD-10 / SNOMED CT coding systems
- [ ] `n13_api_integration.ipynb` — Consuming health data APIs (FHIR servers, public health endpoints)

### Phase 4 — Applied Machine Learning in Healthcare
- [ ] `n14_predictive_modeling.ipynb` — Readmission risk prediction with scikit-learn
- [ ] `n15_nlp_clinical_notes.ipynb` — NLP basics for processing unstructured clinical text
- [ ] `n16_time_series_vitals.ipynb` — Time-series analysis of patient vitals

### Infrastructure & Quality
- [ ] Add `requirements.txt` and `environment.yml` for reproducible environments
- [ ] Set up GitHub Actions CI to validate all notebooks run without errors
- [ ] Add unit tests for utility functions using `pytest`
- [ ] Add CONTRIBUTING.md and issue/PR templates

---

## 🤝 Contributing

Contributions are welcome! Whether you're fixing a typo, adding a new health informatics example, or proposing a new module:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/add-pandas-module`
3. Commit your changes: `git commit -m 'Add Module 8: Pandas for EHR data'`
4. Push to the branch: `git push origin feature/add-pandas-module`
5. Open a Pull Request

Please ensure notebooks are cleared of output before submitting (`Kernel > Restart & Clear Output`).

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👩‍💻 Author

**Angelina Moses**
- GitHub: [@Angelinamoses](https://github.com/Angelinamoses)

---

*Built with a passion for making health data more accessible through code.*
