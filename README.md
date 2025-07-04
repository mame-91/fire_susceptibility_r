This repository contains related R codes and the compiled dataset for the paper "Fire susceptibility assessment in the Carpathians using an interpretable framework" by Manczinger, M., Kovács, L., & Kovács, T. (2025), Scientific Reports, DOI 10.1038/s41598-025-10296-4. 

The .Rmd files contain the following information:

  1. METHODS.Rmd: Details data collection and matching for fire coordinates.
  2. METHODS_NC.Rmd: Details data collection and matching for negative controls.
  3. FEATURE SELECTION.Rmd: Details data preprocessing and feature selection to refine the predictor set with VIF, RFE, and Lasso.
  4. MODELS_H2O: Details MLR, DRF, GBM, and XGBoost model optimization and training in H2O.ai environment and related evaluation procedures.
  5. VULNERABILITY MAPPING.Rmd: Generates discrete spatial susceptibility maps highlighting areas with elevated fire susceptibility across the Carpathian region.
  6. Additional analysis.Rmd: Details model validation procedures.
  7. Check_duplicate_coordinates.Rmd: Checks duplicate fire coordinates from the MODIS dataset (2010-2020) for the Carpathian region.

The all_points_finalized.Rds file contains the fire and control points (n=10,346) with explanatory variables before splitting and scaling the dataset.
