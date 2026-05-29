# Hybrid Quantum-Classical Framework for Woodland Mapping & QUBO Optimization

A research-oriented hybrid quantum-classical deep learning framework for **woodland mapping and object region optimization** using **Attention U-Net**, **quantum neural layers**, and **QUBO-based candidate selection**.

This project combines classical computer vision techniques with quantum computing concepts to explore how hybrid quantum architectures can assist in image segmentation and optimization problems in remote sensing applications.

---

# Overview

The project implements a complete end-to-end pipeline for:

* Satellite/remote sensing image segmentation
* Woodland region extraction
* Hybrid quantum-classical feature learning
* Candidate region proposal generation
* QUBO (Quadratic Unconstrained Binary Optimization) formulation
* Quantum-inspired optimization for bounding box selection

The system integrates:

* **PyTorch** for deep learning
* **PennyLane** for quantum circuit integration
* **Qiskit / QAOA concepts** for optimization
* Classical image processing methods
* Hybrid optimization workflows

---

# Key Features

## Hybrid Quantum-Classical Architecture

* Attention U-Net based segmentation backbone
* Quantum bottleneck layer integrated into CNN pipeline
* Variational quantum circuit feature transformation
* Classical-to-quantum embedding

## Woodland Segmentation

* Semantic segmentation of woodland regions
* Pixel-wise prediction masks
* Threshold-based extraction pipeline

## QUBO Optimization

* Candidate bounding box generation
* Overlap-aware scoring
* QUBO matrix construction
* Quantum-inspired region selection

## Research-Oriented Pipeline

* Modular experimentation workflow
* Supports comparative evaluation
* Quantum and classical optimization integration
* Extendable architecture for future quantum experiments

---

# Project Structure

```bash
quantum-computing-project/
│
├── Code/
│   ├── Final_code.ipynb              # Main training + inference notebook
│   └── qc_model_checkpoints/
│       └── latest.pt                 # Saved model checkpoint
│
├── Diagrams/
│   └── architecture_diagram.png      # System architecture diagram
│
├── Referenced Papers/
│   ├── 2502.02895v1.pdf
│   └── 2507.13852v1.pdf
│
└── README.md
```

---

# System Architecture

The architecture consists of the following stages:

1. Input satellite imagery
2. Attention U-Net encoder-decoder segmentation
3. Quantum bottleneck layer using parameterized quantum circuits
4. Woodland prediction mask generation
5. Candidate bounding box extraction
6. QUBO matrix formulation
7. Quantum-inspired optimization
8. Final optimized region selection

---

# Technologies Used

| Technology       | Purpose                       |
| ---------------- | ----------------------------- |
| Python           | Core development language     |
| PyTorch          | Deep learning framework       |
| PennyLane        | Quantum machine learning      |
| Qiskit           | Quantum optimization concepts |
| OpenCV           | Image processing              |
| NumPy            | Numerical computation         |
| Matplotlib       | Visualization                 |
| Jupyter Notebook | Experimentation environment   |

---

# Installation

## Clone Repository

```bash
git clone https://github.com/abdullahedhiii/quantum-computing-project.git
cd quantum-computing-project
```

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

If a requirements file is unavailable, install the core packages manually:

```bash
pip install torch torchvision pennylane qiskit opencv-python matplotlib numpy
```

---

# Running the Project

## Launch Notebook

```bash
jupyter notebook
```

Open:

```bash
Code/Final_code.ipynb
```

---

# Model Workflow

## Training Phase

* Load satellite imagery dataset
* Preprocess images and masks
* Train Attention U-Net
* Integrate quantum bottleneck
* Save checkpoints

## Inference Phase

* Generate segmentation masks
* Extract candidate regions
* Construct QUBO formulation
* Apply optimization strategy
* Produce final selected regions

---

# Quantum Component

The project explores hybrid quantum learning through:

* Parameterized quantum circuits
* Quantum embeddings
* Variational quantum layers
* Quantum-enhanced feature representation
* QAOA-inspired optimization workflows

The implementation is primarily research-oriented and designed for experimentation on NISQ-era quantum simulation environments.

---

# Research Motivation

Traditional deep learning methods perform well for segmentation tasks, but optimization-heavy post-processing stages can become computationally expensive.

This project investigates whether:

* Quantum feature transformations
* Hybrid variational architectures
* QUBO-based optimization methods

can contribute toward improved candidate selection and optimization workflows in remote sensing applications.

---

# Results & Experiments

The notebook includes experiments related to:

* Segmentation performance
* Prediction visualization
* Candidate box extraction
* Optimization comparisons
* Hybrid quantum-classical evaluation

---

# Future Improvements

* Real quantum hardware execution
* Improved QAOA implementations
* Better QUBO scaling
* Dataset expansion
* Benchmarking against classical optimizers
* Hyperparameter optimization
* Distributed training support

---

# Referenced Research Papers

The repository includes supporting research papers used for experimentation and architectural inspiration inside:

```bash
Referenced Papers/
```

---

# Contributing

Contributions, suggestions, and research collaborations are welcome.

## Steps

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# License

This project is intended for academic and research purposes.

---

# Authors

**Abdullah Anis Edhi 22K-4392**<br/>
**Muhammad Taha Khan 22K-4609**<br/>
**Touseef Naveed 22K-4328**<br/>


---
