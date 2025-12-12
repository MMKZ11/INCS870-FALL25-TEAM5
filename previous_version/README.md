# Previous notebooks (BLS & early trials)

This folder stores earlier versions and exploratory notebooks that were used
before the final LightGBM + EFB & GOSS pipeline was fixed.

They are **not** used for the final experiments, but they document the
evolution of the project.

## Files

- `870BasicBLS.ipynb`  
  Original Broad Learning System (BLS) baseline implementation.

- `BroadLearningSystemGreedyBundling2.py`  
  Python implementation of a **greedy feature bundling** strategy for BLS.

- `BroadLearningSystemMergeExclusiveFeatures.py`  
  Implementation of an **exclusive feature merge** (EFB-like) mechanism for BLS.

- `LightGBM`EFB(4_features).ipynb`  
  Early trial of LightGBM with EFB on a small set of four selected features.

- `greedy_bundling,_EFB,_and_GOSS.ipynb`  
  Mixed experiment combining greedy bundling ideas with LightGBM EFB and GOSS.

- `lgbm_BLS_4.ipynb`  
  Intermediate version integrating BLS and LightGBM into a single pipeline.

- `lgbm_BLS_Gradient_based.ipynb`  
  Trial using gradient-based (GOSS-related) sampling / weighting within the BLS/LGBM framework.

  This folder is kept only to show the intermediate steps and design choices
that led to the final LightGBM configuration.
