# WEBCRAFT: Fault-Tolerant Computing-in-Memory Framework

This repository contains the source code and evaluation framework for the paper: **"WEBCRAFT: Weight Transformations in Bit-Sliced Crossbar Arrays for Fault Tolerant Computing-in-Memory: Design Techniques and Evaluation Framework"**.

## Repository Contents

The project is organized into three comprehensively commented Jupyter Notebooks:

| Notebook | Description | Dataset |
| :--- | :--- | :--- | :--- |
| **`WEBCRAFT_resnet18_CIFAR100.ipynb`** | Recreates experiments for ResNet-18 and ResNet-50 architectures. | CIFAR-100
| **`WEBCRAFT_ViT_CIFAR100.ipynb`** | Recreates experiments for Vision Transformer (ViT-B) architectures. | CIFAR-100
| **`WEBCRAFT_ViT_imagenet.ipynb`** | Large-scale validation experiments for ViT-B. | ImageNet (Val)

## Usage Instructions

The notebooks are designed to be standalone and can be executed on **Google Colab** or a local machine with standard PyTorch libraries installed.

## CIFAR-100 Experiments
The `resnet18` and `ViT` notebooks for CIFAR-100 are fully self-contained.
1. Open the notebook.
2. Run all cells.
3. The script will automatically download the CIFAR-100 dataset and pre-trained weights to run the full experimental pipeline.

## ImageNet Experiments
For `WEBCRAFT_ViT_imagenet.ipynb`, you must provide the ImageNet validation dataset manually due to licensing restrictions.
1. Obtain the **ILSVRC 2012 Validation Set** (`.tar.gz`) from [image-net.org](https://image-net.org/).
2. Update the file path in the notebook to point to your local copy of the dataset.

## Citation

If you use this code or our methodology in your research, please cite our paper:

Malhotra, A., & Gupta, S. K. (2025). Weight Transformations in Bit-Sliced Crossbar Arrays for Fault Tolerant Computing-in-Memory: Design Techniques and Evaluation Framework. [arXiv](https://arxiv.org/abs/2512.18459).
