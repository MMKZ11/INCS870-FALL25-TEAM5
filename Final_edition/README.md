## LightGBM EFB & GOSS Evaluation on CICIoT2023

This repository contains the **final version** of my INCS870 project.

The goal is to evaluate **LightGBM** with:

- **EFB** – Exclusive Feature Bundling  
- **GOSS** – Gradient-based One-Side Sampling  

on the **CICIoT2023** intrusion detection dataset, and to compare four settings under
the **same data split and feature set**:

1. Baseline: LightGBM GBDT (no EFB, no GOSS)  
2. EFB only: Baseline + EFB  
3. GOSS only: Baseline + GOSS  
4. EFB + GOSS: both techniques enabled

