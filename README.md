# Computational Cryptography

This is a landing repository for the development of the course content of computational cryptography.

However, to begin with, we treat this as a repository where we prototype using computational tools for number theory and discrete mathematics in general. [Sage](https://doc.sagemath.org/html/en/index.html) is one of the widely used computational tool by mathematicians, so we do a bit of introduction into it.


## SageMath setup

The easiest way to install sage for a user is through conda/micromamba.

```bash
conda create -n sage python=3.12 sage
```

The above line creates a conda environment named `sage` with python version 3.12, and installs the package **sage**.

Then you activate the environment: `conda activate sage` and use it. Sage adapts jupyter notebook into something called sage notebook. They are very similar with some important distinctions. See sage docs for more details.

Sage has it's own language, which is like an extension of python, and as a result one can program in sage, or in pure python as well. However it's more intuitive to write in sage's language.



