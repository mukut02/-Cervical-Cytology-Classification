# REDSS-Net
**Entropy-Aware Sugeno–Dempster and Fuzzy Evidence Fusion of Deep Models for Cervical Cytology Classification**

This repository presents a **dual-branch deep learning framework** for cervical cytology classification from Pap smear images. The architecture combines **Convolutional Neural Networks (CNNs)** and **Swin Transformers** to jointly capture **local spatial patterns** and **global contextual representations**, improving robustness for medical image analysis.

## Results

- **SIPaKMeD Dataset**
  - Achieved **99.26% test accuracy**

- **Mendeley Liquid-Based Cytology (LBC) Dataset**
  - Achieved **99.48% test accuracy**
## Additional Test
- **Cifar 10**
  - Achieved **98.84 % test accuracy**
- **Caltech 101**
  - Achieved **97.54 % test accuracy**

## Key Features

- **Dual-Branch Architecture**
  - Hybrid framework integrating a **CNN branch** and a **Swin Transformer branch**.
  - Extracts complementary features from Pap smear images.

- **Entropy-Aware Evidence Modeling**
  - Estimates prediction confidence using **entropy-based uncertainty**.
  - Incorporates **class-wise recall** to measure classifier reliability.

- **Uncertainty-Guided Fusion Strategy**
  - Fusion method inspired by **Dempster–Shafer evidence theory**.
  - Utilizes the **Sugeno fuzzy integral** for robust decision fusion.
  - Handles **prediction conflict and uncertainty** across multiple models.

- **Experimental Evaluation**
  - Evaluated on publicly available cervical cytology datasets:
    - **SIPaKMeD**
    - **Mendeley Liquid-Based Cytology (LBC)**
  - Demonstrates improved performance and reliability over conventional methods.
