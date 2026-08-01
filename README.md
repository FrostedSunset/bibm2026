# Lightweight Cross-Domain Fusion with Quantile-Free Uncertainty Quantification for Stain-Invariant Cervical Cancer Detection

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.8%2B-orange.svg)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📝 Paper Abstract

Cervical cell detection on TCT images is critical for computer-aided diagnosis of cervical cancer. Staining heterogeneity across imaging devices and clinical centers induces severe cross-domain distribution shifts, yet existing detection methods produce only deterministic predictions without uncertainty quantification. To address these issues, we propose a cross-domain fusion framework that integrates stain-invariant feature fusion with quantile-free uncertainty quantification. Our framework consists of three core modules: (1) a lightweight Cerv-CDFNet backbone, (2) a Stain-Aware Token Fusion (SATF) module, and (3) a Quantile-Free Uncertainty Quantification (QF-UQ) module.

Experiments on three cervical cytology datasets demonstrate that our method achieves high accuracy with low computational overhead, generalizes well across diverse staining conditions, and provides a practical solution for computer-aided diagnosis.
