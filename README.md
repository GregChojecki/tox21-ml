# Tox21 ML: Toxicity Prediction with Machine Learning

## Overview
This project applies machine learning to the
[Tox21 dataset](https://tripod.nih.gov/tox21/challenge/) —
a benchmark dataset of ~8,000 compounds tested across
12 toxicological assays. The goal is to predict molecular
toxicity from chemical structure alone.

## Why This Matters
Testing compounds for toxicity in the lab is slow and expensive.
ML models that can predict toxicity from molecular structure
help prioritise which compounds to test, reducing cost and
animal testing in early drug discovery.

## The 12 Assays
- **Nuclear Receptors (NR):** AR, ER, AhR, Aromatase, PPAR-γ
- **Stress Response (SR):** ARE, ATAD5, HSE, MMP, p53

## Approach (Planned)
1. Exploratory Data Analysis
2. Baseline: Morgan Fingerprints + Random Forest
3. Deep Learning: PyTorch Feedforward Network
4. Graph Neural Network (GNN) on molecular graphs

## Tech Stack
Python, DeepChem, RDKit, PyTorch, scikit-learn, pandas

## Author
Greg Chojecki — AI Engineer in training |
MSc Analytical Chemistry | 6 years data science in chemistry