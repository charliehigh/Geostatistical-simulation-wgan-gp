# geostatistical Simulation with Multi-Loss WGAN-GP

## Overview
This repository presents a multi-loss Wasserstein Generative Adversarial Network (WGAN-GP) framework for geostatistical simulation.

The model generates geologically realistic realizations that preserve spatial structure and statistical properties of training images, enabling improved uncertainty modeling for mining applications.

## Motivation
Geostatistical simulation is critical for modeling uncertainty in mineral deposits and supporting mine planning decisions.

Traditional methods often struggle to capture complex spatial patterns and may be computationally intensive. This work explores deep learning as an alternative approach for modeling geological variability.

## Key Contributions
- Developed a multi-loss GAN architecture combining:
  - Feature Matching Loss
  - Structural Similarity (SSIM) Loss
  - Pixel Intensity Loss
- Implemented conditional and unconditional simulation
- Introduced image augmentation to improve training diversity
- Applied variogram-based validation for spatial continuity

## Methodology
- WGAN-GP architecture for stable training
- Multi-loss function to improve realism and diversity
- Training on augmented geological training images
- Evaluation using:
  - Structural Similarity Index (SSIM)
  - Variogram analysis

## Applications
- Mineral resource modeling  
- Geological uncertainty analysis  
- Mine planning decision support  

## Repository Structure
- `src/` – model implementation  
- `notebooks/` – experiments and testing  
- `figures/` – generated realizations and plots  
- `docs/` – thesis summary and notes  

## Sample Results

![Generated Realizations](figures/generated_realizations.png)
## Status
Work in progress — code and documentation are being structured for public release.

## Author
Charles Okai Addai
