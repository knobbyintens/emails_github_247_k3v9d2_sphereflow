# SphereFlow: Flow-Matching for 3D Scene Generation

**Status: code released.**

This repository contains the implementation for the paper:

> **SphereFlow: Flow-Matching for 3D Scene Generation**  
> Victoria Ramos, Wei Zhang, Daniel Okafor  
> NeurIPS 2025

The released implementation covers the model, the data pipeline and the training/evaluation scripts used in the experiments.

## Repository layout

- `src/` - model, data pipeline, training and evaluation code
- `data/` - dataset preparation helpers and manifests
- `experiments/` - experiment configs and analysis notebooks

## Getting started

```bash
pip install -r requirements.txt
python -m src.train --config configs/default.yaml
```

## Citation

If you use this code, please cite the paper above.
