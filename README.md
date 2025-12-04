# Insurance Analytics Projects  
Author: Mobasshira Zaman  
Ph.D. Student, Industrial Engineering – Arizona State University  

This repository contains two actuarial modeling projects using R for insurance analytics.

---

## 📌 Project 1 – Motor Claim Frequency (GLM)
Dataset: `freMTPL2freq.xlsx`  
Methods: Poisson GLM, Quasi-Poisson, Offset for exposure  

Files:
- `Project1.Rmd` – Model building & analysis  
- `Project1.html` – Rendered output  

---

## 📌 Project 2 – Workers’ Compensation Loss Reserving
Dataset: 'wkcomp_pos.xlsx'
Methods: Chain Ladder, Mack, GLM incremental approach  

Files:
- `Loss Reserving Analysis of Workers’ Compensation Claims.Rmd` – Model building & analysis  
- `Loss Reserving Analysis of Workers’ Compensation Claims.html` – Rendered output  

---

## 🔧 Requirements
```r
install.packages(c("tidyverse","readxl","ChainLadder","dplyr","ggplot2"))
