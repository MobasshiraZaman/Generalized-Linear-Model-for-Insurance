# Generalized Linear Modeling for Motor Claim Frequency

This repository contains an actuarial modeling project applying **Generalized Linear Models (GLM)** to predict **French Motor Third-Party Liability (MTPL) claim frequency** using the dataset `freMTPL2freq.xlsx`.

---

## 📁 Repository Contents

- **Project1.Rmd** – Main R Markdown script containing the full analysis  
- **Project1.html** – Rendered HTML report  
- **freMTPL2freq.xlsx** – Dataset used for modeling  
- **README.md** – Project documentation (this file)

---

## 📘 Project Overview

This project demonstrates end-to-end actuarial frequency modeling using:

- Poisson GLM  
- Over-dispersed (quasi-Poisson) GLM  
- Exposure modeling through offsets  
- Categorical variable handling  
- Goodness-of-fit evaluation  
- Interpretation of model coefficients  

The analysis explores driver features, vehicle characteristics, and regional information to understand claim frequency patterns.

---

## 🧠 Methods Used

- **Generalized Linear Models**
  - Poisson
  - Quasi-Poisson  
- **Exposure adjustment using log-offset**  
- **Deviance residuals and diagnostics**
- **Model comparison (AIC, deviance)**  

---

## 📊 Dataset

`freMTPL2freq.xlsx` includes variables such as:

- Exposure  
- Number of claims  
- Driver age  
- Vehicle power  
- Vehicle age  
- Region  
- Bonus-Malus coefficient  

---

## ▶️ How to Run

1. Install required R packages:

```r
install.packages(c("tidyverse", "readxl", "ggplot2", "dplyr"))



2. Open Project1.Rmd in RStudio.

3. Click Knit → Knit to HTML.

4. The output file Project1.html will be generated automatically.
