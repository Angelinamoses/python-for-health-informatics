# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-06-12

### Added
- **Phase 1 — Core Curriculum** ✅ COMPLETE
  - `n1_python_fundamentals.ipynb` — Variables, types, operators, I/O with patient demographics
  - `n2_control_flow.ipynb` — if/else, loops, conditions for clinical decision rules
  - `n3_data_structures.ipynb` — Lists, dicts, sets, tuples for patient records
  - `n4_functions.ipynb` — Function design for reusable clinical calculators
  - `n5_error_handling.ipynb` — try/except for robust EHR data validation
  - `n6_file_handling.ipynb` — CSV I/O for clinic visit logs and reports
  - `n7_oop.ipynb` — Classes for modeling Patient, Visit, Diagnosis entities

- **Synthetic Clinical Dataset**
  - `clinic_visits.csv` — Simulated outpatient visit records
  - Documentation for data structure and privacy notes

- **Cloud Deployment Support**
  - Google Colab integration badges
  - Binder support for instant cloud execution

- **Development Infrastructure**
  - GitHub Actions CI/CD workflow for notebook validation
  - `requirements.txt` for reproducible pip environments
  - `environment.yml` for conda users
  - Enhanced `.gitignore`
  - `CONTRIBUTING.md` with contribution guidelines
  - This `CHANGELOG.md`

### Roadmap

**Phase 2 — Data Analysis & Visualization** (Planned)
- `n8_pandas_for_ehr.ipynb` — Pandas for structured clinical data
- `n9_data_visualization.ipynb` — Matplotlib & Seaborn for clinical dashboards
- `n10_numpy_statistics.ipynb` — NumPy for biostatistics

**Phase 3 — Health Standards & Interoperability** (Planned)
- `n11_hl7_fhir_basics.ipynb` — Introduction to HL7 FHIR resources
- `n12_icd_snomed_coding.ipynb` — ICD-10 and SNOMED CT coding systems
- `n13_api_integration.ipynb` — Consuming health data APIs

**Phase 4 — Applied Machine Learning in Healthcare** (Planned)
- `n14_predictive_modeling.ipynb` — Readmission risk prediction
- `n15_nlp_clinical_notes.ipynb` — NLP for unstructured clinical text
- `n16_time_series_vitals.ipynb` — Time-series analysis of patient vitals

---

## Release Guidelines

- **Patch** (x.x.Z): Bug fixes, documentation updates
- **Minor** (x.Y.0): New notebooks, features, backward compatible
- **Major** (X.0.0): Breaking changes, significant restructuring

For more details, see [CONTRIBUTING.md](CONTRIBUTING.md).
