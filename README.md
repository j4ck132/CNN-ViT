# Vision Model Experiments

This repository contains implementations and training logs for both Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs), along with visualizations used in our paper.

## Repository Structure

- `cnn_models.py` – Contains all CNN architectures used in our experiments.
- `vit_models.py` – Contains all Vision Transformer architectures used in our experiments.
- `images/` – Includes visualizations and training logs featured in our paper (e.g. loss curves, accuracy plots, training dynamics).

## Dataset Handling

All datasets are automatically downloaded and loaded within the dataset class definitions. You do not need to manually download any files. The dataset will be retrieved the first time you run a training script.
