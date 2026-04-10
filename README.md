# Green-s-functions-Neural-Operator
Neural operator learning of Green’s functions in frequency domain for PDEs with structured spectral coupling.

This repository implements a neural operator framework for learning Green’s functions of partial differential equations in the frequency domain.

The model parameterizes the Green’s operator as a structured spectral kernel, capturing cross-frequency and cross-component couplings for vector-valued PDEs such as Stokes flow and linear elasticity.

Unlike standard Fourier Neural Operators, the proposed method explicitly models block-coupled Green’s function matrices, enabling improved representation of anisotropic and non-self-adjoint systems.

We evaluate the method on benchmark PDEs including:
- Linear elasticity problems
- lid-driven cavity flow
- Composite RVE
- Poisson equation

- ## Environment

This project was developed and tested using:

- Python 3.x
- PyTorch **2.7.1+cu118**
- CUDA **11.8**
- Linux/Windows (any environment with CUDA 11.8 should work)


**Dataset Overview**

This project includes four datasets generated from different partial differential equations (PDEs):

1. Poisson Equation Dataset
2. Linear Elasticity Equation Dataset
These two datasets are included inside the compressed archive bundled with the source code.

3. Composite RVE Dataset
4. Lid-Driven Cavity Flow Dataset
These two larger datasets are provided separately and can be downloaded directly from the GitHub Release page.
