# Deep Feature Reweighting – Practical Work in AI

This repository contains my implementation of Deep Feature
Reweighting (DFR), based on the paper:

"Last Layer Re-Training Is Sufficient for Robustness to
Spurious Correlations" (Kirichenko et al., ICLR 2023).

## Experiments

### ColoredMNIST
- ERM baseline using a small CNN
- DFR using a group-balanced dataset
- Evaluation of mean and worst-group accuracy

### Waterbirds
- ERM baseline using ImageNet-pretrained ResNet-18
- DFR using frozen 512-dimensional features
- Evaluation across four groups

## Notebooks

1. `01_coloredmnist_erm.ipynb` – ColoredMNIST ERM baseline
2. `02_coloredmnist_drf.ipynb` – ColoredMNIST DFR
3. `03_waterbirds_erm.ipynb` – Waterbirds ERM baseline
4. `04_waterbirds_dfr.ipynb` – Waterbirds DFR

## Reference

Kirichenko et al. (2023):
https://openreview.net/forum?id=Zb6c8A-Fghk
