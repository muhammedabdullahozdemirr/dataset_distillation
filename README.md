#  Efficient Model Training via Dataset Distillation

**Course:** BLG454E – Learning from Data  
**Team Members:** Muhammed Abdullah Özdemir, Nurettin Macit

## Project Description

This project explores dataset distillation, a novel technique to compress large-scale datasets into small synthetic datasets while preserving model performance. Instead of training a neural network on 25,000 real CIFAR-10 images, we distilled the dataset into 1,000 synthetic images using an iterative gradient matching approach.

Our distilled dataset achieved **62.74% test accuracy**, despite a **96% reduction** in data volume—demonstrating the potential of synthetic data in efficient model training.

##  Key Concepts

- Dataset Distillation  
- Gradient Matching  
- Model Compression  
- Synthetic Data Optimization  

##  Technologies & Tools

- Python  
- PyTorch  
- Google Colab  
- CIFAR-10 Dataset (5-class subset)  
- CNN architecture with ~800K parameters  

##  Results Summary

| Metric              | Value                         |
|---------------------|-------------------------------|
| Baseline Accuracy   | 87.36% (Full Dataset)         |
| Final Accuracy      | 62.74% (Distilled Dataset)    |
| Data Reduction      | 96% (25,000 → 1,000 samples)  |
| Training Time       | ~2.5 hours                    |
| Iterations          | 8 (Iterative Refinement)      |


