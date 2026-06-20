# Microscopy Image Generation using Gaussian-Bernoulli Restricted Boltzmann Machine (GB-RBM)

An image generation project that uses a Gaussian-Bernoulli Restricted Boltzmann Machine (GB-RBM) to learn and generate realistic microscopy image patches from blood serum microscopy images.

## Project Objective

This project aims to learn the underlying distribution of microscopy image patches and generate synthetic microscopy images while preserving important structural characteristics of the original dataset.

## Features

- Data augmentation
- Image preprocessing
- Informative patch extraction
- Gaussian-Bernoulli RBM training
- Image reconstruction
- Microscopy image generation
- Quantitative performance evaluation

## Project Pipeline

```text
Blood Serum Microscopy Images

↓

Data Augmentation

↓

Image Preprocessing

↓

Patch Extraction

↓

Dataset Preparation

↓

GB-RBM Training

↓

Image Reconstruction

↓

Microscopy Patch Generation

↓

Performance Evaluation
```

## Evaluation Metrics

- Mean Squared Error (MSE)
- Structural Similarity Index (SSIM)
- Diversity Score
- KL Divergence

## Technologies Used

- Python
- NumPy
- PyTorch
- OpenCV
- Pillow
- Matplotlib
- Scikit-image
- SciPy

## Repository Structure

```text
microscopy-image-generation-gbrbm/

├── Microscopy_Image_Generation_GBRBM.ipynb
├── README.md
├── requirements.txt
├── dataset/
└── results/
```

## Future Improvements

- Train on larger microscopy datasets
- Explore Variational Autoencoders (VAEs)
- Explore Generative Adversarial Networks (GANs)
- Improve image generation quality
