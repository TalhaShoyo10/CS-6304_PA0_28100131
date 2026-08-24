# CS-6304 — Assignment 0: Experiment-Based Understanding of Deep-Learning Architectures

Author: Talha Masood (28100131)

This repository contains all code, results, and the final report for Assignment 0,
covering four deep learning architectures: ResNet-152, Vision Transformers, CLIP,
and Variational Autoencoders.

## Contents

- `notebooks/task1_resnet.ipynb` — ResNet-152 baseline, skip-connection ablation,
  feature-hierarchy (t-SNE) analysis, and transfer-learning comparisons on CIFAR-10.
- `notebooks/task2_vit.ipynb` — ViT classification and attention visualization,
  patch-masking experiment, and CLS-token vs. mean-pooling comparison.
- `notebooks/task3_clip.ipynb` — CLIP zero-shot classification on STL-10 across
  three prompting strategies, modality-gap analysis, and Procrustes alignment.
- `notebooks/task4_vae.ipynb` — MLP-based VAE on MNIST: training, latent space
  visualization, reconstruction quality, and sample generation.
- `results/` — saved metrics (JSON), trained weights, and generated figures for
  each task.
- `report/` — the full report in NeurIPS format (`report.tex`, `neurips_2026.sty`,
  and the compiled `report.pdf`).

## Reproducing

Each notebook is self-contained and was run on Google Colab with a T4 GPU. Running
a notebook top to bottom will regenerate all results and figures in the
corresponding `results/` subfolder.

## Report

The full write-up, covering the implementation and findings for all four tasks, is
in `report/report.pdf`.
