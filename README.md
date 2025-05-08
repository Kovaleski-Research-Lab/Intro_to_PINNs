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
