# Cerberus: Multi-Task Learning for Computational Pathology

## Overview

Cerberus is a Multi-Task Learning (MTL) model designed for Computational Pathology (CPath) applications. It leverages deep learning techniques to perform simultaneous segmentation, classification, and object detection on histological images. The primary objective of this project is to review, optimize, and apply transfer learning to the Cerberus model, evaluating its ability to generalize across different pathology datasets.

This project utilizes multiple histopathology datasets, including:

    -NCT-CRC-HE-100K: Used for training and fine-tuning the classification model.
    
    -EBHI-Seg Dataset: Used for transfer learning evaluation on segmentation and classification tasks.
    
    -GlaS Dataset: Provides gland segmentation benchmarks.

## Model Architecture

The Cerberus architecture was initially published in the article "One model is all you need: Multi-task learning enables simultaneous histology image segmentation and classification." You can find the paper here: [https://www.sciencedirect.com/science/article/pii/S1361841522003139]

<p align="center">
    <img src="https://github.com/user-attachments/assets/c5fb5637-1edd-4597-91e8-382d3a35cfb5" alt="cerberus" width="500"/>
</p>

## Main Result

Segmentation Performance: Outperformed U-Net, Seg-Net, and MedT across multiple histological classes of the EBHI-Seg Dataset.




