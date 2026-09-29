# FactoryGuard AI

FactoryGuard AI is an end-to-end industrial AI learning project for visual inspection and predictive maintenance.

## Current Milestone

**Milestone 01 — Establish the first ML baseline**

This milestone focuses on classical, interpretable machine-learning workflow before deep learning:

- Dataset inspection and EDA
- Train/dev/test split with fixed random seed
- Random-guess baseline
- Logistic Regression baseline with flattened image features
- Evaluation using Accuracy, Macro F1, Confusion Matrix
- Misclassification review and experiment notes

Primary baseline notebook: `notebooks/01_baseline.ipynb`

## Repository Structure

```text
factoryguard_ai/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   └── 01_baseline.ipynb
├── src/
│   ├── __init__.py
│   ├── data/
│   ├── models/
│   └── evaluation/
├── experiments/
│   └── README.md
├── models/
│   └── .gitkeep
└── docs/
    └── project_plan.md
```

## Milestone Rules

1. Keep train/dev/test separated.
2. Do not use the test set for model selection.
3. Keep experiments reproducible (fixed seeds where relevant).
4. Prefer simple baselines before complex models.
5. Record what changed, why, and what to try next after each experiment.
