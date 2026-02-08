---
title: "Alzheimer's Disease Analysis"
excerpt: "Leveraging Deep Learning (including LLMs) and other Machine Learning models for Alzheimer's disease prediction using ROSMAP data.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

## Project Overview

This research project focuses on the early prediction and molecular characterization of Alzheimer's Disease (AD) using single-cell genomics data. By leveraging the **ROSMAP (Religious Orders Study and Memory and Aging Project)** dataset, we aim to identify robust disease markers that traditional analysis might miss.

## Methodology

The core of this work involves moving beyond standard statistical tests to apply advanced **Deep Learning** architectures to biological sequences.

1.  **Foundational Models:** We are fine-tuning Large Language Models (LLMs) adapted for single-cell data, such as **scGPT**, **Geneformer** and others. These models treat gene expression profiles as "language," allowing us to transfer learning from massive datasets to the specific context of Alzheimer's.
2.  **Machine Learning Benchmarks:** We compare these deep learning approaches against traditional ML baselines (such as Random Forests and SVMs) to quantify the performance gain offered by transformer-based architectures.
3.  **Classification Strategies:** A key part of this study involves experimenting with different classification heads on top of the pre-trained models to optimize for accuracy and interpretability.

## Tools & Technologies

- **Data:** ROSMAP (Single-cell RNA-seq)
- **Models:** scGPT, Geneformer, few other TBD
- **Frameworks:** PyTorch, HuggingFace
- **Techniques:** Fine-tuning, Transfer Learning, Explainable AI (XAI)
