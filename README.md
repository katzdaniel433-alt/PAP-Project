# PAP Project

## Project Aim

This project predicts 500-day survival status for malignant pleural mesothelioma patients using gene expression and DNA methylation data from TCGA.

The analysis compares three predictor sets:

- Expression-only
- Methylation-only
- Multiomic: combined expression and methylation features

Two modelling approaches are compared:

- Elastic Net logistic regression
- Random Forest classification


---

## Repository Structure

```text
PAP-Project/
├── data/
│   ├── raw/              # Raw TCGA clinical and omics files
│   ├── interim/          # Cleaned and matched intermediate datasets
│   └── processed/        # Final model-ready x/y objects
├── outputs/
│   ├── tables/           # Model summaries, feature tables and diagnostics
│   ├── figures/          # Report and presentation figures
│   └── model_objects/    # Saved caret model objects
├── scripts/              # R / Rmd analysis scripts
├── renv.lock             # Reproducible R package environment
└── PAP-Project.Rproj
