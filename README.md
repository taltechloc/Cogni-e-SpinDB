# Cogni-e-SpinDB 1.0: open dataset of electrospinning parameter configurations and resultant nanofiber morphologies

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-in%20review-blue.svg)

This repository provides the **search strategies, exploratory data analysis (EDA)**, amd **ML modeling** used for a data descriptor paper submitted to *Scientific Data*.

---

## 📑 Table of Contents  
1. [Overview](#overview)
2. [Search Terms](#search-terms)  
    
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
## 📝 Notes
- **TS** = Topic Search in Clarivate (Web of Science).
- **TITLE-ABS-KEY** = Title, Abstract, and Keyword search in Scopus.
- These queries were designed to capture the **broadest relevant literature**.

---
