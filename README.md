# Skin_Cancer_Classification
Vital Nexus is a deep learning framework designed to improve the accuracy of binary skin cancer classification (Benign vs. Malignant). Unlike standard monolithic architectures, Vital Nexus utilizes a Dual-Path Feature Extraction strategy to simultaneously analyze high-resolution textures and global spatial structures.
Vital Nexus: Dual-Path Attention Fusion for Skin Cancer Diagnostics
📌 Project Overview
Vital Nexus is a novel deep learning framework designed to resolve the challenges of binary skin cancer classification (Benign vs. Malignant). Standard models often struggle with high intra-class similarity; our architecture solves this by utilizing a Dual-Path Feature Extraction strategy.

The Innovation
Unlike monolithic CNNs, Vital Nexus processes dermatoscopic images through two specialized streams:

Texture Path (EfficientNetB0): Extracts micro-patterns, pigment networks, and irregular border textures.

Structural Path (MobileNetV2): Captures the global geometry, symmetry, and architectural integrity of the lesion.

Attention-Fusion Module: A custom channel-attention mechanism that dynamically weighs features from both paths, prioritizing diagnostic signals while suppressing background noise (hair, shadows, or markers).

📊 Benchmarking & Performance
Vital Nexus was rigorously evaluated against seven state-of-the-art (SOTA) architectures. Our model achieved a superior balance of Sensitivity (crucial for medical safety) and Overall Accuracy.
