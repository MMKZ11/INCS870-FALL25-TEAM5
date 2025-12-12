# Final results (LightGBM + EFB & GOSS on CICIoT2023)

This folder summarizes the **final experimental results** of the INCS870 project.
All results are obtained on the same subset of the **CICIoT2023** dataset using
**10 selected features** and a fixed train/test split.

We compare four LightGBM configurations:

1. **Baseline** – GBDT, no EFB, no GOSS  
2. **EFB only** – Baseline + Exclusive Feature Bundling  
3. **GOSS only** – Baseline + Gradient-based One-Side Sampling  
4. **EFB + GOSS** – both techniques enabled
