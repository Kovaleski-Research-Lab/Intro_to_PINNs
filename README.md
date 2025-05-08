# Intro_to_PINNs
Repository for the code associated with the guest lecture presented at the University of Missouri "Introduction to Physics Informed Neural Networks (PINNS)", Atomistic Materials Analytics, EECS 8615.

## Installation

Installation of the required packages to run the provided code will vary based on your system. 
I prefer to use Conda to manage my python environments. However, if you
use something different, refer to the `requirements.txt` file for the required packages.
NOTE: As of 05/08/25 the most recent version of PyTorch is not compatible with numpy>=2.

### Installing with Conda

```bash
    conda create -n pinn python=3.12
    conda activate pinn
    python -m pip install -r requirements.txt
```

It's not necessarily good practice to use `pip` with conda, however it seems to be
the best option for this project.

### Docker

Please reach out if there are issues with installation and I will provide a dockerfile and docker image
to run the code in a container. Might do this anyway.

## References
I can't reccomend Dr. Ben Moseley's blog/github/published work enough when it comes to learning about PINNs. He is my first go to when I need to refresh my memory on the subject. With that said, this code is based on the following references:

https://benmoseley.blog

https://github.com/benmoseley

https://beltoforion.de/en/harmonic_oscillator/


Lin, Xing, Yair Rivenson, Nezih T. Yardimci, Muhammed Veli, Yi Luo, Mona Jarrahi, and Aydogan Ozcan. 2018. “All-Optical Machine Learning Using Diffractive Deep Neural Networks.” Science 361 (6406): 1004–8. https://doi.org/10.1126/science.aat8084.

G. E. Karniadakis, I. G. Kevrekidis, L. Lu, P. Perdikaris, S. Wang, and L. Yang, “Physics-informed machine learning,” Nat Rev Phys, vol. 3, no. 6, pp. 422–440,  May 2021, doi: 10.1038/s42254-021-00314-5.

Chen, Z., Liu, Y. & Sun, H. Physics-informed learning of governing equations from scarce data. Nat Commun 12, 6136 (2021). https://doi.org/10.1038/s41467-021-26434-1

Raissi et al, Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear and partial differential equations, JCP (2018)


