# 🔥 PyTorch Examples Repository

> **Author:** Christopher Gaughan  
> [LinkedIn](https://www.linkedin.com/in/christophergaughan/) | [Portfolio](https://christophergaughan.github.io)

![PyTorch](https://img.shields.io/badge/PyTorch-2.5.1+cu121-red)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

This repository contains practical, educational examples built with PyTorch 2.5.1, tested using NVIDIA A100 GPUs on Google Colab. All projects are fully anonymized and designed to showcase my machine learning engineering capabilities — from core tensor operations to transformer components like positional encoding.

---

## 🧠 Projects Overview

### 📍 Positional Encodings
> *Built from scratch to explore transformer positional encoding using sine/cosine signals*

- Implements sinusoidal encodings from “Attention Is All You Need” [Original Paper](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)
- Visualizes encodings across positions & dimensions
- Explains how sequential token order is encoded in models like BERT
- Code: `Positional_Encodings.ipynb`

---

### 🧠 PyTorch Tensors Intro
> *Hands-on intro to tensor creation, indexing, reshaping, and operations*

- Basics of tensors, operations, and gradients
- Great for newcomers or interviews
- Code: `PyTorch_Tensor_Intro.ipynb`

---

### 🧩 PyTorch Workflow
> *End-to-end ML project setup in PyTorch*

- Data loading, model definition, training loop
- Clean separation of concerns
- Code: `PyTorch_Workflow.ipynb`

---

### 🖼️ Computer Vision Classification
> *Image classification using CNNs in PyTorch*

- End-to-end workflow for image classification
- Uses torchvision transforms and loaders
- Code: `ComputerVision_PyTorch.ipynb`

---

### 🧪 Custom Dataset Handling
> *Shows how to create and load custom datasets in PyTorch*

- Custom `Dataset` and `DataLoader` implementation
- Ideal for adapting real-world data into training pipelines
- Code: `PyTorch_Custom_Datasets.ipynb`

---

## ⚙️ Requirements

Tested with:

- Python 3.11  
- PyTorch 2.5.1+cu121  
- Jupyter Notebook  
- NumPy  
- Matplotlib  

Install dependencies:
```bash
pip install torch matplotlib numpy
```

## Usage
Clone the repository:
```
git clone https://github.com/christophergaughan/PyTorch.git
cd PyTorch
```

### Launch the notebooks:
`jupyter notebook`

All notebooks are designed to run with or without GPU. For optimal speed, use Google Colab + GPU runtime.

### GPU Acceleration
All code has been tested on:

* NVIDIA A100 GPUs (via Google Colab)

* Accelerated training for heavy models (e.g., CNNs, transformer prototypes)

### Future Additions
* 🧠 Generative Adversarial Networks (GANs)

* 🕹️ Reinforcement Learning agents

* 🏥 Transfer learning with medical imaging

### 📚 References
* PyTorch Documentation

* Attention Is All You Need — Transformer architecture introduction

### 🪪 License
This project is licensed under the MIT License. See LICENSE file for details.



