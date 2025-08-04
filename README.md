# Cogni-e-SpinDB 1.0: Open Dataset of Electrospinning Parameter Configurations and Resultant Nanofiber Morphologies

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-in%20review-blue.svg)

This repository provides the **search strategies**, **exploratory data analysis (EDA)**, and **machine learning (ML) modeling** used for a data descriptor paper for Cogni-e-SpinDB 1.0 data.

---

## 📑 Table of Contents

1. [Overview](#overview)
2. [Search Terms](#search-terms)
3. [Repository Structure](#repository-structure)
4. [How to Use](#how-to-use)
5. [Notes](#notes)
6. [Contact](#contact)

---

## 📖 Overview

Electrospinning is a versatile technique for producing nanofibers, and process control plays a crucial role in tuning fiber morphology and multi-layered architectures.  
This repository documents the exact **search strategies** used to identify research publications related to:

- General electrospinning
- Process control in electrospinning
- Multi-layer process control
- Multi-parameter process control

---

## 🔍 Search Terms

### 1. Electrospinning (Total)

TS=(electrospinning OR “electro-sprayed” OR “electro-fabrication” OR “electrostatic spinning”)

### 2. Electrospinning Process Control

TS=(electrospinning OR “electro-sprayed” OR “electro-fabrication” OR “electrostatic spinning”)
AND TS=(control OR “feedback control” OR “closed-loop control” OR “process control”
OR “parameter control” OR “parameter tuning” OR “process optimization”)

### 3. Multi-layer Process Control

TITLE-ABS-KEY (electrospinning OR “electro-sprayed” OR “electro-fabrication” OR “electrostatic spinning”)
AND TITLE-ABS-KEY (control OR “feedback control” OR “closed-loop control” OR “process control”
OR “parameter control” OR “parameter tuning” OR “process optimization”)
AND TITLE-ABS-KEY (multilayer OR “Multilayered” OR “layers” OR “layered” OR “Sandwich”
OR “multi-walled” OR “Cross layer” OR “Poly laminate” OR “multi-level”)

### 4. Multi-parameter Process Control

TITLE-ABS-KEY (electrospinning OR “electro-sprayed” OR “electro-fabrication” OR “electrostatic spinning”)
AND TITLE-ABS-KEY (control OR “feedback control” OR “closed-loop control” OR “process control”
OR “parameter control” OR “parameter tuning” OR “process optimization”)
AND TITLE-ABS-KEY (Multiparameter OR “Multivariable” OR “multi-input” OR “multivariate” OR “multiplex”
OR “multicomponent” OR “multifactorial” OR “Poly parameter” OR “multidimensional”
OR “n-dimensional” OR “multicriteria” OR “multi-argument”)

---

## 📂 Repository Structure

| File                    | Description                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| `requirements.txt`      | Python dependencies required to run the notebooks.                                          |
| `eda.ipynb`             | Exploratory Data Analysis notebook exploring distributions, correlations, and basic trends. |
| `tail_analysis.ipynb`   | Tail analysis applied to average fiber diameter in the dataset.                             |
| `pvdf_regression.ipynb` | ML regression model trained on PVDF nanofiber data.                                         |
| `pva_regression.ipynb`  | ML regression model trained on PVA nanofiber data.                                          |

---

## ⚙️ How to Use

1. **Clone the repository**:

```bash
git clone https://github.com/taltechloc/Cogni-e-SpinDB.git
cd cogni-e-spindb
```

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

Open Jupyter notebooks to explore the data and models:

- eda.ipynb
- tail_analysis.ipynb
- pvdf_regression.ipynb
- pva_regression.ipynb

---

## 📝 Notes

- **TS** = Topic Search in Clarivate (Web of Science).
- **TITLE-ABS-KEY** = Title, Abstract, and Keyword search in Scopus.
- These queries were designed to capture the **broadest relevant literature**.

---

📬 Contact
For questions or collaboration inquiries, please contact:
📧 mehrab.mahdian@taltech.ee
