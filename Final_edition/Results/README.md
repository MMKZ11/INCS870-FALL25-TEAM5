# Final results (10-feature LightGBM on CICIoT2023 10-class subset)

This folder contains the **final results** for the INCS870 project.

All experiments here are run on the **10-class subset** of CICIoT2023
described in `../data/README.md`, using a **10-feature subset**
selected from the original 40 columns.

The main comparison focuses on:

- Baseline: **GBDT** (LightGBM, no EFB)
- EFB+GBDT: **GBDT with Exclusive Feature Bundling (EFB)** enabled

The goal is to show that EFB can be applied on this IoT intrusion
detection task **without degrading the macro-level performance**
(accuracy, F1, recall), while reducing the effective feature
dimensionality in more sparse/high-dimensional settings.
