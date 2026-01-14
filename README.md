# Introduction to AI – Image Classification

This repository contains a comparative study of classical and neural network-based
machine learning models for image classification. The project is part of an
*Introduction to Artificial Intelligence* at my university course and focuses on understanding model behavior across datasets with increasing visual complexity.

## Datasets
Three benchmark datasets are used:

- **MNIST**: Handwritten digit images (grayscale, low complexity)
- **Fashion-MNIST**: Clothing images with higher visual variability
- **Food-MNIST**: RGB food images with complex textures and color patterns

## Models Implemented
The following models are implemented and evaluated:

- Decision Tree (Information Gain / Entropy)
- Multilayer Perceptron (MLP)
- Convolutional Neural Network (CNN – bonus task)

Each model is trained using a stratified train/validation split, tuned using
validation accuracy, and evaluated on a held-out test set.

## Key Findings
- Decision Trees provide interpretability but struggle with high-dimensional image data.
- MLPs improve performance through nonlinear modeling but lose spatial information
  due to feature flattening.
- CNNs achieve the best performance on complex image datasets by leveraging spatial
  locality and hierarchical feature learning.

The results highlight that **model suitability strongly depends on data structure**,
especially for image-based tasks.


## How to Run
1. Clone the repository:
```bash
git clone https://github.com/hannguyen2880/intro2ai-image-classification.git
cd intro2ai-image-classification/notebooks
```

2. Open and run the notebooks using Jupyter Notebook or Google Colab.
