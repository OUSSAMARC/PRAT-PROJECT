# Cerberus: Multi-Task Learning for Computational Pathology

<p align="center">
    <img src="https://github.com/user-attachments/assets/c5fb5637-1edd-4597-91e8-382d3a35cfb5" alt="cerberus" width="500"/>
</p>


## Overview

Cerberus is a Multi-Task Learning (MTL) model designed for Computational Pathology (CPath) applications. It leverages deep learning techniques to perform simultaneous segmentation, classification, and object detection on histological images. The primary objective of this project is to review, optimize, and apply transfer learning to the Cerberus model, evaluating its ability to generalize across different pathology datasets.

This project utilizes multiple histopathology datasets, including:

    -NCT-CRC-HE-100K: Used for training and fine-tuning the classification model.
    
    -EBHI-Seg Dataset: Used for transfer learning evaluation on segmentation and classification tasks.
    
    -GlaS Dataset: Provides gland segmentation benchmarks.

## Model Architecture

The Cerberus architecture was initially published in the article "One model is all you need: Multi-task learning enables simultaneous histology image segmentation and classification." You can find the paper here: [https://www.sciencedirect.com/science/article/pii/S1361841522003139]

## Main Result

Segmentation Performance: Outperformed U-Net, Seg-Net, and MedT across multiple histological classes of the EBHI-Seg Dataset.

## Important conclusions

In this work, we explored the domain of **Computational Pathology (CPath)**, examining its objectives, challenges, and its growing role in medical diagnostics. We then investigated **Cerberus**, a Multi-Task Learning (MTL) model, and evaluated its performance in both classification and segmentation tasks through transfer learning. Our results highlight several critical aspects regarding the potential of MTL models, dataset requirements, and the future applications of Cerberus in medical imaging.

- **Strength of Multi-Task Learning (MTL):** Cerberus demonstrated promising results, reinforcing the power of MTL in medical image analysis by leveraging shared feature representations across tasks.
- **Need for Large-Scale Histopathological Datasets:** Unlike general computer vision tasks, computational pathology lacks a standardized dataset equivalent to ImageNet. Developing a collaborative repository of annotated histological images would enhance the training of MTL models like Cerberus, improving their generalization.
- **Potential for Automatic Annotation:** Cerberus could play a crucial role in automating histological image annotation. Given the high cost and time required for manual labeling, a well-trained MTL model could significantly accelerate dataset creation and improve AI-assisted diagnostic tools.
- **Alignment of Training Tasks:** Proper alignment of training tasks and datasets is essential to maximizing the advantages of MTL. Ensuring consistency in the multi-task learning framework and transfer learning phase prevents performance degradation.




